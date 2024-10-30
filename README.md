- <!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>მენტალური ჰოსპიტალი</title>
    <style>
        /* ძირითადი სტილები */
        body {
            font-family: Arial, sans-serif;
            color: #2e2e2e;
            background-color: #f4f8fb;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #6eb1d1;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .section {
            margin-bottom: 30px;
        }
        h1, h2, h3 {
            color: #3a5a76;
        }
        .quote {
            background-color: #eaf2f8;
            padding: 15px;
            margin: 10px 0;
            border-left: 5px solid #6eb1d1;
        }
        /* Roadmap-ის სექცია */
        .roadmap {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .roadmap-item {
            padding: 10px;
            background-color: #f0f5fa;
            border: 1px solid #d0e0ea;
            border-radius: 5px;
        }
        .psychologist {
            display: flex;
            gap: 15px;
            align-items: center;
            padding: 10px 0;
        }
        .psychologist img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
        }
    </style>
</head>
<body>

<header>
    <h1>მენტალური ჰოსპიტალი</h1>
    <p>დახმარება და მხარდაჭერა თქვენი მენტალური ჯანმრთელობისთვის</p>
</header>

<div class="content">
    <!-- მოტივაციური ციტატები -->
    <section class="section">
        <h2>მოტივაციური ფრაზები</h2>
        <div class="quote">"თქვენი ძლიერი მხარე იმალება იმ სირთულეებში, რომელთა გადალახვა გჭირდებათ."</div>
        <div class="quote">"ნუ ეცდებით ყველაფრის მოგვარებას ერთბაშად. ერთი ნაბიჯით დაიწყეთ."</div>
        <!-- შესაძლებელია დამატება სხვა ციტატების -->
    </section>

    <!-- Roadmap -->
    <section class="section">
        <h2>Roadmap</h2>
        <div class="roadmap">
            <div class="roadmap-item">1. პროგრამის ჩაშვება</div>
            <div class="roadmap-item">2. მომხმარებლებისთვის ვებსაიტის გაცნობა</div>
            <div class="roadmap-item">3. მომხმარებლის და მომწოდებლის ურთიერთკავშირი</div>
            <div class="roadmap-item">4. სიახლეები მიღებული ფიდბექებიდან</div>
            <div class="roadmap-item">5. აპლიკაციის გამოშვება</div>
        </div>
    </section>

    <!-- ფსიქოლოგები -->
    <section class="section">
        <h2>გამოცდილი ფსიქოლოგები</h2>
        <div class="psychologist">
            <img src="psychologist1.jpg" alt="ფსიქოლოგი 1">
            <div>
                <h3>დოქტორი ლიკა წერეთელი</h3>
                <p>გამოცდილი ფსიქოლოგი შფოთვითი აშლილობებისა და დეპრესიის მიმართულებით.</p>
            </div>
        </div>
        <div class="psychologist">
            <img src="psychologist2.jpg" alt="ფსიქოლოგი 2">
            <div>
                <h3>დოქტორი ნიკა მარგიანი</h3>
                <p>ექიმი და კოგნიტური თერაპიის სპეციალისტი.</p>
            </div>
        </div>
    </section>

    <!-- კონტაქტი -->
    <section class="section">
        <h2>კონტაქტი</h2>
        <form>
            <label for="message">მოსაზრება:</label><br>
            <textarea id="message" rows="4" cols="50"></textarea><br><br>
            <button type="submit">გაგზავნა</button>
        </form>
    </section>
</div>

</body>
</html>
