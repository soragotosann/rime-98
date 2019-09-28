- 这是应用皮肤后的输入效果：
![image](https://raw.githubusercontent.com/thep0y/rime-98/master/images/default.png)
- 这是反查的效果：
![image](https://raw.githubusercontent.com/thep0y/rime-98/master/images/reverse.png)

皮肤是在squirrel.yaml里，名叫“mojave_dark”，配置可参考本仓库/build/squirrel.yaml。


## 鼠须管(Mac)使用简要步骤：
- 将wubi98.dict.yaml(98五笔词库)、wubi98.schema.yaml(配置文件)、pinyin_simp.dict.yaml(反查必须的拼音词库)、pinyin_simp.schema.yaml(拼音词库配置文件)、default.custom.yaml(用户配置文件)下载下来后，放在RIME的配置文件夹内。
- 配置文件夹为`~/Library/Rime`，快速进入方式是通过RIME的“用户设定...”进入。
- 修改squirrel.yaml，选择自己喜欢的皮肤。
- 选择“重新部署”，即可生效。

## 小狼毫(Windows)使用简要步骤：
- 右击任务栏的小狼毫输入法图标，打开“用户文件夹”。
- 将wubi98.dict.yaml(98五笔词库)、wubi98.schema.yaml(配置文件)、pinyin_simp.dict.yaml(反查必须的拼音词库)、pinyin_simp.schema.yaml(拼音词库配置文件)、default.custom.yaml(用户配置文件)下载下来放进此文件夹。
- 右击任务栏的小狼毫输入法图标，点击“重新部署”，应该就能用了。如果不能用的话，在“输入法设定”里找找是不是有“五笔98”，如果没有，检查你之前的操作。


Linux的就不再另附了，太小众，而且小小输入法我觉得已经很不错了。



## 补充一点：
我用的wubi98.dict.yaml内的码表内的词库只有两个元素，其实默认是三个元素，最后应该有个词频，但是我觉得用五笔打字并不需要词频调整，所以就没有将词频部分写上。
