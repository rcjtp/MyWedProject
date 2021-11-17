# PNS CHA
 โปรเจคชานมไข่มุก Application จัดทำโดย ธนภูมิ สร้อยมณีโชติ
## Features
- มีสินค้าที่ให้ลูกค้าเลือกได้
- สามารถจ่ายเงินออนไลน์
- มีเดลิเวอลี่บริการจัดส่ง
## Exmple Code
``` 
<body style="        background-color: #FBC78D;">
    <div class="container" align="center" style="margin-top:5%;" >
        
            <div class="form-group col-md-4">
                <img src="~/img/Logo.png" style="width:100%; height:40%"/>
            </div>
            <div class="form-group col-md-4">
                <input type="text"
                       class="form-control"
                       id="Username"
                       aria-describedby="emailHelp"
                       placeholder="Username">
            </div>
            <div class="form-group col-md-4">
                <input type="password"
                       class="form-control"
                       id="Password"
                       placeholder="Password">
            </div>
            

            
            <input type="button" class="btn btn-success" onclick="location.href='@Url.Action("Index", "Home")'" 
                   value="เข้าสู่ระบบ"  style="background-color : #808080; border-color : #808080; width : 30.5%;"/>
            
            
        
    </div>           
</body>
``` 
## Credit
610107030009@dpu.ac.th
## License
