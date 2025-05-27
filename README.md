# DJSON Extension for VS Code

The DJSON extension adds language support for DJSON files in Visual Studio Code. DJSON (Dynamic JSON) is a JSON-like format that extends standard JSON with additional features such as comments and template interpolation.

## Features

- **Syntax Highlighting**: Full syntax highlighting for DJSON files
- **Comment Support**: Both line (`//`) and block (`/* */`) comments are supported
- **Template Interpolation**: Special handling for template expressions using `{{ }}` syntax
- **Language Configuration**: Bracket matching, auto-closing pairs, and surrounding pairs

## What is DJSON?

DJSON is a superset of JSON that adds several useful features:

1. **Comments**: Unlike standard JSON, DJSON supports both line and block comments
   ```djson
   {
     "name": "example", // This is a line comment
     /* This is a 
        block comment */
     "value": 42
   }
   ```

2. **Template Interpolation**: Use `{{ }}` to include dynamic content
   ```djson
   {
     "greeting": "Hello, {{ name }}!",
     "items": [{{ dynamicItems }}]
   }
   ```

3. **Standard JSON Compatibility**: All valid JSON is also valid DJSON

## Usage

1. Files with the `.djson` extension will automatically be recognized by VS Code with this extension
2. Create a new file with the `.djson` extension to start using DJSON
3. Enjoy syntax highlighting, comment support, and other language features

## Release Notes

### 0.0.1

- Initial release with basic language support
- Syntax highlighting for DJSON files
- Comment and template interpolation support

---

**Enjoy using DJSON!**
