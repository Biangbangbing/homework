# homework.hyml
<!DOCTYPE>
<html>
<head>
    <meta charset="utf-8">
    <link href="styles/style.css/qianduanzuoye.css" rel="stylesheet" type="text/css">
    <title>表格+表单</title>
</head>
<body>
    <form mrthod="post" action="demo.php">
    <table border="1px" width="100%" align="center" cellpadding="1" cellspacing="0px">
        <tr>
            <th colspan="3" align="left"><strong>1.姓名和联系方式</strong></th>
            
        <tr>
            <td align="right" width="20%">真实姓名:</td>
            <td width="30%">
                <input type="text" name="a" style="width:30%;height:15%"/>*
            </td>
            <td width="50%">
                <p>
                        <input id="aaa" name="sex" type="radio">男
                        <input id="bbb" name="sex" type="radio">女
                </p>
            </td>
        </tr>
        <tr>
            <td align="right" width="20%">电子邮箱:</td>
            <td width="30%"><input type="text" name="b" style="width:30%;height:15%"/>*</td>
            <td><strong width="50%">非常重要!</strong>
                <p>这是本工作室与您联系的首选方式哦，请填写真实.
                </p>
            </td>
        </tr>
        <tr>
            <td align="right" width="20%">电话:</td>
            <td width="30%"><input type="text" name="c" style="width:30%;height:15%"/>*</td>
            <td width="50%">电话为必须填写项</td>
        </tr>
        <tr>
            <td align="right" width="20%">所实习部门:</td>
            <td width="50%">
                <select name="bm"
                <option value="研发">研发</option>  
                <option value="研发"selected>研发</option>
                </select>
            </td>
        </tr>
        <tr>
            <td align="right" width="20%">实习岗位:</td>
            <td width="30%"><input type="text" name="d" style="width:30%;height:15%"/>*</td>
            <td width="50%">研发部岗位:前端/后端/运维</td>
        </tr>
        <tr>
            <td align="right" width="20%">手机号码:</td>
            <td width="30%"><input type="text" name="e" style="width:30%;height:15%"/></td>
        </tr>
        <tr>
            <td align="right" width="20%">邮箱:</td>
            <td width="30%"><input type="text" name="f" style="width:30%;height:15%"/></td>
        </tr>
        <tr>
            <td align="right" width="20%">性别取向:</td>
            <td width="30%"><input type="text" name="g" style="width:30%;height:15%"/></td>
        </tr>
        <tr>
            <td colspan="3" align="center"><input type="submit" value="提交注册信息">
                                           <input type="reset" value="重设信息"></td>
        </tr>
    </form>
</body>
</html>
