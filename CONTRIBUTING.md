#贡献指南
> 每一次的pull 请求都应具备一个有意义的标题。 使用类似于`更新 readme.md文件`等不明所以的标题的pull请求会被无理由拒绝。请确认提交请求前，您已经仔细阅读过了本指南中的小要求。

## 向列表中添加新条目须知
1. 确保您只修改了`README.md`文件，不允许修改其他的文件或添加到新文件。
2. 将新条目添加到对应的分组中，尽量避免创建新的分组。
3. 确保新添加的条目在对应分组的最底端，不要在分组的中间或者前面添加新条目。
4. 不要添加死链，尽量保证添加的链接都是HTTPS类型。
5. 请确保添加的资源都是英文资源，其他语言的资源 *暂时不要添加*。
6. 若您添加的资源对于设备有要求（例如仅支持RPi3之后的设备），资源描述后面应添加这里给出的 [小标记](media/badges)。

### 添加步骤
1. 点击 README.md。
2. 点击中间偏右上角位于 raw | blame | history右侧的 *小铅笔按钮* 。
3. Github 会跳转到编辑页面，并提示已经在您的帐号自动创建了一个当前项目的fork分支。
4. 将您要进行的修改添加进去。
5. 在编辑页的最下端有两个长长的编辑栏，在里面填写本次修改的概要（如  Added motionEye OS to the OS list，英文不好的话写中文也无大碍），然后点击*Propose file change*按钮。
6. 然后会跳转到 PR(Pull Request) 界面，点击*Create Pull Request* 按钮。
7. 确定操作和修改无误后，勇敢的点击 *Create Pull Request*按钮。

#### Gitmoji
我们推荐在维护条目时使用 [gitmoji](https://gitmoji.carloscuesta.me/)。为了保证gitmoji正常显示，它与提交概要之间需要用一个空格隔开。请尽量只使用下表所示的四个：（如果您在本地编辑器进行编辑工作的话，可能表中有一些gitmoji在编辑器上无法显示，不用担心）

|Name, Use|Emoji|Example
|---|---|---
|`:heavy-plus-sign`, 添加条目|➕|`git commit -m ":heavy-plus-sign: Added motionEye OS to the OS list"`
|`:heavy-minus-sign`, 删除条目|➖| `git commit -m ":heavy-minus-sign Removed motionEye OS from the OS list"`
|`:truck`, 移动条目到其他分组|🚚| `git commit -m ":truck: Moved motionEye OS from Projects to OS's"`
|`:pencil2`, 修改错字|✏️| `git commit -m ":pencil2: Fixed typo for Raspbian Jessie Lite"`
