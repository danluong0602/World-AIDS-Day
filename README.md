<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>World AIDS Day</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        .menu-container {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: 20px auto; /* Căn giữa trên máy tính */
            border-radius: 8px;
        }

        .menu-header {
            background-color: #d60000;
            color: #fff;
            padding: 15px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            cursor: pointer;
            border-radius: 8px 8px 0 0;
        }

        .menu-header img {
            max-width: 120px;
        }

        .menu-header button {
            background: none;
            border: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
        }

        .menu {
            list-style: none;
            margin: 0;
            padding: 0;
            display: none;
            background-color: white;
            border-radius: 0 0 8px 8px;
        }

        .menu-item {
            padding: 14px 20px;
            border-bottom: 1px solid #f0f0f0;
            display: flex;
            align-items: center;
            cursor: pointer;
        }

        .menu-item:hover {
            background-color: #f9f9f9;
        }

        .menu-item a {
            text-decoration: none;
            color: #333;
            flex-grow: 1;
        }

        .menu.show {
            display: block;
        }

        /* Responsive cho thiết bị di động */
        @media (max-width: 768px) {
            .menu-container {
                width: 100%;
                max-width: 100%;
                border-radius: 0;
            }

            .menu-header img {
                max-width: 100px;
            }
        }
    </style>
</head>

