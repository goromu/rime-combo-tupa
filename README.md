# rime-combo-tupa

切韻拼音·宮保測試二

並擊輸入切韻拼音，需配合[rime-tupa](https://github.com/ayaka14732/rime-tupa)

此方案無法辨別聲調，最多六鍵同時並擊。

章組同端組輸入。

## 鍵位表

|      |      |      |      |      |      |      |      |      |      | 
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| j   **Q**| n   **W**| d   **E**| t   **R**| th  **T**|     **Y**| i   **U**| u   **I**|-ng  **O**|-k   **P**|
| q   **A**| ng  **S**| g   **D**| k   **F**| kh  **G**| e   **H**| o   **J**| ou  **K**|-n   **L**|-t   **:**|
| z   **Z**| s   **X**| dz  **C**| ts  **V**| tsh **B**| ae  **N**| a   **M**|-w   **,**|-j   **.**|     **/**|

### 組合聲母

    Q + W <nr>, W + E <dr>, E + R <tr>, R + T <trh>,
    A + S <m>, S + D <b>, D + F <p>, F + G <ph>,
    Z + X <sr>, X + C <dzr>, C + V <tsr>, V + B <tsrh>
    W + A <h>, E + A <zj>, W + F <sj>, E + F <l>,
    Z + V <zr>,

### 組合韻母

    U + I <yi>,
    U + H <ie>, I + H <ye>, I + J <yo>, H + J <ee>, J + K <oeu>,
    J + N <iae>, K + N <yae>, K + M <ya>,

<kbd>Space</kbd>是開合轉換符，把y轉換爲u，u轉換爲y，o轉換爲eo。特別地，將ou轉換爲weo。

### 組合韻尾

    O + ; <p>, L + ; <m>,
