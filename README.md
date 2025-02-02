<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kako Student Može Zaraditi</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="language-selector">
            <select id="language-select">
                <option value="en">English</option>
                <option value="sr">Srpski</option>
            </select>
        </div>
        <h1>Kako studenti mogu da zarade</h1>
    </header>
    
    <div class="main-content">
        <div class="categories">
            <!-- Influencing Category -->
            <div class="category-box">
                <h3>Influencing</h3>
                <p>Influencing je jedan od najbrže rastućih načina zarade. Koristeći društvene mreže kao Instagram ili TikTok, možete promovirati proizvode i zarađivati putem sponzorstava.</p>
            </div>
            <!-- Photo Editing Category -->
            <div class="category-box">
                <h3>Photo Editing</h3>
                <p>Sa stručnostima u uređivanju fotografija, možete raditi kao freelancer i pružiti usluge za društvene mreže ili brendove koji žele da poboljšaju vizualni sadržaj.</p>
            </div>
            <!-- Web Development Category -->
            <div class="category-box">
                <h3>Web Development</h3>
                <p>Web development je veoma tražena veština. Sa osnovnim znanjem HTML-a, CSS-a i JavaScript-a, možete raditi kao freelancer i praviti sajtove za klijente.</p>
            </div>
            <!-- Graphic Design Category -->
            <div class="category-box">
                <h3>Graphic Design</h3>
                <p>Grafički dizajneri rade na kreiranju vizualnih sadržaja, kao što su logotipi, brošure, posteri i drugi dizajni za kompanije ili pojedince.</p>
            </div>
            <!-- Content Writing Category -->
            <div class="category-box">
                <h3>Content Writing</h3>
                <p>Pisanje sadržaja za blogove, web stranice i druge online platforme može doneti dobar prihod. Potrebna je kreativnost i znanje o SEO-u.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2025 Kako studenti mogu da zarade. Sva prava zadržana.</p>
    </footer>

    <script>
        // Language switcher logic (simple)
        const languageSelect = document.getElementById('language-select');
        languageSelect.addEventListener('change', function() {
            if (languageSelect.value === 'sr') {
                document.querySelector('h1').innerText = "Kako studenti mogu da zarade";
                document.querySelectorAll('.category-box h3')[0].innerText = "Influencer";
                document.querySelectorAll('.category-box p')[0].innerText = "Influencer je jedan od najbrže rastućih načina zarade...";
                document.querySelectorAll('.category-box h3')[1].innerText = "Fotografsko uređivanje";
                document.querySelectorAll('.category-box p')[1].innerText = "Sa stručnostima u uređivanju fotografija...";
                document.querySelectorAll('.category-box h3')[2].innerText = "Web razvoj";
                document.querySelectorAll('.category-box p')[2].innerText = "Web razvoj je veoma tražena veština...";
                document.querySelectorAll('.category-box h3')[3].innerText = "Grafički dizajn";
                document.querySelectorAll('.category-box p')[3].innerText = "Grafički dizajneri rade na kreiranju...";
                document.querySelectorAll('.category-box h3')[4].innerText = "Pisanje sadržaja";
                document.querySelectorAll('.category-box p')[4].innerText = "Pisanje sadržaja za blogove...";
            } else {
                document.querySelector('h1').innerText = "How Students Can Earn";
                document.querySelectorAll('.category-box h3')[0].innerText = "Influencing";
                document.querySelectorAll('.category-box p')[0].innerText = "Influencing is one of the fastest-growing ways to earn...";
                document.querySelectorAll('.category-box h3')[1].innerText = "Photo Editing";
                document.querySelectorAll('.category-box p')[1].innerText = "With skills in photo editing, you can work as a freelancer...";
                document.querySelectorAll('.category-box h3')[2].innerText = "Web Development";
                document.querySelectorAll('.category-box p')[2].innerText = "Web development is a highly sought-after skill...";
                document.querySelectorAll('.category-box h3')[3].innerText = "Graphic Design";
                document.querySelectorAll('.category-box p')[3].innerText = "Graphic designers create visual content...";
                document.querySelectorAll('.category-box h3')[4].innerText = "Content Writing";
                document.querySelectorAll('.category-box p')[4].innerText = "Content writing for blogs, websites...";
            }
        });
    </script>
</body>
</html>