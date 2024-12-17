JSON格式示例：
Accelaration,加速度
IR，八个红外测距


{
    "Accelaration": { 
        "acc_x":accelerationData[0],  // int
        "acc_y":accelerationData[1],
        "acc_z":accelerationData[2]
    },

    "IR":{
        "IR0":irData[0],              // int
        "IR1":irData[1],
        "IR2":irData[2],
        "IR3":irData[3],
        "IR4":irData[4],
        "IR5":irData[5],
        "IR6":irData[6],
        "IR7":irData[7]
    }

    //其他JSON包待补充
}

UWB数据类型：
//待补充