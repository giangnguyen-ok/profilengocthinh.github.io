<div style="background-color: orange;">
    <h2>Profile các bạn nhóm 5</h2>
    <ul>
        <li class="rainbow-text">Mình tên là Nguyễn Ngọc Thịnh,</li> hiện đang theo học tại ngôi trường THPT CHuyên Bến Tre, mình rất hân hạnh được giới với tất cả mọi người về bản thân mình</li>
    </ul>
    <script>
        // JavaScript để tạo hiệu ứng chuyển màu cầu vồng
        const rainbowText = document.querySelectorAll('.rainbow-text');

        rainbowText.forEach(text => {
            let hue = 0;
            const interval = setInterval(() => {
                hue++;
                if (hue >= 360) {
                    hue = 0;
                }
                text.style.color = `hsl(${hue}, 100%, 50%)`;
            }, 20);
        });
    </script>
    <image src="1.jpg">
    <li> Thông tin cá nhân
        <ol>
            <li>Họ và tên: Nguyễn Ngọc Thịnh</li>
            <li>Trường trung học phổ thông Chuyên Bến Tre</li>
            <li>Lớp: 12 Lý</li>
            <li>Giới tính: Nam</li> 
            <li>Cân nặng: 68kg</li>
            <li>Chiều cao: 1,8m</li>
        </ol>
    </li>
    <li> Nguyện vọng tương lai 
        <ol>
            <li>Khối thi là Khoa học tự nhiên </li>
            <li>Nguyện vọng 1 là Đại học Bách Khoa</li>
        </ol>
    </li>
</div>


