
## `cc.primitive` 模块






一个创建 3D 物体顶点数据的基础模块，你可以通过 "cc.primitive" 来访问这个模块。





### 索引



##### 方法

  - [`box`](#box) 创建长方体顶点数据
  - [`cone`](#cone) 创建圆锥体顶点数据
  - [`cylinder`](#cylinder) 创建圆柱体顶点数据
  - [`plane`](#plane) 创建平台顶点数据
  - [`quad`](#quad) 创建面片顶点数据
  - [`sphere`](#sphere) 创建球体顶点数据
  - [`torus`](#torus) 创建圆环顶点数据
  - [`capsule`](#capsule) 创建胶囊体顶点数据
  - [`polyhedron`](#polyhedron) 创建多面体顶点数据



### Details




<!-- Method Block -->
#### 方法


##### box

创建长方体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:24](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L24) |

###### 参数列表
- `width` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `length` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `widthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `lengthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### cone

创建圆锥体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:39](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L39) |

###### 参数列表
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### cylinder

创建圆柱体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:54](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L54) |

###### 参数列表
- `radiusTop` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `radiusBottom` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### plane

创建平台顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:70](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L70) |

###### 参数列表
- `width` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `length` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `widthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `lengthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### quad

创建面片顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:83](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L83) |



##### sphere

创建球体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:91](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L91) |

###### 参数列表
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `segments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### torus

创建圆环顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:102](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L102) |

###### 参数列表
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `tube` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `tubularSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### capsule

创建胶囊体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:116](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L116) |

###### 参数列表
- `radiusTop` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `radiusBottom` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `sides` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### polyhedron

创建多面体顶点数据

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| 定义于 | [cocos2d/core/3d/primitive/index.ts:132](https://github.com/cocos-creator/engine/blob/246760b55cfc698ac5f3450a1794d9d0554a0600/cocos2d/core/3d/primitive/index.ts#L132) |

###### 参数列表
- `type` <a href="../enums/primitive.PolyhedronType.html" class="crosslink">primitive.PolyhedronType</a> 
- `Size` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `sizeX` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `sizeY` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `sizeZ` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


