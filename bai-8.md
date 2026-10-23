[⬅️ Quay lại Trang chủ Mục lục](README.md)

# 📘 BÀI 8: QUAN HỆ CHIA HẾT VÀ TÍNH CHẤT
*Bộ sách: Kết nối tri thức với cuộc sống – Toán 6 (Tập 1)*

> [!NOTE]
> **🎯 MỤC TIÊU BÀI HỌC**
> Sau khi hoàn thành bài học này, các em sẽ:
> - Nhận biết được quan hệ chia hết, khái niệm **ước** và **bội** trong tập hợp các số tự nhiên.
> - Biết cách tìm tập hợp các ước và các bội của một số tự nhiên cho trước.
> - Hiểu và vận dụng được **tính chất chia hết của một tổng** (hoặc một hiệu, một tích) để xét tính chia hết mà không cần tính giá trị biểu thức.

---

## 1. Quan hệ chia hết. Khái niệm Ước và Bội

### 1.1. Khi nào $a$ chia hết cho $b$?

> [!IMPORTANT]
> **📌 ĐỊNH NGHĨA QUAN HỆ CHIA HẾT**
> Cho hai số tự nhiên $a$ và $b$ ($b \neq 0$):
> - Nếu có số tự nhiên $k$ sao cho $a = b \cdot k$ thì ta nói **$a$ chia hết cho $b$** và ký hiệu là **$a \ \vdots \ b$**.
> - Nếu $a$ không chia hết cho $b$, ta ký hiệu là **$a \not\vdots \ b$** (hoặc **$a \ \nmid \ b$**).
>
> **📌 KHÁI NIỆM ƯỚC VÀ BỘI**
> Nếu $a$ chia hết cho $b$ ($a \ \vdots \ b$), ta nói:
> - $a$ là **bội** của $b$.
> - $b$ là **ước** của $a$.
> - Ký hiệu tập hợp các ước của $a$ là $\text{Ư}(a)$ và tập hợp các bội của $b$ là $\text{B}(b)$.

**💡 Ví dụ minh họa:**
- Ta có $15 : 3 = 5$ (không dư) nên $15 \ \vdots \ 3$. Khi đó: **15 là bội của 3**, và **3 là ước của 15**.
- Ta có $15 : 4 = 3$ (dư 3) nên $15 \ \nmid \ 4$. Khi đó: 15 không phải là bội của 4, và 4 không phải là ước của 15.

---

### 1.2. Bảng phân biệt nhanh hai khái niệm: Ước và Bội

Để không bao giờ bị nhầm lẫn giữa **Ước** và **Bội**, các em hãy đối chiếu qua bảng so sánh dưới đây:

| Tiêu chí so sánh | Ước của số tự nhiên $a$ – $\text{Ư}(a)$ | Bội của số tự nhiên $b$ – $\text{B}(b)$ |
| :--- | :--- | :--- |
| **Bản chất (Khi $a \ \vdots \ b$)** | Số đứng **sau** dấu chia hết ($b$ là số chia). | Số đứng **trước** dấu chia hết ($a$ là số bị chia). |
| **Mẹo ghi nhớ** | "Ước là **chia được**" ($a$ chia hết cho những số nào?). | "Bội là **nhân lên**" (gấp $b$ lên nhiều lần). |
| **Cách tìm chuẩn xác** | Lần lượt chia $a$ cho các số tự nhiên từ $1$ đến $a$. Nếu $a \ \vdots \ m$ thì $m \in \text{Ư}(a)$. | Lần lượt nhân $b$ với $0; 1; 2; 3; \dots$ Kết quả nhận được đều thuộc $\text{B}(b)$. |
| **Số lượng phần tử** | **Hữu hạn** (đếm được hết, phần tử lớn nhất chính là $a$). | **Vô hạn** (không có phần tử lớn nhất, phải dùng dấu `...` ở cuối tập hợp). |
| **Ví dụ với số $6$** | $\text{Ư}(6) = \{1; 2; 3; 6\}$ *(Vì $6 \ \vdots \ 1$, $6 \ \vdots \ 2$, $6 \ \vdots \ 3$, $6 \ \vdots \ 6$)* | $\text{B}(6) = \{0; 6; 12; 18; 24; \dots\}$ *(Vì $0 \ \vdots \ 6$, $6 \ \vdots \ 6$, $12 \ \vdots \ 6$, ...)* |

> [!WARNING]
> **⚠️ LƯU Ý ĐẶC BIỆT VỀ SỐ 0 VÀ SỐ 1**
> - **Số 0:** Là **bội** của mọi số tự nhiên khác 0 (vì $0 \ \vdots \ b$ với mọi $b \neq 0$). Số 0 **không phải là ước** của bất kỳ số tự nhiên nào!
> - **Số 1:** Chỉ có duy nhất một ước là chính nó, nhưng lại là **ước** của mọi số tự nhiên (vì $a \ \vdots \ 1$ với mọi $a$).
> - **Mọi số tự nhiên $a > 1$** luôn có ít nhất hai ước là **$1$** và **chính nó ($a$)**.

---

## 2. Tính chất chia hết của một tổng

Làm thế nào để biết tổng $(24 + 36 + 120)$ có chia hết cho $6$ hay không mà không cần cộng chúng lại? Hãy áp dụng ngay 2 tính chất sau!

