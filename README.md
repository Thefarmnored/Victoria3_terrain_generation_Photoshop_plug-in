# Victoria3 terrain 生成 Photoshop plug-in
为了在 Photoshop 中调整好图层的包含颜色后能够直接生成地形文件，而不是依次导出再依次操作最后再合并代码……
为了能够一步到位，所以需要能够和 Photoshop 关联起来，所以这是一个 Photoshop plug-in

# 下面是 Adobe Photoshop plug-in SDK 描述
# Starter Photoshop Plugin (Vanilla)

This starter plugin is a good place to get started when developing for Photoshop. It does not rely on any frameworks or build steps -- hence the name "Vanilla".

## Load into Photoshop

Make sure Photoshop is up and running first. First, add the plugin to the "Developer Workspace" in the UXP Developer Tools (UDT) application.
  * If you selected "Create Plugin..." earlier, it will have already be there with the plugin ID and name you specified. 
  * Otherwise, click "Add Plugin" and select the `manifest.json` file in the corresponding plugin folder.

Click the ••• button next to the corresponding workspace entry, and click "Load". Switch over to Photoshop, and the plugin's panel will be running. 

## Continue creating

* Read more about creating and debugging plugins using the UDT application [here](https://developer.adobe.com/photoshop/uxp/2022/guides/devtool/udt-walkthrough/). 
* We build on this starter template and show you how to [edit a document](https://developer.adobe.com/photoshop/uxp/2022/guides/getting-started/editing-the-document/) and [write a file](https://developer.adobe.com/photoshop/uxp/2022/guides/getting-started/writing-a-file/) using UXP. 
