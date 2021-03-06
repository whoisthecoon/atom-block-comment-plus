## 0.5.1
- Improving config option for wrapping commented code: you can now choose between spaces, new lines or none (default)

## 0.5.0
- Added a config option to add a space after and before comment signs (issue #4)

## 0.4.0
- Added Julia support ([#5](https://github.com/whoisthecoon/atom-block-comment-plus/issues/5))

## 0.3.0
- Keeps selection after commenting/uncommenting

## 0.2.0
- Fixing [issue #1](https://github.com/whoisthecoon/atom-block-comment-plus/issues/1):
  the package threw an error when trying to uncomment a line-commented line.
- Added specs
- Add Elm support thanks to [leobm](https://github.com/leobm)

## 0.1.0
- Based on grammar at start and end points of selection
- Handles embedded languages (such as PHP in HTML)
- Multiple selections
- uncomment when cursor is positioned inside a comment block.
- Supported languages:
  - C-based languages
  - Python
  - Coffee Script
  - HTML
  - Markdown
  - Ruby
