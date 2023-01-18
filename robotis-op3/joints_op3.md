# ROBOTIS OP3 Joint

## ID MAP
<img src="https://emanual.robotis.com/assets/images/platform/op3/op3_030_rev2.png">

## Home Position
<img src="https://emanual.robotis.com/assets/images/platform/op3/op3_assemble_data.png">

<b>Home Positionの定義</b>
- ROBOTIS OP3モデルとしての関節角度が 0[deg] ないし 0[rad] である。
- <a href ="https://emanual.robotis.com/docs/en/dxl/x/xm430-w350/">Dynamixel XM430-W350-R</a>のPositionの値が 2048 ないし 0x800 である。 

## Motion Range

<b>Note:</b>
- 配布されているROBOTIS OP3のURDFモデルでは関節可動範囲のパラメーター設定がされておらず、すべての関節の可動範囲が -0.9π to 0.9π , -2.83rad to +2.83rad となっているので注意が必要。

<b>関節可動範囲一覧</b>
| ID  | Joint name | Motion | Range(Dynamixel potision) | Range(degrees) ※モーター出力軸CCWが-(マイナス)、CWが+(プラス) |
| --- | ---        | ---    | ---                       | ---            |
| 1   | Shoulder R | Pitch  |                     | -179(腕を前に振る) to +179(腕を後ろに振る) |
| 2   | Shoulder L | Pitch  |                     | -179(腕を後ろに振る) to +179(腕を前にふる) |
| 3   | Shoulder R | Roll   |                     | -100(腕を上げる) to +120(腕を下げる)  |
| 4   | Shoulder L | Roll   |                     | -120(腕を下げる) to +100(腕を上げる)  |
| 5   | Elbow R    | Roll   |                     | -135(肘を内側に曲げる) to +135(肘を外側に曲げる)  |
| 6   | Elbow L    | Roll   |                     | -135(肘を外側に曲げる) to +135(肘を内側に曲げる)  |
| 7   | Hip R      | Yaw    |                     | -90(脚を外側に回す) to +45(足を内側に回す)  |
| 8   | Hip L      | Yaw    |                     | -45(脚を内側に回す) to +90(脚を外側に回す)  |
| 9   | Thigh R    | Roll   |                     | -90(脚を外側に開く) to +45(脚を内側に閉じる) |
| 10  | Thigh L    | Roll   |                     | -45(脚を内側に閉じる) to +90(脚を外側に開く) |
| 11  | Thigh R    | Pitch  |                     | -135(脚を前に振る) to +28(脚を後ろに振る)  |
| 12  | Thigh L    | Pitch  |                     | -28(脚を後ろに振る) to -135(脚を前に振る)  |
| 13  | Knee R     | Pitch  |                     | -135(膝を逆方向に曲げる) to +148(膝を順方向に曲げる)  |
| 14  | Knee L     | Pitch  |                     | -148(膝を順方向に曲げる) to +135(膝を逆方向に曲げる)  |
| 15  | Ankle R    | Pitch  |                     | -28(足首を後ろに振る) to +110(足首を前に振る) |
| 16  | Ankle L    | Pitch  |                     | -110(足首を前に振る) to +28(足首を後ろに振る)  |
| 17  | Ankle R    | Roll   |                     | -80(足首を内側に閉じる) to +90(足首を外側に開く) |
| 18  | Ankle L    | Roll   |                     | -90(足首を外側に開く) to +80(足首を内側に閉じる) |
| 19  |  Neck      | Yaw(Pan)    |                     | -135(首を左に回す) to +135(首を右に回す) |
| 20  |  Head      | Pitch(Tilt) |                     | -90(頭が仰ぐ) to +135(頭がうつ向く)  |

## 関連情報

<b>Webots Documentation: ROBOTIS's Robotis OP3</b> <a href ="https://cyberbotics.com/doc/guide/robotis-op3">https://cyberbotics.com/doc/guide/robotis-op3</a>
