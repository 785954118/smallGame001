游戏说明：
1.按照策划案文档做，
2.游戏做两关就行了，其他直接弹其实框，开发中，敬请期待

3.弹框跟切换界面经量加点动作（又小变大）
    public static showAni(node) {
        node.scale = 0
        node.active = true
        var action = cc.scaleTo(0.3, 1, 1);
        action.easing(cc.easeExponentialInOut());
        node.runAction(action)
    }
    public static hideAni(node) {
        var action = cc.scaleTo(0.3, 0, 0);
        action.easing(cc.easeExponentialInOut());
        node.runAction(action)
    }
4.登录界面进入大厅加个进度条加载，假的加载，给个两秒左右
