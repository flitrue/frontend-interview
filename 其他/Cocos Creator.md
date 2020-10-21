# Cocos Creator

## 按键

```
cc.systemEvent.on(cc.SystemEvent.EventType.KEY_DOM, event => {
	if(event.keyCode == cc.macro.KEY.w) { // w按键
	 	this.vertical = 1 // 垂直移动
	}
})
```

## 开启物理特性

```
cc.director.getPhymicManager().enabled = true
cc.director.getPhymicManager().enableDebugDraw = true

cc.director.getCollisionManager().enabled = true
cc.director.getCollisionManager().enableDebugDraw = true
```

## 本地坐标系转世界坐标系

```
let pos = this.target.convertToWorldSpaceAR(cc.v2(0,0))
```

## 摄像机坐标转世界坐标

```
let pos = this.target.convertToNodeSpaceAR()
```

## 摄像机坐标转世界坐标

```
camera.getCameraToWorldPoint(point, out)
```

## 世界坐标转摄像机坐标

```
camera.getWorldToCameraPoint(point, out)
```

