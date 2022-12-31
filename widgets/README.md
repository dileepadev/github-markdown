# How to use?

- Copy a proper image URL.
- Change the type (e.g. `tools` or `social`), theme (e.g. `light` or `dark`) and widget (e.g. `github`).
- Use the `dark` property to set the background color of the widget to a dark color.
- Use the `light` property to set the background color of the widget to a light color.
- Follow `Markdown` or `HTML` styles to apply.

### Image URL

```html
https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png
```

### Structure

```markdown

URL: https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png

(https://ghmd.dileepabandara.dev)/widgets/tools/dark/github(.png)
                                    │       │     │     │
                                    │       │     │     └─⫸ `github` = Widget name (e.g. github)
                                    │       │     │
                                    │       │     └─⫸ `dark` = Theme name (e.g. dark or light)
                                    │       │                  
                                    │       │                   
                                    │       └─⫸ `tools` = Type name (e.g. tools or social)                
                                    │                         
                                    │
                                    └─⫸ `widgets` = Directory name

```

### Markdown

```markdown
![Flutter](https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png)  
![Flutter](https://ghmd.dileepabandara.dev/widgets/tools/light/github.png)
```

### HTML

```html
<img src="https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png"/>  
<img src="https://ghmd.dileepabandara.dev/widgets/tools/light/github.png"/>
```

### Custom Size

```html
<img src="https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png" width="75"/>  
<img src="https://ghmd.dileepabandara.dev/widgets/tools/light/github.png" width="75"/>  
```

### Examples

<img src="https://ghmd.dileepabandara.dev/widgets/tools/dark/github.png" width="75"/> &nbsp; <img src="https://ghmd.dileepabandara.dev/widgets/tools/light/github.png" width="75"/>
