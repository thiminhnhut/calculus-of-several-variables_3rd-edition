# Homework 5

## Câu a

- Cho $\Phi (X) = - \dfrac{k}{r}$ với $k > 0, X = (x, y, z), r = \sqrt{x^2 + y^2 + z^2}$.

- Tính $\nabla \Phi (X)$?

**Lời giải:**

- Ta có: $$\nabla \Phi (X) = \left(-\dfrac{k}{r}\right)' \dfrac{X}{r} = \dfrac{k}{r^2} \cdot \dfrac{X}{r} = \dfrac{k}{r^3}X$$

- Giải thích $F=-\nabla \Phi = -\dfrac{k}{r^3}X$:
  - $X$ là vector từ gốc tọa độ đến vệ tinh.
  - Dấu $(-)$ cho biết lực hướng ngược lại so với $X$, tức là bị hút về phía gốc tọa độ.
  - Độ lớn của $F$ là: $||F|| = \dfrac{k}{r^3} ||X|| = \dfrac{k}{r^3} r = \dfrac{k}{r^2}$, đúng với định luật hấp dẫn.

## Câu b

- Cho:
  - Quỹ đạo: $C(t)$.
  - Lực bảo toàn: $F(C(t)) = -\nabla \Phi (C(t))$.
  - Định luật 2 Newton: $m C''(t) = F(C(t))$.
  - Tổng năng lượng: $E(t) = \dfrac{1}{2} m ||C'(t)||^2 + \Phi (C(t))$.

- Chứng minh $\dfrac{dE}{dt} = 0$.

**Lời giải:**

- Ta có:
  $$
  \begin{aligned}
  \dfrac{dE}{dt} & = \dfrac{d}{dt} \left( \dfrac{1}{2} m ||C'(t)||^2 + \Phi (C(t)) \right) \\
  & = \dfrac{1}{2} m \cdot 2 C'(t) \cdot C''(t) + \nabla \Phi (C(t)) \cdot C'(t) \\
  & = m C'(t) \cdot C''(t) + \nabla \Phi (C(t)) \cdot C'(t) \\
  & = C'(t) \cdot (m C''(t) + \nabla \Phi (C(t))) \\
  & = C'(t) \cdot (F(C(t)) + \nabla \Phi (C(t))) \textrm{ thay } mC''(t) = F(C(t))\\
  & = C'(t) \cdot ( -\nabla \Phi (C(t)) + \nabla \Phi (C(t))) \textrm{ thay } F(C(t)) = -\nabla \Phi (C(t))\\
  & = 0.
  \end{aligned}
  $$

## Câu c

- Tốc độ thay đổi theo hướng của chuyển động: $D_v \Phi (P) = \nabla \Phi (P) \cdot v$

- Trong quỹ đạo tròn thì $v \perp P$ mà $\nabla \Phi (P)$ cùng hướng với $P$, nên $D_v \Phi (P) = \nabla \Phi (P) \cdot v = 0$.

## Câu d

- Cho: $m=1000kg$, $\Phi = -\dfrac{10^6}{r} (J)$, $P_0=(300,400,0) km$ và $v_0=2km/s=2000m/s$.

- Tính $E(0)$ và vận tốc quỹ đạo tròn tại $P_1=(100,0,0) km/s$.

**Lời giải:**

- Tính $r_0 = ||P_0|| = \sqrt{300^2 + 400^2 + 0^2} = 500 (km)$.

- Năng lượng tại $t=0$:
  $$
  \begin{aligned}
  E(0) & = \dfrac{1}{2} m ||v_0||^2 + \Phi (P_0) \\
  & = \frac{1}{2} m v_0^2 + \left(-\dfrac{10^6}{r_0}\right) \\
  & = \dfrac{1}{2} \cdot 1000 \cdot 2000^2 + \left(-\dfrac{10^6}{500}\right) \\
  & = 2 \times 10^9 - 2000 = 1999998000 (J).
  \end{aligned}
  $$
- Tại $P_1$, ta có: $r_1 = ||P_1|| = 100 (km)$ và $\Phi (P_1) = -\dfrac{10^6}{100} = -10^4 (J)$.

- Ta có: E(1) = E(0), nên:
  $$
  \begin{aligned}
  E(1) & = \dfrac{1}{2} m ||v_1||^2 + \Phi (P_1) \\
  & \dfrac{1}{2} \cdot 1000 \cdot ||v_1||^2 + \left(-10^4\right) = 1999998000 \\
  & \Rightarrow ||v_1||^2 = \dfrac{1999998000 + 10^4}{500} = 4000016 \\
  & \Rightarrow ||v_1|| = \sqrt{4000016} \approx 2000 (m/s).
  \end{aligned}
  $$
