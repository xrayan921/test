# This is a level 1 header (largest)
## This is a level 2 header
### This is a level 3 header
#### This is a level 4 header
##### This is a level 5 header
###### This is a level 6 header (smallest)
```

### 2. Emphasis

```markdown:example.md
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

### 3. Lists

Unordered lists:
```markdown:example.md
* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
```

Ordered lists:
```markdown:example.md
1. First item
2. Second item
3. Third item
```

### 4. Links

```markdown:example.md
[Sourcegraph](https://sourcegraph.com)
```

### 5. Images

```markdown:example.md
![Alt text](https://example.com/image.jpg)
```

### 6. Code

Inline code:
```markdown:example.md
Use the `print()` function in Python
```

Code blocks:
```markdown:example.md
```python
def hello_world():
    print("Hello, world!")
```
```

## Try It Yourself

You can practice Markdown in many online editors or in any text editor. If you want to see how your Markdown renders, you can use tools like:

```bash
npm install -g markdown-preview
