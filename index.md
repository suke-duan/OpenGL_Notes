## 使用VBO绘图
<details>
<summary>VBO</summary>
作用: 生成一个VBO
参数:
</details>
<details>
<summary>glInterleavedArrays</summary>
--分离数组: VBO是个组合的数组，通过该函数，将数组分离出顶点、颜色、纹理等数据
<details>
<summary>----format</summary>
格式:数组里面数据的格式，有如下选项
GL_V2F: 二维顶点，数据类型为浮点型<br>
GL_V3F: 三维顶点，数据类型为浮点型<br>
GL_C4UB_V2F: 颜色+二维顶点，数据类型为浮点型<br>
GL_C4UB_V3F: 颜色+三维顶点，数据类型为浮点型<br>
GL_C3F_V3F: 颜色+三维顶点，数据类型为浮点型<br>
GL_N3F_V3F: 法矢+三维顶点，数据类型为浮点型<br>
GL_C4F_N3F_V3F: 颜色+法矢+三维顶点，数据类型为浮点型<br>
GL_T2F_V3F: 纹理+三维顶点，数据类型为浮点型<br>
GL_T4F_V4F: 纹理+三维顶点，数据类型为浮点型<br>
GL_T2F_C4UB_V3F: 纹理+颜色+三维顶点，数据类型为浮点型<br>
GL_T2F_C3F_V3F: 纹理+颜色+三维顶点，数据类型为浮点型<br>
GL_T2F_N3F_V3F: 纹理+法矢+三维顶点，数据类型为浮点型<br>
GL_T2F_C4F_N3F_V3F: 纹理+颜色+法矢+三维顶点，数据类型为浮点型<br>
GL_T4F_C4F_N3F_V4F: 纹理+颜色+法矢+三维顶点，数据类型为浮点型<br>
</details>
<details>
<summary>----stride</summary>
步长: 前一个数据与后一个数据的距离，如果是0，表示紧挨着<br>
含义
</details>
<details>
<summary>----pointer</summary>
指针<br>
含义
</details>
</details>



<img src="https://latex.codecogs.com/gif.latex?\frac{x}{y}" title="\frac{x}{y}" />


