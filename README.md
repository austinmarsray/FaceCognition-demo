## python及第三方库选择

<table class="dataintable">
	<tbody>
		<tr>
            <th style="width:20%">配置项</th>
            <th style="width:20%">版本</th>
            <th style="width:60%">备注</th>
        </tr>
        <tr>
            <td>python</td>
            <td>3.6.10</td>
            <td></td>
        </tr>
        <tr>
            <td>dlib</td>
            <td>19.7.0</td>
            <td>dlib应先于face_cognition安装，因为face_cognition对于dlib有依赖要求，且要求dlib版本高于19.7.0</td>
        </tr>
        <tr>
            <td>face-cognition</td>
            <td>1.3.0</td>
            <td></td>
        </tr>
        <tr>
            <td>opencv-python</td>
            <td>3.4.10.35</td>
            <td></td>
        </tr>
    </tbody>
</table>



## 注意事项

- example文件夹下存放需要训练的图片，图片以人物姓名命名作为标签；
- 第三方库版本选择尽量按照给定的版本，使用最新版本会出现安装失败的情况，其余版本没有测试。