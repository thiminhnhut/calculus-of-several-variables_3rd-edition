# Diffirentiation of Vectors

## Đạo hàm của vectơ theo một biến số thực

Cho hàm số vectơ $X(t) = (x(t), y(t), z(t))$ với $t$ là biến số thực. Đạo hàm của hàm số vectơ theo biến số $t$ được định nghĩa bởi:

$\frac{dX(t)}{dt} = \left( \dfrac{dx}{dt}, \dfrac{dy}{dt}, \dfrac{dz}{dt} \right) = X'(t)$

- Vận tốc $v(t) = ||X'(t)||$ và $v(t)^2 = X'(t) \cdot X'(t)= X'(t)^2$.

- Gia tốc $a(t) = \dfrac{d^2X(t)}{dt^2} = X''(t) = v'(t)$

- Tính chất về đạo hàm:

    - $\dfrac{d(X + Y)}{dt} = \dfrac{dX}{dt} + \dfrac{dY}{dt}$

    - $\dfrac{d(kX)}{dt} = k \dfrac{dX}{dt}$ với $k$ là hằng số.

    - $\dfrac{d(X \cdot Y)}{dt} = \dfrac{dX}{dt} \cdot Y + X \cdot \dfrac{dY}{dt}$

    - $\dfrac{dX^2}{dt} = 2X \cdot \dfrac{dX}{dt}$

## Độ dài của đường cong

- Độ dài $s = \int_a^b v(t) dt = \int_a^b ||X'(t)|| dt$

- Tổng quát với $X(t) = (x_1(t), x_2(t), ..., x_n(t))$ trong không gian $R^n$: $s = \int_a^b \sqrt{\left(\dfrac{dx_1}{dt}\right)^2 + \left(\dfrac{dx_2}{dt}\right)^2 + ... + \left(\dfrac{dx_n}{dt}\right)^2} dt$