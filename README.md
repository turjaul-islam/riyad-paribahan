# riyad-paribahan<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <title>রিয়াদ পরিবহন</title>
    <style>
        body {
            font-family: sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        form {
            margin-top: 10px;
        }
        label, select, input {
            margin: 10px 5px;
            padding: 5px;
        }
        button {
            padding: 7px 15px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            background-color: #ddd;
            text-align: center;
            padding: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <h1># রিয়াদ পরিবহন</h1>
        <p>আপনার বিশ্বস্ত ভ্রমণ সঙ্গী</p>
    </header>

    <nav>
        <a href="#">হোম</a>
        <a href="#">বুকিং</a>
        <a href="#">যোগাযোগ</a>
        <a href="#">প্রশ্নোত্তর</a>
    </nav>

    <section>
        <h2>স্বাগতম!</h2>
        <p>রিয়াদ পরিবহন আপনাকে দেশের যেকোনো প্রান্তে দ্রুত ও নিরাপদে পৌঁছে দেয়।</p>

        <h3>টিকিট বুকিং</h3>
        <form>
            <label for="from">যাত্রা শুরুর স্থান:</label>
            <select id="from">
                <option>ঢাকা</option>
                <option>চট্টগ্রাম</option>
                <option>রাজশাহী</option>
            </select>

            <label for="to">গন্তব্য:</label>
            <select id="to">
                <option>খুলনা</option>
                <option>সিলেট</option>
                <option>বরিশাল</option>
            </select>

            <label for="date">তারিখ নির্বাচন:</label>
            <input type="date" id="date">

            <button type="submit">বুক করুন</button>
        </form>
    </section>

    <section>
        <h3>যোগাযোগ করুন</h3>
        <p>ফোন: ০১৭xxxxxxxxx</p>
        <p>ইমেইল: contact@riyadparibahan.com</p>
    </section>

    <section>
        <h3>প্রশ্নোত্তর</h3>
        <p><strong>প্রশ্ন:</strong> কীভাবে টিকিট বুক করব?<br>
        <strong>উত্তর:</strong> উপরের ফর্ম পূরণ করে "বুক করুন" চাপ দিন।</p>

        <p><strong>প্রশ্ন:</strong> টাকা কিভাবে দেব?<br>
        <strong>উত্তর:</strong> মোবাইল ব্যাংকিং/অফিসে গিয়েও দিতে পারেন।</p>
    </section>

    <footer>
        © ২০২৫ রিয়াদ পরিবহন | সর্বস্বত্ব সংরক্ষিত
    </footer>

</body>
</html>

