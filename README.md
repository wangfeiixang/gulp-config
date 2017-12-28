 ## gulp配置文件

> 1. 启用`gulp-connect`开启热更新和服务器
> 2. 使用`gulp-autoprefixer`自动给css加前缀
> 3. 使用`gulp-babel`将ES6转译ES5
> 4. 使用`gulp-autoprefixer`自动给css加前缀
> 5. 使用`gulp-uglify`压缩js文件
> 6. 使用`gulp-imagemin`对图片进行处理 </br>
>> (1) 使用`imagemin-pngquant`压缩png图片
> 7. 使用`gulp-rename`对文件进行重新命名
> 8. 使用`gulp-htmlmin`对html文件进行压缩
> 9. 使用`gulp-webserver`开启热更新和服务器

### `gulp-connect`和`gulp-webserver`都是热更新,监控src目录文件夹，可实现同步涮新，`gulp-connect`需要配合chrome插件liveReload;`gulp-webserver`需要引入根目录文件夹`./`


