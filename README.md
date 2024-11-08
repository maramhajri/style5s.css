/* تغيير لون الخلفية */
body {
    background-color: #f9f9f9; /* لون خلفية هادئ */
    font-family: Arial, sans-serif; /* خط بسيط وسهل القراءة */
}

/* تحسين شكل العناوين */
h1, h2, h3, h4, h5, h6 {
    color: #333333; /* لون داكن للعناوين */
    text-align: center; /* توسيط العناوين */
}

/* تصميم الأزرار */
button, .btn {
    background-color: #007bff; /* لون أزرق للأزرار */
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover, .btn:hover {
    background-color: #0056b3; /* لون أزرق داكن عند تمرير الفأرة */
}

/* تصميم الروابط */
a {
    color: #007bff;
    text-decoration: none;
}

a:hover {
    color: #0056b3;
    text-decoration: underline;
}

/* تحسين شكل المنتجات */
.product-card {
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
    background-color: white;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease;
}

.product-card:hover {
    transform: scale(1.05); /* تكبير المنتج عند التمرير عليه */
}

/* تحسين شكل رأس الصفحة */
.header {
    background-color: #007bff;
    color: white;
    padding: 15px;
    text-align: center;
    font-size: 1.5em;
}

/* تصميم التذييل */
.footer {
    background-color: #333333;
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 0.9em;
}
