# BUAA-Marp-Theme

![image-20230401205208836](readme.assets/image-20230401205208836.png)

![image-20230401205155968](readme.assets/image-20230401205155968.png)

based on: https://github.com/kaisugi/marp-theme-academic

feature: 

- BUAA logo (red / blue)
- optimize font
- table adjust

## Usage

export to html: 

```shell
npx @marp-team/marp-cli@latest buaa.md -o buaa.html --theme-set ./theme --pdf-outlines --allow-local-files
```

export to pdf: 

```shell
npx @marp-team/marp-cli@latest buaa.md -o buaa.pdf --theme-set ./theme --pdf-outlines --allow-local-files
```

for more commands, see: https://github.com/marp-team/marp-cli

to have a preview in vscode, you could add below to your `settings.json`: 

```json
{
    // ...
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/Lincest/BUAA-Marp-Theme/master/theme/buaa_red.css",
        "https://raw.githubusercontent.com/Lincest/BUAA-Marp-Theme/master/theme/buaa.css",
        "https://raw.githubusercontent.com/Lincest/BUAA-Marp-Theme/master/theme/buaa_blue.css"
    ],
}
```

## Example

![](readme.assets/buaa.001.jpg)
![](readme.assets/buaa.002.jpg)
![](readme.assets/buaa.003.jpg)
![](readme.assets/buaa.004.jpg)
![](readme.assets/buaa.005.jpg)
![](readme.assets/buaa.006.jpg)
![](readme.assets/buaa.007.jpg)
![](readme.assets/buaa.008.jpg)
![](readme.assets/buaa.009.jpg)



