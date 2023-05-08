# Vue-Note

#### el挂载点：

- `el: "#app"` -> `<div id="app"></div>`
- `el: ".app"` -> `<div class="app"></div>`
- `el: "div"` -> `<div></div>`

#### data:

- vue所需要的数据存在data元素内

  ```js
  data: {
  	message: "Hello Data!",
  	info: {
  		name: "pjm",
  		email: "panjm2001@126.com",
  	},
  },
  ```

- 例如使用 `{{ info.name }}` 取值

#### v-text

- 会覆盖标签里面的内容，使用插值表达式 {{  }} 可替换部分内容
- 支持表达式

#### v-html

- 设置标签的innerHTML
- 替换标签里面，渲染html

#### v-on

- `<input type="button" value="v-on指令" @click="hello" />`

- v-on:可以简写成@

- 方法定义在methods

  ```javascript
  methods: {
  	hello: function () {
  		alert("Hello!");
  	},
  },
  ```

#### v-show

![image-20230507221307415](C:\Users\panjiaming\AppData\Roaming\Typora\typora-user-images\image-20230507221307415.png)

#### v-if

![image-20230508141113968](C:\Users\panjiaming\AppData\Roaming\Typora\typora-user-images\image-20230508141113968.png)

#### v-bind

![image-20230508142811404](C:\Users\panjiaming\AppData\Roaming\Typora\typora-user-images\image-20230508142811404.png)

#### v-model

![image-20230508152131289](C:\Users\panjiaming\AppData\Roaming\Typora\typora-user-images\image-20230508152131289.png)