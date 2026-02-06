# The chain rule and the gradient

## The chain rule

## Tangent plane

## Directional derivative

## Function depending only on the distance from the origin

| Không gian | Khoảng cách từ một điểm đến gốc tọa độ                                                                 |
| ---------- | ------------------------------------------------------------------------------------------------------ |
| $2-space $ | $r^2 = x^2 + y^2 $                                                                                     |
|            | $\dfrac{dr}{dx} =\dfrac{x}{r}; \quad \dfrac{dr}{dy} =\dfrac{y}{r}$                                     |
|            | $\nabla r = \left(\dfrac{x}{r}, \dfrac{y}{r}\right) = \dfrac{X}{r}$                                    |
| $3-space$  | $r^2 = x^2 + y^2 + z^2$                                                                                |
|            | $\dfrac{dr}{dx} =\dfrac{x}{r}; \quad \dfrac{dr}{dy} =\dfrac{y}{r}; \quad \dfrac{dr}{dz} =\dfrac{z}{r}$ |
|            | $\nabla r = \left(\dfrac{x}{r}, \dfrac{y}{r}, \dfrac{z}{r}\right) = \dfrac{X}{r}$                      |
| $n-space$  | $r^2 = x_1^2 + x_2^2 + ... + x_n^2$                                                                    |
|            | $\dfrac{dr}{dx_i} =\dfrac{x_i}{r}, \quad i = 1, 2, ..., n$                                             |
|            | $\nabla r = \left(\dfrac{x_1}{r}, \dfrac{x_2}{r}, ..., \dfrac{x_n}{r}\right) = \dfrac{X}{r}$           |

- Cho hàm số $f(X) = g(r)$ với $r = ||X|| = \sqrt{x_1^2 + x_2^2 + ... + x_n^2}$. Khi đó:

  - $\dfrac{\partial f}{\partial x_i} = g'(r) \dfrac{x_i}{r}, \quad i = 1, 2, ..., n$.

  - $\nabla f(X) = g'(r) \dfrac{X}{r}$.

- Các tính chất của gradient của hàm số chỉ phụ thuộc vào $r$:

  - Luôn hướng theo theo bán kính

  - Luôn vuông góc với các mặt đẳng mức

  - Độ lớn của gradient chỉ phụ thuộc vào $r$