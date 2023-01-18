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
- 配布されているROBOTIS OP3のURDFモデルでは関節可動範囲のパラメーター設定がされておらず、すべての関節の可動範囲が-0.9π to 0.9πとなっているので注意が必要。

<b>関節可動範囲一覧</b>
| ID  | Joint name | Motion | Range(Dynamixel potision) | Range(degrees) |
| --- | ---        | ---    | ---                       | ---            |
| 1   | Shoulder R | Pitch  | 0 to 0                    | 0 to 0         |
| 2   | Shoulder L | Pitch  |                     |          |
| 3   | Shoulder R | Roll   |                     |          |
| 4   | Shoulder L | Roll   |                     |          |
| 5   | Elbow R    | Roll   |                     |          |
| 6   | Elbow L    | Roll   |                     |          |
| 7   | Hip R      | Yaw    |                     |          |
| 8   | Hip L      | Yaw    |                     |          |
| 9   | Thigh R    | Roll   |                     |          |
| 10  | Thigh L    | Roll   |                     |          |
| 11  | Thigh R    | Pitch  |                     |          |
| 12  | Thigh L    | Pitch  |                     |          |
| 13  | Knee R     | Pitch  |                     |          |
| 14  | Knee L     | Pitch  |                     |          |
| 15  | Ankle R    | Pitch  |                     |          |
| 16  | Ankle L    | Pitch  |                     |          |
| 17  | Ankle R    | Roll   |                     |          |
| 18  | Ankle L    | Roll   |                     |          |
| 19  |  Neck      | Yaw(Pan)    |                     |          |
| 20  |  Head      | Pitch(Tilt) |                     |          |
