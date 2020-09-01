A theme for [staticBlog](https://github.com/shukriadams/staticBlog)

## Use

Add the following to your package.json

    {
        "dependencies": {
            "staticblog-theme-darkmoon": "https://github.com/shukriadams/staticblog-theme-darkmoon.git#<TAG>"
        }
    }

Add to build script

    const blogEngine = require('staticblog')
    
    await blogEngine({
        ...
        themeFolder: './node_modules/staticblog-theme-darkmoon',
        ...
    })