> [!IMPORTANT]
> **📌 TÍNH CHẤT 1 (Trường hợp chia hết)**
> Nếu tất cả các số hạng của một tổng đều chia hết cho cùng một số thì tổng chia hết cho số đó.
> - Nếu $a \ \vdots \ m$ và $b \ \vdots \ m$ thì $(a + b) \ \vdots \ m$.
> - **Mở rộng:** Nếu $a \ \vdots \ m$, $b \ \vdots \ m$ và $c \ \vdots \ m$ thì $(a + b + c) \ \vdots \ m$.
>
> **📌 TÍNH CHẤT 2 (Trường hợp không chia hết)**
> Nếu chỉ có **một** số hạng của tổng không chia hết cho một số, còn các số hạng khác đều chia hết cho số đó thì tổng không chia hết cho số đó.
> - Nếu $a \ \nmid \ m$ và $b \ \vdots \ m$ thì $(a + b) \ \nmid \ m$.
> - **Mở rộng:** Nếu $a \ \nmid \ m$, $b \ \vdots \ m$ và $c \ \vdots \ m$ thì $(a + b + c) \ \nmid \ m$.

**💡 Chú ý mở rộng cho phép trừ:**
- Với $a \ge b$: Nếu $a \ \vdots \ m$ và $b \ \vdots \ m$ thì $(a - b) \ \vdots \ m$.
- Nếu $a \ \nmid \ m$ và $b \ \vdots \ m$ (hoặc $a \ \vdots \ m$ và $b \ \nmid \ m$) thì $(a - b) \ \nmid \ m$.

---

## 3. Những "bẫy" toán học cần tránh

> [!CAUTION]
> **🚨 CẢNH BÁO CÁC LỖI SAI HỌC SINH LỚP 6 HAY MẮC PHẢI!**
> 
> **❌ Bẫy 1: Quên số $0$ khi tìm Bội và quên số $1$ hoặc chính nó khi tìm Ước.**
> - *Sai lầm:* Viết $\text{B}(5) = \{5; 10; 15; \dots\}$ (Thiếu số $0$ đầu tiên!).
> - *Sửa đúng:* $\text{B}(5) = \{0; 5; 10; 15; \dots\}$.
> 
> **❌ Bẫy 2: Dùng dấu ngoặc tròn `(...)` thay vì ngoặc nhọn `{...}` và dùng dấu phẩy `,` thay vì chấm phẩy `;` khi viết tập hợp.**
> - *Sửa đúng:* Luôn viết $\text{Ư}(8) = \{1; 2; 4; 8\}$.
> 
> **❌ Bẫy 3: Ngộ nhận về Tính chất 2 khi có từ HAI số hạng trở lên không chia hết!**
> - *Sai lầm:* Thấy $7 \ \nmid \ 5$ và $8 \ \nmid \ 5$ nên vội vàng kết luận $(7 + 8) \ \nmid \ 5$.
> - *Thực tế:* $7 + 8 = 15$, mà $15 \ \vdots \ 5$!
> - *Quy tắc vàng:* Nếu trong tổng có **từ 2 số hạng trở lên không chia hết** cho $m$, ta **KHÔNG ĐƯỢC** dùng ngay Tính chất 2 mà phải cộng các số hạng không chia hết đó lại (hoặc cộng phần dư của chúng) rồi mới xét tiếp!

---

## 4. Bài tập tự luyện nhanh

**Bài 1:** Tìm các tập hợp sau:
a) $\text{Ư}(18)$
b) $\text{B}(7)$ gồm các số nhỏ hơn $30$.

**Bài 2:** Không thực hiện phép tính, hãy cho biết các tổng/hiệu sau có chia hết cho $8$ không? Vì sao?
a) $A = 24 + 40 + 72$
b) $B = 80 + 16 - 13$
c) $C = 32 + 11 + 5$ *(Cẩn thận bẫy toán học nhé!)*

<details>
<summary><b>👉 Nhấn vào đây để xem Đáp án & Giải thích chi tiết</b></summary>

<br>

**Giải Bài 1:**
- **a)** Lần lượt chia $18$ cho các số từ $1$ đến $18$, ta được: $\text{Ư}(18) = \{1; 2; 3; 6; 9; 18\}$.
- **b)** Nhân $7$ lần lượt với $0; 1; 2; 3; 4$, ta được các bội nhỏ hơn $30$ là: $\{0; 7; 14; 21; 28\}$.

**Giải Bài 2:**
- **a)** Vì $24 \ \vdots \ 8$, $40 \ \vdots \ 8$ và $72 \ \vdots \ 8$ nên theo tính chất 1: $A = (24 + 40 + 72) \ \vdots \ 8$.
- **b)** Vì $80 \ \vdots \ 8$, $16 \ \vdots \ 8$ nhưng $13 \ \nmid \ 8$ nên theo tính chất 2: $B = (80 + 16 - 13) \ \nmid \ 8$.
- **c)** Ta thấy $11 \ \nmid \ 8$ và $5 \ \nmid \ 8$ (có 2 số không chia hết). Ta nhóm lại: $C = 32 + (11 + 5) = 32 + 16$. Vì $32 \ \vdots \ 8$ và $16 \ \vdots \ 8$ nên $C \ \vdots \ 8$.

</details>

---

[⬅️ Quay lại Trang chủ Mục lục](README.md)
