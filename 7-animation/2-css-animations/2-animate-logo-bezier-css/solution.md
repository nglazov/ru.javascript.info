Для такой анимации необходимо подобрать правильную кривую Безье. Для того чтобы самолет "выпрыгнул", она должна иметь `y>1` на одном из участков.

Например, мы можем указать `y>1` для обеих контрольных точек: `cubic-bezier(0.25, 1.5, 0.75, 1.5)`.

График кривой Безье:

![](bezier-up.png)
