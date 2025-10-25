<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Revenue Projections Summary</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; background: linear-gradient(135deg, #667eea, #764ba2); padding: 20px; }
        .container { max-width: 1600px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 0; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #667eea; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        .lang-btn { padding: 12px 30px; border: 2px solid #667eea; background: white; color: #667eea; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; transition: all 0.3s ease; }
        .lang-btn:hover { background: #f0f0ff; transform: translateY(-2px); }
        .lang-btn.active { background: #667eea; color: white; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
        .header { background: linear-gradient(135deg, #1e3c72, #2a5298); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 4em; margin-bottom: 20px; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .revenue-table { width: 100%; border-collapse: collapse; margin: 30px 0; }
        .revenue-table th { background: #667eea; color: white; padding: 15px; text-align: left; }
        .revenue-table td { padding: 15px; border-bottom: 1px solid #ddd; }
        .revenue-table tr:hover { background: #f0f0ff; }
        .total-row { background: #27ae60 !important; color: white; font-weight: bold; font-size: 1.3em; }
        .back-link { display: inline-block; background: #3498db; color: white; padding: 12px 30px; border-radius: 8px; text-decoration: none; margin: 20px 0; font-weight: bold; }
        .back-link:hover { background: #2980b9; }
        .highlight-box { background: linear-gradient(135deg, #667eea, #764ba2); color: white; padding: 40px; border-radius: 15px; margin: 30px 0; text-align: center; }
        .highlight-box h2 { font-size: 3em; margin-bottom: 15px; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>📊 REVENUE PROJECTIONS</h1>
                <p style="font-size: 1.8em;">Complete Financial Summary - All 11 Strategies</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>

                <div class="highlight-box">
                    <h2>$2.8M - $5.9M</h2>
                    <p style="font-size: 1.5em;">Year 1 Conservative Target (4 Core Strategies)</p>
                </div>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #1e3c72;">Year 1 Revenue by Strategy</h2>

                <table class="revenue-table">
                    <thead>
                        <tr>
                            <th style="width: 10%;">#</th>
                            <th style="width: 45%;">Strategy</th>
                            <th style="width: 22.5%;">Low Estimate</th>
                            <th style="width: 22.5%;">High Estimate</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td><strong>Emergency Hospital Delivery</strong></td>
                            <td>$560,000</td>
                            <td>$1,600,000</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td><strong>Golf Course Programs</strong></td>
                            <td>$280,000</td>
                            <td>$700,000</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td><strong>Resilient Medical Supply</strong></td>
                            <td>$500,000</td>
                            <td>$1,000,000</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td><strong>Equipment Rental Programs</strong></td>
                            <td>$600,000</td>
                            <td>$1,100,000</td>
                        </tr>
                        <tr>
                            <td>5</td>
                            <td><strong>Facility Storage Cabinets</strong></td>
                            <td>$450,000</td>
                            <td>$1,050,000</td>
                        </tr>
                        <tr>
                            <td>6</td>
                            <td><strong>Telehealth E-Commerce</strong></td>
                            <td>$900,000</td>
                            <td>$1,800,000</td>
                        </tr>
                        <tr>
                            <td>7</td>
                            <td><strong>Pharmacy Partnerships</strong></td>
                            <td>$280,000</td>
                            <td>$700,000</td>
                        </tr>
                        <tr>
                            <td>8</td>
                            <td><strong>Specialty Divisions</strong></td>
                            <td>$750,000</td>
                            <td>$1,500,000</td>
                        </tr>
                        <tr>
                            <td>9</td>
                            <td><strong>Home Modification Services</strong></td>
                            <td>$250,000</td>
                            <td>$550,000</td>
                        </tr>
                        <tr>
                            <td>10</td>
                            <td><strong>Virtual Care Services</strong></td>
                            <td>$350,000</td>
                            <td>$700,000</td>
                        </tr>
                        <tr>
                            <td>11</td>
                            <td><strong>General Product Lines</strong></td>
                            <td>$1,200,000</td>
                            <td>$2,300,000</td>
                        </tr>
                        <tr class="total-row">
                            <td colspan="2"><strong>TOTAL (All 11 Strategies)</strong></td>
                            <td><strong>$6.1M</strong></td>
                            <td><strong>$13.0M</strong></td>
                        </tr>
                        <tr style="background: #3498db; color: white; font-weight: bold;">
                            <td colspan="2"><strong>REALISTIC TARGET (4 Core Strategies: 1,4,6,11)</strong></td>
                            <td><strong>$2.8M</strong></td>
                            <td><strong>$5.9M</strong></td>
                        </tr>
                    </tbody>
                </table>

                <div style="background: #fff3cd; border-left: 5px solid #ffc107; padding: 30px; margin: 40px 0; border-radius: 8px;">
                    <h3 style="color: #856404; margin-bottom: 15px; font-size: 1.8em;">📌 Conservative Year 1 Approach</h3>
                    <p style="color: #856404; font-size: 1.2em; line-height: 1.8;">Focus on 4 core strategies in Year 1: Emergency Hospital Delivery (#1), Equipment Rental (#4), Telehealth E-Commerce (#6), and General Product Lines (#11). These provide the foundation with minimal overlap and maximum revenue potential ($2.8M - $5.9M).</p>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>📊 ПРОГНОЗЫ ДОХОДОВ</h1>
                <p style="font-size: 1.8em;">Полная Финансовая Сводка - Все 11 Стратегий</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>

                <div class="highlight-box">
                    <h2>$2.8M - $5.9M</h2>
                    <p style="font-size: 1.5em;">Консервативная Цель на 1-й Год (4 Основные Стратегии)</p>
                </div>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #1e3c72;">Доходы 1-го Года по Стратегиям</h2>

                <table class="revenue-table">
                    <thead>
                        <tr>
                            <th style="width: 10%;">#</th>
                            <th style="width: 45%;">Стратегия</th>
                            <th style="width: 22.5%;">Нижняя Оценка</th>
                            <th style="width: 22.5%;">Верхняя Оценка</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>1</td><td><strong>Экстренная Больничная Доставка</strong></td><td>$560,000</td><td>$1,600,000</td></tr>
                        <tr><td>2</td><td><strong>Программы Гольф-Клубов</strong></td><td>$280,000</td><td>$700,000</td></tr>
                        <tr><td>3</td><td><strong>Устойчивые Медицинские Поставки</strong></td><td>$500,000</td><td>$1,000,000</td></tr>
                        <tr><td>4</td><td><strong>Программы Аренды Оборудования</strong></td><td>$600,000</td><td>$1,100,000</td></tr>
                        <tr><td>5</td><td><strong>Складские Шкафы для Учреждений</strong></td><td>$450,000</td><td>$1,050,000</td></tr>
                        <tr><td>6</td><td><strong>Телемедицина и Э-Коммерция</strong></td><td>$900,000</td><td>$1,800,000</td></tr>
                        <tr><td>7</td><td><strong>Партнерства с Аптеками</strong></td><td>$280,000</td><td>$700,000</td></tr>
                        <tr><td>8</td><td><strong>Специализированные Подразделения</strong></td><td>$750,000</td><td>$1,500,000</td></tr>
                        <tr><td>9</td><td><strong>Услуги по Модификации Домов</strong></td><td>$250,000</td><td>$550,000</td></tr>
                        <tr><td>10</td><td><strong>Услуги Виртуальной Помощи</strong></td><td>$350,000</td><td>$700,000</td></tr>
                        <tr><td>11</td><td><strong>Общие Линейки Продуктов</strong></td><td>$1,200,000</td><td>$2,300,000</td></tr>
                        <tr class="total-row"><td colspan="2"><strong>ИТОГО (Все 11 Стратегий)</strong></td><td><strong>$6.1M</strong></td><td><strong>$13.0M</strong></td></tr>
                        <tr style="background: #3498db; color: white; font-weight: bold;"><td colspan="2"><strong>РЕАЛИСТИЧНАЯ ЦЕЛЬ (4 Основные: 1,4,6,11)</strong></td><td><strong>$2.8M</strong></td><td><strong>$5.9M</strong></td></tr>
                    </tbody>
                </table>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>📊 DAROMAD PROGNOZLARI</h1>
                <p style="font-size: 1.8em;">To'liq Moliyaviy Xulosa - Barcha 11 Strategiya</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>

                <div class="highlight-box">
                    <h2>$2.8M - $5.9M</h2>
                    <p style="font-size: 1.5em;">1-Yil Konservativ Maqsad (4 Asosiy Strategiya)</p>
                </div>

                <h2 style="font-size: 2.5em; margin: 40px 0 30px 0; text-align: center; color: #1e3c72;">1-Yil Daromadlari Strategiya Bo'yicha</h2>

                <table class="revenue-table">
                    <thead>
                        <tr>
                            <th style="width: 10%;">#</th>
                            <th style="width: 45%;">Strategiya</th>
                            <th style="width: 22.5%;">Past Baho</th>
                            <th style="width: 22.5%;">Yuqori Baho</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>1</td><td><strong>Shoshilinch Kasalxona Yetkazish</strong></td><td>$560,000</td><td>$1,600,000</td></tr>
                        <tr><td>2</td><td><strong>Golf Klub Dasturlari</strong></td><td>$280,000</td><td>$700,000</td></tr>
                        <tr><td>3</td><td><strong>Chidamli Tibbiy Ta'minot</strong></td><td>$500,000</td><td>$1,000,000</td></tr>
                        <tr><td>4</td><td><strong>Uskuna Ijara Dasturlari</strong></td><td>$600,000</td><td>$1,100,000</td></tr>
                        <tr><td>5</td><td><strong>Muassasalar Saqlash Shkaflar</strong></td><td>$450,000</td><td>$1,050,000</td></tr>
                        <tr><td>6</td><td><strong>Teletibbiyot va E-Tijorat</strong></td><td>$900,000</td><td>$1,800,000</td></tr>
                        <tr><td>7</td><td><strong>Dorixonalar bilan Hamkorlik</strong></td><td>$280,000</td><td>$700,000</td></tr>
                        <tr><td>8</td><td><strong>Maxsus Bo'limlar</strong></td><td>$750,000</td><td>$1,500,000</td></tr>
                        <tr><td>9</td><td><strong>Uy Modifikatsiya Xizmatlari</strong></td><td>$250,000</td><td>$550,000</td></tr>
                        <tr><td>10</td><td><strong>Virtual Tibbiy Xizmatlar</strong></td><td>$350,000</td><td>$700,000</td></tr>
                        <tr><td>11</td><td><strong>Umumiy Mahsulot Liniyalari</strong></td><td>$1,200,000</td><td>$2,300,000</td></tr>
                        <tr class="total-row"><td colspan="2"><strong>JAMI (Barcha 11 Strategiya)</strong></td><td><strong>$6.1M</strong></td><td><strong>$13.0M</strong></td></tr>
                        <tr style="background: #3498db; color: white; font-weight: bold;"><td colspan="2"><strong>HAQIQIY MAQSAD (4 Asosiy: 1,4,6,11)</strong></td><td><strong>$2.8M</strong></td><td><strong>$5.9M</strong></td></tr>
                    </tbody>
                </table>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => content.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            localStorage.setItem('preferred-language', lang);
            window.scrollTo(0, 0);
        }
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferred-language');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) switchLanguage(savedLang);
        });
    </script>
</body>
</html>
