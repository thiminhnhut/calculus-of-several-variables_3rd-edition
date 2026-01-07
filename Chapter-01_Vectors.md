# Vectors

## Biểu diễn điểm trong không gian

- Điểm được biểu diễn trên trục số bằng một số thực $x$.

- Điểm được biểu diễn trên mặt phẳng tọa độ Oxy bằng cặp số $(x, y)$.

- Điểm được biểu diễn trong không gian tọa độ Oxyz bằng bộ ba số $(x, y, z)$.

- Điểm được biểu diễn trong không gian $R^n$ bằng bộ n số $(x_1, x_2, ..., x_n)$.

## Một số phép toán trên điểm

Cho 2 điểm $A(x_1, y_1, z_1)$ và $B(x_2, y_2, z_2)$:

1. Phép cộng: $A + B = (x_1 + x_2, y_1 + y_2, z_1 + z_2)$

2. Phép trừ: $A - B = (x_1 - x_2, y_1 - y_2, z_1 - z_2)$

3. Phép nhân với một số thực k: $kA = (kx_1, ky_1, kz_1)$

4. Dùng quy tắc hình bình hành để biểu diễn phép cộng (hoặc trừ) hai điểm trên mặt phẳng.

## Một số tính chất của phép toán trên điểm

1. Tính giao hoán của phép cộng: $A + B = B + A$

2. Tính kết hợp của phép cộng: $(A + B) + C = A + (B + C)$

3. Tồn tại phần tử không: $A + O = A$ với $O = (0, 0, 0)$ là phần tử không.

4. Nếu $A(x_1, x_2, x_3)$ thì tồn tại phần tử đối: $A + (-A) = O$ với $-A = (-x_1, -x_2, -x_3)$.

## Vectơ trong không gian

- Cho 2 điểm $A(x_1, y_1, z_1)$ và $B(x_2, y_2, z_2)$: $\overrightarrow{AB} = B - A = (x_2 - x_1, y_2 - y_1, z_2 - z_1)$.

- Nếu $\overrightarrow{AB} // \overrightarrow{CD}$ thì tồn tại số thực k sao cho $\overrightarrow{AB} = k\overrightarrow{CD}$.

  - Nếu k > 0 thì hai vectơ cùng hướng

  - Nếu k < 0 thì hai vectơ ngược hướng.

## Tích vô hướng của hai vectơ (Scalar product)

1. Cho hai vectơ $\overrightarrow{A} = (a_1, a_2, a_3)$ và $\overrightarrow{B} = (b_1, b_2, b_3)$. Tích vô hướng của hai vectơ được định nghĩa bởi công thức: $\overrightarrow{A} \cdot \overrightarrow{B} = a_1b_1 + a_2b_2 + a_3b_3$

2. Mở rộng: Cho hai vectơ trong không gian R^n: $\overrightarrow{A} = (a_1, a_2, ..., a_n)$ và $\overrightarrow{B} = (b_1, b_2, ..., b_n)$. Tích vô hướng được định nghĩa bởi công thức: $\overrightarrow{A} \cdot \overrightarrow{B} = a_1b_1 + a_2b_2 + ... + a_nb_n$

3. Tính chất của tích vô hướng:

   - Tính giao hoán: $\overrightarrow{A} \cdot \overrightarrow{B} = \overrightarrow{B} \cdot \overrightarrow{A}$

   - Tính phân phối: $\overrightarrow{A} \cdot (\overrightarrow{B} + \overrightarrow{C}) = \overrightarrow{A} \cdot \overrightarrow{B} + \overrightarrow{A} \cdot \overrightarrow{C}$

   - Tương quan với phép nhân vô hướng: $k(\overrightarrow{A} \cdot \overrightarrow{B}) = (k\overrightarrow{A}) \cdot \overrightarrow{B} = \overrightarrow{A} \cdot (k\overrightarrow{B})$

   - Nếu $\overrightarrow{A} = 0$ thì $\overrightarrow{A} \cdot \overrightarrow{A} = 0$, ngược lại $\overrightarrow{A} \cdot \overrightarrow{A} > 0$.

- Nếu $\overrightarrow{A} \cdot \overrightarrow{B} = 0$ thì hai vectơ vuông góc với nhau. (perpendicular)

4. Chứng minh $(\overrightarrow{A} + \overrightarrow{B})^2 = \overrightarrow{A}^2 + 2\overrightarrow{A} \cdot \overrightarrow{B} + \overrightarrow{B}^2$.

   - $(\overrightarrow{A} + \overrightarrow{B})^2 = (\overrightarrow{A} + \overrightarrow{B}) \cdot (\overrightarrow{A} + \overrightarrow{B}) = \overrightarrow{A} \cdot (\overrightarrow{A} + \overrightarrow{B}) + \overrightarrow{B} \cdot (\overrightarrow{A} + \overrightarrow{B}) = \overrightarrow{A} \cdot \overrightarrow{A} + \overrightarrow{A} \cdot \overrightarrow{B} + \overrightarrow{B} \cdot \overrightarrow{A} + \overrightarrow{B} \cdot \overrightarrow{B} = \overrightarrow{A}^2 + 2\overrightarrow{A} \cdot \overrightarrow{B} + \overrightarrow{B}^2$.
