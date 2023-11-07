


    <picture>
  <source media=“(prefers-color-scheme: dark)” srcset=“https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png”>
  <source media=“(prefers-color-scheme: light)” srcset=“https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png”>
  <img alt=“Shows an illustrated sun in light mode and a moon with stars in dark mode.” src=“https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png”>
</picture>

```[tasklist]

\ escape character

Syntax highlighting in code block.
```ruby
require ‘redcarpet’
markdown = Redcarpet.new(“Hello World!”)
puts markdown.to_html
```

# Linking to Markdown
ou can link to specific lines in Markdown files by loading the Markdown file without Markdown rendering. To load a Markdown file without rendering, you can use the ?plain=1 parameter at the end of the url for the file. For example, github.com/<organization>/<repository>/blob/<branch_name>/README.md?plain=1.

You can link to a specific line in the Markdown file the same way you can in code. Append #L with the line number or numbers at the end of the url. For example, github.com/<organization>/<repository>/blob/<branch_name>/README.md?plain=1#L14 will highlight line 14 in the plain README.md file.