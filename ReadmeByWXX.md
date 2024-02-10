# how to start web application

just run the entry file to start web application
- linux/macos: run `webui.sh`. if you want to specify any arguement, modify `webui-user.sh`
- windows: run `webui-user.bat`, and from `webui-user.bat` we can see the actual app entry is `webui.bat`. if you want to specify any arguement, modify `webui-user.bat`


在运行过程中，需要从pypi源安装依赖，以及从github下载一些依赖的模型文件到本地。如果被墙，可以手动替换pypi源安装python pkg，手动从网络上下载github有关的依赖放置在本地恰当的文件夹中（可以`webui.sh`执行时的控制台输出判断文件被下载后的目标路径）


# how to use pretrained-models
- go to https://civitai.com/ and download models
- place model to `stable-diffusion-webui/models/Stable-diffusion`, then you can see the models in the options of input field `Stable Diffusion checkpoint` in the website