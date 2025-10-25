<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Revenue Summary - CORRECTED</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 20px; }
        .container { max-width: 1600px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 20px; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #667eea; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        .lang-btn { padding: 12px 30px; border: 2px solid #667eea; background: white; color: #667eea; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; transition: all 0.3s ease; }
        .lang-btn:hover { background: #f0f4ff; transform: translateY(-2px); }
        .lang-btn.active { background: #667eea; color: white; }
        .header { background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 3.5em; margin-bottom: 20px; }
        .warning-banner { background: #f39c12; color: white; padding: 30px 40px; text-align: center; font-size: 1.3em; font-weight: bold; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .section-title { font-size: 2.5em; color: #1e3c72; margin-bottom: 30px; text-align: center; border-bottom: 4px solid #667eea; padding-bottom: 15px; }
        table { width: 100%; border-collapse: collapse; margin: 30px 0; background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        th { background: linear-gradient(135deg, #1e3c72, #2a5298); color: white; padding: 20px; text-align: left; font-size: 1.1em; }
        td { padding: 18px; border-bottom: 1px solid #e9ecef; }
        tr:hover { background: #f8f9fa; }
        .total-row { background: #fff3cd !important; font-weight: bold; font-size: 1.2em; }
        .revenue-box { background: linear-gradient(135deg, #27ae60, #2ecc71); color: white; padding: 40px; border-radius: 15px; margin: 30px 0; text-align: center; }
        .revenue-amount { font-size: 4em; font-weight: bold; display: block; margin: 20px 0; }
        .product-tag { display: inline-block; background: #667eea; color: white; padding: 8px 15px; border-radius: 20px; margin: 5px; font-size: 0.9em; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
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
                <h1>📊 COMPLETE REVENUE PROJECTIONS</h1>
                <p style="font-size: 1.5em;">11 Strategies with 36 BOC-Licensed DME Products</p>
            </div>

            <div class="warning-banner">
                ⚠️ COMPLETE PICTURE: Core BOC-licensed DME equipment (wheelchairs, hospital beds, braces, oxygen, etc.) generates 70-80% of revenue. Complementary products are 20-30%.
            </div>

            <div class="section">
                <div class="revenue-box">
                    <h3 style="font-size: 2em; margin-bottom: 20px;">TOTAL YEAR 1 REVENUE PROJECTION</h3>
                    <span class="revenue-amount">$5.58M - $11.05M</span>
                    <p style="font-size: 1.3em;">Combined Revenue Across All 11 Strategies</p>
                </div>

                <h2 class="section-title">💰 Complete Revenue Breakdown by Strategy</h2>
                
                <table>
                    <thead>
                        <tr>
                            <th>Strategy</th>
                            <th>Licensed DME<br/>(70-80%)</th>
                            <th>Complementary<br/>(20-30%)</th>
                            <th>TOTAL Year 1</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>1. Emergency Hospital Delivery</strong></td>
                            <td>$400K-$1.2M</td>
                            <td>$160K-$400K</td>
                            <td style="color: #e74c3c; font-weight: bold; font-size: 1.2em;">$560K-$1.6M</td>
                        </tr>
                        <tr>
                            <td><strong>2. Golf Course Programs</strong></td>
                            <td>$180K-$450K</td>
                            <td>$100K-$250K</td>
                            <td style="color: #27ae60; font-weight: bold; font-size: 1.2em;">$280K-$700K</td>
                        </tr>
                        <tr>
                            <td><strong>3. Resilient Medical Supply</strong></td>
                            <td>$300K-$600K</td>
                            <td>$200K-$400K</td>
                            <td style="color: #e67e22; font-weight: bold; font-size: 1.2em;">$500K-$1.0M</td>
                        </tr>
                        <tr>
                            <td><strong>4. Equipment Rental Programs</strong></td>
                            <td>$500K-$900K</td>
                            <td>$100K-$200K</td>
                            <td style="color: #9b59b6; font-weight: bold; font-size: 1.2em;">$600K-$1.1M</td>
                        </tr>
                        <tr>
                            <td><strong>5. Facility Storage Cabinets</strong></td>
                            <td>$280K-$700K</td>
                            <td>$120K-$300K</td>
                            <td style="color: #3498db; font-weight: bold; font-size: 1.2em;">$400K-$1.0M</td>
                        </tr>
                        <tr>
                            <td><strong>6. Telehealth E-Commerce</strong></td>
                            <td>$420K-$1.05M</td>
                            <td>$180K-$450K</td>
                            <td style="color: #1abc9c; font-weight: bold; font-size: 1.2em;">$600K-$1.5M</td>
                        </tr>
                        <tr>
                            <td><strong>7. Pharmacy Partnerships</strong></td>
                            <td>$280K-$700K</td>
                            <td>$120K-$300K</td>
                            <td style="color: #e91e63; font-weight: bold; font-size: 1.2em;">$400K-$1.0M</td>
                        </tr>
                        <tr>
                            <td><strong>8. Specialty Divisions</strong></td>
                            <td>$525K-$1.05M</td>
                            <td>$225K-$450K</td>
                            <td style="color: #f39c12; font-weight: bold; font-size: 1.2em;">$750K-$1.5M</td>
                        </tr>
                        <tr>
                            <td><strong>9. Home Modification</strong></td>
                            <td>$210K-$525K</td>
                            <td>$90K-$225K</td>
                            <td style="color: #795548; font-weight: bold; font-size: 1.2em;">$300K-$750K</td>
                        </tr>
                        <tr>
                            <td><strong>10. Virtual Care Services</strong></td>
                            <td>$168K-$420K</td>
                            <td>$72K-$180K</td>
                            <td style="color: #607d8b; font-weight: bold; font-size: 1.2em;">$240K-$600K</td>
                        </tr>
                        <tr>
                            <td><strong>11. General Product Lines</strong></td>
                            <td>$336K-$840K</td>
                            <td>$144K-$360K</td>
                            <td style="color: #ff9800; font-weight: bold; font-size: 1.2em;">$480K-$1.2M</td>
                        </tr>
                        <tr class="total-row">
                            <td><strong>COMBINED TOTAL</strong></td>
                            <td>$3.599M-$8.985M</td>
                            <td>$1.511M-$3.965M</td>
                            <td style="color: #27ae60; font-size: 1.4em;">$5.11M-$12.95M</td>
                        </tr>
                    </tbody>
                </table>

                <div style="background: #fff3cd; padding: 30px; border-radius: 10px; border-left: 6px solid #f39c12; margin: 30px 0;">
                    <h3 style="color: #856404; margin-bottom: 15px;">📊 Key Financial Insights:</h3>
                    <ul style="color: #856404; line-height: 2;">
                        <li><strong>Conservative Estimate (Low End):</strong> $5.11M Year 1</li>
                        <li><strong>Aggressive Estimate (High End):</strong> $12.95M Year 1</li>
                        <li><strong>Realistic Target (Mid-Range):</strong> $7-9M Year 1</li>
                        <li><strong>DME Equipment Percentage:</strong> 70-80% ($3.6M-$9M)</li>
                        <li><strong>Complementary Products:</strong> 20-30% ($1.5M-$4M)</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>📊 ПОЛНЫЕ ПРОГНОЗЫ ДОХОДА</h1>
                <p style="font-size: 1.5em;">11 Стратегий с 36 BOC-Лицензированными DME Продуктами</p>
            </div>

            <div class="warning-banner">
                ⚠️ ПОЛНАЯ КАРТИНА: Основное BOC-лицензированное DME оборудование (инвалидные коляски, больничные кровати, брейсы, кислород и т.д.) генерирует 70-80% дохода. Дополнительные продукты 20-30%.
            </div>

            <div class="section">
                <div class="revenue-box">
                    <h3 style="font-size: 2em; margin-bottom: 20px;">ОБЩИЙ ПРОГНОЗ ДОХОДА НА 1-Й ГОД</h3>
                    <span class="revenue-amount">$5.58M - $11.05M</span>
                    <p style="font-size: 1.3em;">Совокупный Доход по Всем 11 Стратегиям</p>
                </div>

                <h2 class="section-title">💰 Полная Разбивка Дохода по Стратегиям</h2>
                
                <table>
                    <thead>
                        <tr>
                            <th>Стратегия</th>
                            <th>Лицензированное DME<br/>(70-80%)</th>
                            <th>Дополнительные<br/>(20-30%)</th>
                            <th>ИТОГО 1-й Год</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td><strong>1. Экстренная Доставка в Больницы</strong></td><td>$400K-$1.2M</td><td>$160K-$400K</td><td style="color: #e74c3c; font-weight: bold;">$560K-$1.6M</td></tr>
                        <tr><td><strong>2. Программы на Гольф-Полях</strong></td><td>$180K-$450K</td><td>$100K-$250K</td><td style="color: #27ae60; font-weight: bold;">$280K-$700K</td></tr>
                        <tr><td><strong>3. Устойчивое Медицинское Снабжение</strong></td><td>$300K-$600K</td><td>$200K-$400K</td><td style="color: #e67e22; font-weight: bold;">$500K-$1.0M</td></tr>
                        <tr><td><strong>4. Программы Аренды Оборудования</strong></td><td>$500K-$900K</td><td>$100K-$200K</td><td style="color: #9b59b6; font-weight: bold;">$600K-$1.1M</td></tr>
                        <tr><td><strong>5. Складские Шкафы для Учреждений</strong></td><td>$280K-$700K</td><td>$120K-$300K</td><td style="color: #3498db; font-weight: bold;">$400K-$1.0M</td></tr>
                        <tr><td><strong>6. Телемедицина Электронная Коммерция</strong></td><td>$420K-$1.05M</td><td>$180K-$450K</td><td style="color: #1abc9c; font-weight: bold;">$600K-$1.5M</td></tr>
                        <tr><td><strong>7. Партнерства с Аптеками</strong></td><td>$280K-$700K</td><td>$120K-$300K</td><td style="color: #e91e63; font-weight: bold;">$400K-$1.0M</td></tr>
                        <tr><td><strong>8. Специализированные Подразделения</strong></td><td>$525K-$1.05M</td><td>$225K-$450K</td><td style="color: #f39c12; font-weight: bold;">$750K-$1.5M</td></tr>
                        <tr><td><strong>9. Модификация Домов</strong></td><td>$210K-$525K</td><td>$90K-$225K</td><td style="color: #795548; font-weight: bold;">$300K-$750K</td></tr>
                        <tr><td><strong>10. Виртуальные Медицинские Услуги</strong></td><td>$168K-$420K</td><td>$72K-$180K</td><td style="color: #607d8b; font-weight: bold;">$240K-$600K</td></tr>
                        <tr><td><strong>11. Общие Линейки Продуктов</strong></td><td>$336K-$840K</td><td>$144K-$360K</td><td style="color: #ff9800; font-weight: bold;">$480K-$1.2M</td></tr>
                        <tr class="total-row"><td><strong>ОБЩИЙ ИТОГ</strong></td><td>$3.599M-$8.985M</td><td>$1.511M-$3.965M</td><td style="color: #27ae60; font-size: 1.4em;">$5.11M-$12.95M</td></tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>📊 TO'LIQ DAROMAD PROGNOZLARI</h1>
                <p style="font-size: 1.5em;">36 BOC-Litsenziyalangan DME Mahsulotlar bilan 11 Strategiya</p>
            </div>

            <div class="warning-banner">
                ⚠️ TO'LIQ RASM: Asosiy BOC-litsenziyalangan DME uskuna (nogironlar aravachalari, shifoxona karavotlari, breyslar, kislorod va boshqalar) daromadning 70-80% ini ishlab chiqaradi. Qo'shimcha mahsulotlar 20-30%.
            </div>

            <div class="section">
                <div class="revenue-box">
                    <h3 style="font-size: 2em; margin-bottom: 20px;">1-YIL UCHUN UMUMIY DAROMAD PROGNOZI</h3>
                    <span class="revenue-amount">$5.58M - $11.05M</span>
                    <p style="font-size: 1.3em;">Barcha 11 Strategiya Bo'yicha Birlashgan Daromad</p>
                </div>

                <h2 class="section-title">💰 Strategiya Bo'yicha To'liq Daromad Taqsimoti</h2>
                
                <table>
                    <thead>
                        <tr>
                            <th>Strategiya</th>
                            <th>Litsenziyalangan DME<br/>(70-80%)</th>
                            <th>Qo'shimcha<br/>(20-30%)</th>
                            <th>JAMI 1-Yil</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td><strong>1. Shifoxonalarga Favqulodda Yetkazib Berish</strong></td><td>$400K-$1.2M</td><td>$160K-$400K</td><td style="color: #e74c3c; font-weight: bold;">$560K-$1.6M</td></tr>
                        <tr><td><strong>2. Golf Maydonchalari Dasturlari</strong></td><td>$180K-$450K</td><td>$100K-$250K</td><td style="color: #27ae60; font-weight: bold;">$280K-$700K</td></tr>
                        <tr><td><strong>3. Barqaror Tibbiy Ta'minot</strong></td><td>$300K-$600K</td><td>$200K-$400K</td><td style="color: #e67e22; font-weight: bold;">$500K-$1.0M</td></tr>
                        <tr><td><strong>4. Uskuna Ijarasi Dasturlari</strong></td><td>$500K-$900K</td><td>$100K-$200K</td><td style="color: #9b59b6; font-weight: bold;">$600K-$1.1M</td></tr>
                        <tr><td><strong>5. Muassasalar uchun Saqlash Shkaflari</strong></td><td>$280K-$700K</td><td>$120K-$300K</td><td style="color: #3498db; font-weight: bold;">$400K-$1.0M</td></tr>
                        <tr><td><strong>6. Telemeditsina Elektron Tijorat</strong></td><td>$420K-$1.05M</td><td>$180K-$450K</td><td style="color: #1abc9c; font-weight: bold;">$600K-$1.5M</td></tr>
                        <tr><td><strong>7. Dorixonalar bilan Hamkorlik</strong></td><td>$280K-$700K</td><td>$120K-$300K</td><td style="color: #e91e63; font-weight: bold;">$400K-$1.0M</td></tr>
                        <tr><td><strong>8. Maxsus Bo'limlar</strong></td><td>$525K-$1.05M</td><td>$225K-$450K</td><td style="color: #f39c12; font-weight: bold;">$750K-$1.5M</td></tr>
                        <tr><td><strong>9. Uyni Modernizatsiyalash</strong></td><td>$210K-$525K</td><td>$90K-$225K</td><td style="color: #795548; font-weight: bold;">$300K-$750K</td></tr>
                        <tr><td><strong>10. Virtual Tibbiy Xizmatlar</strong></td><td>$168K-$420K</td><td>$72K-$180K</td><td style="color: #607d8b; font-weight: bold;">$240K-$600K</td></tr>
                        <tr><td><strong>11. Umumiy Mahsulot Chiziqlari</strong></td><td>$336K-$840K</td><td>$144K-$360K</td><td style="color: #ff9800; font-weight: bold;">$480K-$1.2M</td></tr>
                        <tr class="total-row"><td><strong>UMUMIY JAMI</strong></td><td>$3.599M-$8.985M</td><td>$1.511M-$3.965M</td><td style="color: #27ae60; font-size: 1.4em;">$5.11M-$12.95M</td></tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(b => b.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            window.scrollTo(0, 0);
        }
    </script>
</body>
</html>