<body>

    <div class="menu-container">
        <div class="menu-header" id="menu-toggle">
            <img class="img-responsive" alt="Logo"
                src="https://84864c160d.vws.vegacdn.vn/UploadImages/Config/thptduongvanduong/Logo/logo-01.png">
	    <img class="img-responsive" alt="Logo" src="https://lh3.googleusercontent.com/pw/AP1GczNyLL1QtsdXOcFMtRSRx5xOjlRpBxSamysraju5BPWEGdI0mJsvu5cuDtREWZo2mxP-zMaWtCjBNXeDYmzCcUfl25LnZIujhoBryX3l4jyhStfxlw=w2400">

            <button>&#9776;</button>
        </div>
        <ul class="menu" id="menu">
            <li class="menu-item"><a href="#1.">HIV là gì?</a></li>
            <li class="menu-item"><a href="#2.">AIDS là gì?</a></li>
            <li class="menu-item"><a href="#3.">Con đường lây truyền HIV</a></li>
            <li class="menu-item"><a href="#4.">Triệu chứng của HIV</a></li>
            <li class="menu-item"><a href="#5.">Chẩn đoán HIV</a></li>
            <li class="menu-item"><a href="#6.">Điều trị HIV</a></li>
            <li class="menu-item"><a href="#7.">Phòng ngừa HIV</a></li>
            <li class="menu-item"><a href="#8.">Những quan niệm sai lầm về HIV/AIDS</a></li>
        </ul>
    </div>

    <script>
        const menuToggle = document.getElementById('menu-toggle');
        const menu = document.getElementById('menu');

        menuToggle.addEventListener('click', () => {
            menu.classList.toggle('show');
        });
    </script>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>World AIDS Day</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #eef5f9;
        }

        .banner {
            position: relative;
            text-align: center;
            background-image: url('https://lh3.googleusercontent.com/pw/AP1GczNAIdZ7JsU7XUT2MM0emQAtnZsdScjVQKNCRSk3ODOG6bUKe1piFOQyTy48KVB1x6_RjJGA-eXAhiyfPa1mpuFK0KmJZnZZYLebAkLbGiUdWV0eUA=w2400'); /* Đường dẫn ảnh */
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
        }

        .banner h1 {
            font-size: 60px;
            margin: 0;
            color: white; /* Đổi màu chữ thành trắng */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .banner h2 {
            font-size: 30px;
            margin: 10px 0;
            color: white; /* Đổi màu chữ thành trắng */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .banner h3 {
            background-color: #567dbd;
            color: white;
            padding: 10px 20px;
            border: none;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px; /* Khoảng cách giữa chữ và nút */
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1>World AIDS Day</h1>
        <h2>December 1</h2>
        <h3>Read More ⭣</h3>
    </div>
<!DOCTYPE html>
            <html lang="vi">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>HIV/AIDS: Những điều cần biết</title>
                <style>
                    body {
                        font-family: Arial, sans-serif;
                        line-height: 1.6;
                        margin: 20px;
                        background-color: #f8f9fa;
                        text-align: left; /* Đảm bảo toàn bộ văn bản căn lề trái */
                    }
                    .container {
                        max-width: 800px;
                        margin: 0 auto;
                        background: #fff;
                        padding: 20px;
                        border: 1px solid #ddd;
                        border-radius: 8px;
                        text-align: left; /* Căn lề trái trong container */
                    }
                    h1 {
                        color: #d32f2f;
                        text-align: center;
                        margin-bottom: 20px;
                    }
                    h1 img {
                        vertical-align: middle;
                        margin-right: 10px;
                    }
                    h2 {
                        color: #333;
                        margin-top: 20px;
                    }
                    ul {
                        margin-left: 20px;
                        list-style: disc;
                    }
                    li {
                        margin-bottom: 10px;
                    }
                    .highlight {
                        color: #d32f2f;
                        font-weight: bold;
                    }
                    .small-note {
                        font-size: 0.9em;
                        color: #555;
                    }
                </style>
            </head>
            <body>
                <div class="container">
                    <h1> HIV/AIDS: Những điều cần biết</h1>
<p>Mỗi năm, hàng triệu người trên thế giới nhiễm HIV, và con số này vẫn tiếp tục tăng.</p>
    <p>Tại Việt Nam, số người nhiễm HIV đang có xu hướng trẻ hóa, đòi hỏi chúng ta phải có những giải pháp cấp bách.</p>
    <p>Dưới đây là một số video tài liệu về tình hình HIV/AIDS hiện nay tại Việt Nam:</p>
    <p style="text-align: center; font-size: 24px; color: #d32f2f; font-weight: bold;">⭣</p>

    <style>
        
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* Tỉ lệ 16:9 */
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
            margin-bottom: 20px;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <!-- Video đầu tiên -->
    <div class="video-container">
        <iframe 
            src="https://www.youtube.com/embed/YfqvzmJXwhE" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>
    </div>

    <!-- Video thứ hai -->
    <div class="video-container">
    <iframe 
        src="https://www.youtube.com/embed/374cNIh2a3M?start=1" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</div>

</body>



<hr>                    
                    <h2 id="1.">1. HIV là gì?</h2>
                    <p>
                        HIV (<span class="highlight">Human Immunodeficiency Virus</span>) là virus gây suy giảm miễn dịch ở người. 
                        <p>Virus này <b>tấn công và làm suy yếu hệ miễn dịch</b>, đặc biệt là các tế bào CD4 (một loại tế bào bạch cầu quan trọng trong hệ miễn dịch). 
                    </p>
                    <p><b>Nếu không được điều trị</b>, HIV có thể dẫn đến <span class="highlight">giai đoạn cuối gọi là AIDS</span> (Acquired Immunodeficiency Syndrome).</p>
<hr>                    
                    <h2 id="2.">2. AIDS là gì?</h2>
                    <p>
                        <b>AIDS</b> là giai đoạn cuối cùng của nhiễm HIV, khi hệ miễn dịch bị suy giảm nghiêm trọng và cơ thể dễ bị các bệnh nhiễm trùng hoặc ung thư.
                    </p>
                    <ul>
                        <p>Một người được chẩn đoán là AIDS khi:</p>
                            <ul>
                                <li>Số lượng tế bào CD4 giảm xuống dưới <span class="highlight">200 tế bào/mm³ máu</span>.</li>
                                <li>Xuất hiện một hoặc nhiều bệnh chẳng hạn như: <span class="highlight">viêm phổi, lao phổi, hoặc ung thư Kaposi</span>.</li>
                            </ul>
                        </p>
                    </ul>
<hr>            
                    <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HIV Lây Truyền</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        .content {
            padding: 20px;
            text-align: left;
        }

        h2, h3, h4 {
            color: #d60000;
        }

        .image-container {
            position: relative;
            width: 100%;
            height: auto;
            overflow: hidden;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Giúp hình ảnh hiển thị đầy đủ */
        }

        ul, li {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 8px;
        }

        .note {
            font-style: italic;
            color: #555;
        }
    </style>
</head>

<body>

<div class="content">
    <h2 id="3.">3. HIV lây qua con đường nào?</h2>

    <!-- Hình ảnh full màn hình -->
    <div class="image-container">
        <img src="https://lh3.googleusercontent.com/pw/AP1GczNOVlXQ2TRSe9XHhcfPXrYOvU0Pz5IgPN9EJ32AYj7k_Yy52L2yAKbHMyzTcIhRsIiZ9OaPF3CZ1v5WZ47rEeweIIO3KF8nW3IlEx14Zh2hYNdlxg=w2400" alt="HIV Transmission Image">
    </div>

    <h3>▶ HIV Lây Truyền Qua Đường Nào?</h3>
    <p><b>1. Qua Đường Máu:</b></p>
    <ul>
        <li>Truyền máu hoặc chế phẩm từ máu bị nhiễm HIV.</li>
        <li>Dùng chung kim tiêm, ống tiêm, dụng cụ xăm mình hoặc xỏ khuyên không được tiệt trùng.</li>
        <li>Tiếp xúc với vết thương hở hoặc máu của người nhiễm HIV.</li>
    </ul>

    <p><b>2. Qua Đường Tình Dục:</b></p>
    <ul>
        <li>Quan hệ tình dục không an toàn (không dùng bao cao su) qua âm đạo, hậu môn, hoặc miệng với người nhiễm HIV.</li>
        <li>Nguy cơ cao hơn khi có tổn thương hoặc bệnh lây truyền qua đường tình dục khác.</li>
    </ul>

    <p><b>3. Từ Mẹ Sang Con:</b></p>
    <ul>
        <li>Trong quá trình mang thai, sinh con hoặc khi cho con bú. Tuy nhiên, nguy cơ này có thể giảm đáng kể nếu người mẹ được điều trị bằng thuốc kháng virus (ARV).</li>
    </ul>

    <h3>▶ HIV KHÔNG Lây Truyền Qua Đường Nào?</h3>
    <p>1. Tiếp Xúc Thông Thường:</p>
    <ul>
        <li>Bắt tay, ôm, hôn xã giao.</li>
        <li>Sử dụng chung đồ dùng sinh hoạt như chén, đũa, ly, khăn tắm.</li>
    </ul>

    <p>2. Đường Hô Hấp và Da:</p>
    <ul>
        <li>Hít thở không khí chung với người nhiễm HIV.</li>
        <li>Muỗi đốt hoặc côn trùng cắn.</li>
        <li>Tiếp xúc với mồ hôi, nước mắt hoặc nước bọt (trừ khi có máu trong đó và tiếp xúc với vết thương hở).</li>
    </ul>

    <p>3. Môi Trường Học Đường và Nơi Làm Việc:</p>
    <ul>
        <li>Làm việc hoặc học tập cùng người nhiễm HIV không gây nguy cơ lây nhiễm.</li>
        <li>Chơi thể thao hoặc bơi chung hồ bơi.</li>
    </ul>

    <h4 class="note">Lưu ý: HIV chỉ lây qua các con đường trực tiếp với dịch cơ thể chứa virus và không thể sống lâu bên ngoài cơ thể người. Vì vậy, hiểu biết đúng sẽ giúp bạn phòng tránh và tránh kỳ thị người nhiễm HIV.</h4>
</div>

</body>

</html>

<hr>                    
                    <h2 id="4.">4. Triệu chứng của HIV</h2>
<img src="https://lh3.googleusercontent.com/pw/AP1GczP0xH_E3_dg9RBz8nuepohJwFD-TizB6Vxb2uSJsSHlh3nk0FWt-Uuw-XF38eTEnR8OMrSEkek26mFVYDVsk9H07Lk16IJVsHa5b_cUAA6-zdVJEA=w2400" 
     alt="Triệu chứng HIV" 
     style="width: 100%; max-width: 600px; display: block; margin: 10px auto;">
<p>Nhiễm HIV thường trải qua ba giai đoạn chính:</p>
<ul>
    <li><p><span class="highlight">Giai đoạn 1:</span> Nhiễm cấp tính (2-4 tuần sau khi phơi nhiễm).</p>
        <ul>
            <li>Triệu chứng giống cúm: <b>sốt, mệt mỏi, phát ban, đau họng</b>.</li>
            <li>Virus nhân lên nhanh chóng và làm giảm tế bào CD4.</li>
        </ul>
    </li>
    <li><p><span class="highlight">Giai đoạn 2:</span> Giai đoạn tiềm ẩn (kéo dài nhiều năm).</p>
        <ul>
            <li>Ít triệu chứng hoặc không có triệu chứng.</li>
            <li>HIV vẫn âm thầm nhân lên trong cơ thể.</li>
        </ul>
    </li>
    <li><p><span class="highlight">Giai đoạn 3:</span> AIDS.</p>
        <ul>
            <li>Triệu chứng rõ rệt: <b>sút cân nghiêm trọng, mệt mỏi, nhiễm trùng thường xuyên, đổ mồ hôi đêm, sốt kéo dài</b>.</li>
        </ul>
    </li>
</ul>

<hr>            
                    <h2 id="5.">5. Chẩn đoán HIV</h2>
                    <ul>
                        <p>- <b>Xét nghiệm máu</b> là phương pháp chính xác nhất để chẩn đoán HIV.</p>
                        <p>- Các xét nghiệm phổ biến bao gồm: </p>
<li>	<b>Xét nghiệm kháng thể/kháng nguyên HIV</b> (ELISA, Western Blot).</li>
<li>	<b>Xét nghiệm PCR</b> (đo tải lượng virus).</li>
<li>	<b>Xét nghiệm nhanh HIV</b> (cho kết quả sau 20-30 phút).</li>
                    </ul>
<hr>
                    <h2 id="6.">6. Điều trị HIV</h2>
                    <p>Hiện nay <b>chưa có thuốc chữa khỏi hoàn toàn HIV</b>, nhưng có thể <b>kiểm soát virus bằng thuốc kháng virus (ARV)</b>.</p>
<p>	<b>ARV (Antiretroviral Therapy):</b> </p>
<li>	Giúp <b>giảm tải lượng virus</b> trong máu xuống mức không phát hiện được.</li>
<li>	<b>Ngăn ngừa sự phát triển của AIDS</b>.</li>
<li>	<b>Giảm nguy cơ lây truyền HIV</b> cho người khác.</li>
<p><b>Người nhiễm HIV cần dùng ARV suốt đời</b> để kiểm soát bệnh.</p>


<hr>
<h2 id="7.">7. Phòng ngừa HIV</h2>
                    <p><b>Các biện pháp phòng ngừa HIV hiệu quả:</b></p>
<p>	<b>Sử dụng bao cao su đúng cách</b> khi quan hệ tình dục. </p>
<li>	<b>Không dùng chung kim tiêm</b> hoặc <b>vật dụng cá nhân có thể dính máu</b>.</li>
<li>	<b>Xét nghiệm HIV định kỳ</b> nếu có nguy cơ phơi nhiễm.</li>
<li>	<b>Sử dụng PrEP</b> (dự phòng trước phơi nhiễm) hoặc <b>PEP</b> (dự phòng sau phơi nhiễm) theo chỉ dẫn của bác sĩ.</li>
<li>	<b>Phụ nữ mang thai nhiễm HIV nên điều trị ARV</b> để giảm nguy cơ lây truyền cho con.</li>
<hr>
<h2 id="8.">8. Những quan niệm sai lầm về HIV/AIDS</h2>
<li>	<b>HIV không phải là án tử hình:</b> Với điều trị ARV, người nhiễm HIV có thể sống lâu và khỏe mạnh như người bình thường.</li>
<li>	<b>HIV không lây qua các tiếp xúc thông thường</b> như ôm, hôn, hoặc bắt tay.</li>
<li>	<b>HIV không chỉ lây qua người đồng tính:</b> Bất kỳ ai quan hệ tình dục không an toàn hoặc tiếp xúc với máu nhiễm HIV đều có nguy cơ.</li>
<hr>
<h2>☞ KẾT LUẬN</h2>
<p>HIV/AIDS vẫn là một vấn đề sức khỏe toàn cầu, nhưng với sự tiến bộ của y học, việc <b>phòng ngừa, chẩn đoán sớm và điều trị kịp thời</b> có thể giúp người nhiễm HIV sống khỏe mạnh và giảm thiểu nguy cơ lây lan.</p>

                </div>
            </body>
            </html>
            
            
        </div>
    </div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footer Example</title>
    <style>
        .footer {
            background-color: red;
            color: white; /* Áp dụng màu trắng cho toàn bộ chữ */
            text-align: center;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
        .footer img {
            max-width: 100px;
            margin: 10px;
        }
        .footer h3 {
            margin: 20px 0 10px;
        }
        .footer ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .footer ul li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <footer class="footer">
        <div>
            <img class="img-responsive" alt="Logo" src="https://84864c160d.vws.vegacdn.vn/UploadImages/Config/thptduongvanduong/Logo/logo-01.png">
            <img class="img-responsive" alt="Logo" src="https://lh3.googleusercontent.com/pw/AP1GczNyLL1QtsdXOcFMtRSRx5xOjlRpBxSamysraju5BPWEGdI0mJsvu5cuDtREWZo2mxP-zMaWtCjBNXeDYmzCcUfl25LnZIujhoBryX3l4jyhStfxlw=w2400">
        </div>
        <h3>THÀNH VIÊN THỰC HIỆN</h3>
        <ul>
            <li>Lương Đức Dân - 12B8</li>
            <li>Đặng Phước Đông - 12B8</li>
            <li>Nguyễn Thanh Phúc - 12B8</li>
            <li>Phạm Hoàng Khiêm - 12B8</li>
            <li>Mai Thị Ngọc Linh - 12B8</li>
        </ul>
    </footer>
</body>
</html>


</body>

</html>
