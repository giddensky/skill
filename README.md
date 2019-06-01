# skill
#### 1、git提交代码
clone项目的dev分支，然后增加或修改自己的代码，提交时：
> 1. 切换分支为dev，并且pull代码，更新本地代码，避免dev线上的冲突
> 2. 新建以名称和日期为特征的分支，提交代码，push代码
> 3. 代码等待管理员审核，合并分支到dev
> 4. 审核通过后，删除新建的分支
> 5. 切换本地分支为dev，pull代码，继续开发
> #### 这是我在开发中看到一位同事使用的代码提交技法，觉得很好，可以最大限度的保证代码和dev的同步，减少代码冲突

#### 2、idea解决包冲突
使用idea右侧栏`maven project`中的show dependencies查看包依赖关系  
快捷键：<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>shift</kbd>+<kbd>u</kbd>
