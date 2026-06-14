<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Профессиональный опыт Ирины Щербич — налоговый менеджер, эксперт" />
  <title>Ирина Щербич — профессиональный опыт</title>
  <style>
    :root {
      --bg: #f7f9fc;
      --card: rgba(255, 255, 255, 0.86);
      --card-solid: #ffffff;
      --text: #172033;
      --muted: #607089;
      --accent: #2563eb;
      --accent-2: #0f766e;
      --accent-3: #7c3aed;
      --line: rgba(37, 99, 235, 0.15);
      --shadow: 0 20px 45px rgba(31, 41, 55, 0.10);
      --shadow-soft: 0 12px 25px rgba(31, 41, 55, 0.08);
      --radius: 24px;
      --max: 1180px;
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: Inter, "Segoe UI", Arial, sans-serif;
      color: var(--text);
      background:
        radial-gradient(circle at top left, rgba(37, 99, 235, 0.12), transparent 34rem),
        radial-gradient(circle at top right, rgba(15, 118, 110, 0.12), transparent 30rem),
        linear-gradient(180deg, #ffffff 0%, var(--bg) 45%, #eef4fb 100%);
      line-height: 1.65;
    }

    a { color: inherit; }

    .page {
      width: min(100% - 32px, var(--max));
      margin: 0 auto;
    }

    .hero {
      position: relative;
      overflow: hidden;
      margin: 28px auto 34px;
      padding: 34px;
      border: 1px solid rgba(255, 255, 255, 0.7);
      border-radius: 34px;
      background:
        linear-gradient(135deg, rgba(255,255,255,0.88), rgba(255,255,255,0.55)),
        linear-gradient(135deg, rgba(37, 99, 235, 0.16), rgba(15, 118, 110, 0.12), rgba(124, 58, 237, 0.10));
      box-shadow: var(--shadow);
      backdrop-filter: blur(18px);
    }

    .hero::before {
      content: "";
      position: absolute;
      inset: -120px -120px auto auto;
      width: 320px;
      height: 320px;
      border-radius: 999px;
      background: rgba(37, 99, 235, 0.14);
      filter: blur(8px);
    }

    .hero-grid {
      position: relative;
      display: grid;
      grid-template-columns: 1.25fr 340px;
      gap: 34px;
      align-items: center;
      z-index: 1;
    }

    .eyebrow {
      display: inline-flex;
      gap: 10px;
      align-items: center;
      padding: 8px 12px;
      border: 1px solid rgba(37, 99, 235, 0.18);
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.72);
      color: var(--accent);
      font-weight: 700;
      letter-spacing: .02em;
      font-size: 14px;
    }

    h1 {
      margin: 20px 0 10px;
      font-size: clamp(42px, 6vw, 76px);
      line-height: .95;
      letter-spacing: -0.06em;
      background: linear-gradient(90deg, #0f172a 0%, #2563eb 42%, #0f766e 72%, #7c3aed 100%);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }

    .subtitle {
      margin: 0;
      font-size: clamp(20px, 2.4vw, 30px);
      color: #26364f;
      font-weight: 700;
    }

    .contacts {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 24px;
    }

    .contact-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 10px 14px;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.82);
      border: 1px solid rgba(37, 99, 235, 0.14);
      color: #26364f;
      text-decoration: none;
      font-weight: 700;
      box-shadow: 0 8px 18px rgba(31, 41, 55, 0.06);
    }

    .photo-wrap {
      justify-self: end;
      position: relative;
      width: min(100%, 310px);
      aspect-ratio: 1 / 1;
      border-radius: 34px;
      padding: 10px;
      background: linear-gradient(135deg, rgba(37, 99, 235, .26), rgba(15, 118, 110, .18), rgba(255,255,255,.9));
      box-shadow: var(--shadow);
    }

    .photo-wrap img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center top;
      border-radius: 26px;
      display: block;
      background: #fff;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
      margin-top: 30px;
    }

    .stat-card {
      padding: 18px;
      border-radius: 20px;
      background: rgba(255, 255, 255, 0.76);
      border: 1px solid rgba(15, 118, 110, 0.12);
    }

    .stat-card strong {
      display: block;
      font-size: 28px;
      line-height: 1;
      color: var(--accent-2);
      margin-bottom: 8px;
    }

    .stat-card span { color: var(--muted); font-size: 14px; }

    .nav {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 30px;
      justify-content: center;
    }

    .nav a {
      text-decoration: none;
      padding: 10px 14px;
      border-radius: 999px;
      color: #34445e;
      background: rgba(255, 255, 255, 0.72);
      border: 1px solid rgba(37, 99, 235, 0.12);
      font-weight: 700;
      transition: transform .2s ease, box-shadow .2s ease, border-color .2s ease;
    }

    .nav a:hover {
      transform: translateY(-2px);
      box-shadow: var(--shadow-soft);
      border-color: rgba(37, 99, 235, 0.28);
    }

    section { margin: 28px 0; }

    .section-title {
      display: flex;
      align-items: center;
      gap: 12px;
      margin: 0 0 18px;
      font-size: clamp(26px, 3vw, 38px);
      letter-spacing: -0.035em;
    }

    .section-title::before {
      content: "";
      width: 12px;
      height: 36px;
      border-radius: 99px;
      background: linear-gradient(180deg, var(--accent), var(--accent-2));
      box-shadow: 0 8px 18px rgba(37, 99, 235, 0.22);
    }

    .card {
      background: var(--card);
      border: 1px solid rgba(255, 255, 255, 0.8);
      box-shadow: var(--shadow-soft);
      border-radius: var(--radius);
      padding: 26px;
      backdrop-filter: blur(12px);
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .skill-card {
      position: relative;
      overflow: hidden;
      min-height: 170px;
      padding: 24px;
      border-radius: 24px;
      background: var(--card-solid);
      border: 1px solid var(--line);
      box-shadow: 0 10px 24px rgba(31, 41, 55, 0.06);
      transition: transform .25s ease, box-shadow .25s ease, border-color .25s ease;
    }

    .skill-card::after {
      content: "";
      position: absolute;
      right: -50px;
      top: -50px;
      width: 120px;
      height: 120px;
      border-radius: 999px;
      background: rgba(37, 99, 235, .08);
      transition: transform .25s ease;
    }

    .skill-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 38px rgba(31, 41, 55, 0.12);
      border-color: rgba(37, 99, 235, 0.32);
    }

    .skill-card:hover::after { transform: scale(1.18); }

    .skill-card h3 { margin: 0 0 10px; font-size: 22px; }
    .skill-card p { margin: 0; color: var(--muted); }

    .timeline {
      position: relative;
      display: grid;
      gap: 20px;
    }

    .experience-card {
      display: grid;
      grid-template-columns: 180px 1fr;
      gap: 24px;
      padding: 26px;
      border-radius: 26px;
      background: rgba(255, 255, 255, 0.92);
      border: 1px solid rgba(37, 99, 235, 0.12);
      box-shadow: var(--shadow-soft);
    }

    .period {
      font-size: 18px;
      font-weight: 900;
      color: var(--accent);
      line-height: 1.25;
    }

    .company {
      margin: 0;
      font-size: 24px;
      line-height: 1.25;
      letter-spacing: -0.025em;
    }

    .role {
      margin: 6px 0 16px;
      font-weight: 800;
      color: #334155;
    }

    details {
      margin: 12px 0;
      border-radius: 18px;
      border: 1px solid rgba(37, 99, 235, 0.13);
      background: linear-gradient(180deg, #ffffff, #f8fbff);
      overflow: hidden;
    }

    summary {
      cursor: pointer;
      padding: 15px 18px;
      font-weight: 900;
      color: #26364f;
      list-style: none;
      display: flex;
      justify-content: space-between;
      gap: 18px;
      align-items: center;
    }

    summary::-webkit-details-marker { display: none; }
    summary::after {
      content: "+";
      flex: 0 0 auto;
      width: 28px;
      height: 28px;
      display: grid;
      place-items: center;
      border-radius: 50%;
      color: #fff;
      background: linear-gradient(135deg, var(--accent), var(--accent-2));
    }
    details[open] summary::after { content: "−"; }

    details ul, .clean-list {
      margin: 0;
      padding: 0 20px 18px 40px;
      color: #34445e;
    }

    details li, .clean-list li { margin: 8px 0; }

    .case-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .case-card {
      padding: 24px;
      border-radius: 24px;
      background:
        linear-gradient(180deg, rgba(255,255,255,.94), rgba(255,255,255,.86)),
        linear-gradient(135deg, rgba(37, 99, 235, .12), rgba(15, 118, 110, .10));
      border: 1px solid rgba(37, 99, 235, 0.14);
      box-shadow: var(--shadow-soft);
    }

    .case-card .label {
      display: inline-block;
      padding: 6px 10px;
      border-radius: 999px;
      background: rgba(15, 118, 110, .10);
      color: var(--accent-2);
      font-weight: 900;
      font-size: 13px;
      margin-bottom: 12px;
    }

    .case-card h3 { margin: 0 0 10px; font-size: 22px; line-height: 1.25; }
    .case-card p { margin: 0; color: #3e4c63; }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .tag {
      padding: 9px 12px;
      border-radius: 999px;
      background: #ffffff;
      border: 1px solid rgba(37, 99, 235, 0.14);
      color: #334155;
      font-weight: 800;
      box-shadow: 0 8px 16px rgba(31, 41, 55, 0.05);
    }

    .edu-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 18px;
    }

    .edu-card {
      padding: 22px;
      border-radius: 22px;
      background: #fff;
      border: 1px solid rgba(37, 99, 235, 0.12);
    }

    .edu-card h3 { margin: 0 0 8px; }
    .edu-card p { margin: 0; color: var(--muted); }

    .footer {
      margin: 30px 0 42px;
      padding: 22px;
      color: var(--muted);
      text-align: center;
    }

    @media (max-width: 920px) {
      .hero-grid,
      .experience-card,
      .skills-grid,
      .case-grid,
      .edu-grid {
        grid-template-columns: 1fr;
      }
      .photo-wrap { justify-self: start; max-width: 260px; }
      .stats { grid-template-columns: 1fr; }
      .hero { padding: 24px; border-radius: 26px; }
    }

    @media (max-width: 560px) {
      .page { width: min(100% - 22px, var(--max)); }
      .hero { margin-top: 14px; padding: 18px; }
      .contacts { flex-direction: column; }
      .contact-pill { width: 100%; justify-content: center; }
      .card, .experience-card { padding: 18px; }
      details ul, .clean-list { padding-left: 26px; }
      h1 { font-size: 44px; }
    }

    @media print {
      body { background: #fff; }
      .hero, .card, .experience-card, .case-card, .skill-card, .edu-card { box-shadow: none; }
      .nav { display: none; }
      details { break-inside: avoid; }
    }
  </style>
</head>
<body>
  <main class="page">
    <header class="hero">
      <div class="hero-grid">
        <div>
          <span class="eyebrow">Профессиональный опыт</span>
          <h1>Ирина Щербич</h1>
          <p class="subtitle">Налоговый менеджер, эксперт</p>
          <div class="contacts" aria-label="Контакты">
            <a class="contact-pill" href="tel:+79153391983">+7 915 339 1983</a>
            <a class="contact-pill" href="mailto:irina_msk_job@mail.ru">irina_msk_job@mail.ru</a>
          </div>
          <div class="stats" aria-label="Ключевые показатели опыта">
            <div class="stat-card"><strong>14+</strong><span>лет опыта налогового планирования и взаимодействия с налоговыми органами</span></div>
            <div class="stat-card"><strong>9+</strong><span>лет работы в бухгалтерском учете и прохождение аудиторских проверок</span></div>
            <div class="stat-card"><strong>11</strong><span>филиалов с функциональным подчинением специалистов</span></div>
          </div>
        </div>
        <figure class="photo-wrap">
          <img src="Foto.jpg" alt="Фото Ирины Щербич" />
        </figure>
      </div>
    </header>

    <nav class="nav" aria-label="Навигация по странице">
      <a href="#skills">Ключевые навыки</a>
      <a href="#experience">Опыт</a>
      <a href="#cases">Кейсы</a>
      <a href="#tools">Инструменты</a>
      <a href="#education">Образование</a>
    </nav>

    <section id="skills">
      <h2 class="section-title">Ключевые навыки</h2>
      <div class="skills-grid">
        <article class="skill-card">
          <h3>Налогообложение</h3>
          <p>Опыт налогового планирования, взаимодействия с налоговыми органами более 14 лет.</p>
        </article>
        <article class="skill-card">
          <h3>Бухучет</h3>
          <p>Более 9 лет работы, успешное прохождение аудиторских проверок.</p>
        </article>
        <article class="skill-card">
          <h3>Управление командой</h3>
          <p>Опыт руководства отделом, прямые подчиненные.</p>
        </article>
      </div>
    </section>

    <section id="experience">
      <h2 class="section-title">Профессиональный опыт</h2>
      <div class="timeline">
        <article class="experience-card">
          <div class="period">2013 — апрель 2026</div>
          <div>
            <h3 class="company">ООО «РН-Бурение», г. Москва</h3>
            <p class="role">ДО группы ПАО «НК «Роснефть»<br>И.о. начальника отдела / Главный специалист налогового отдела</p>
            <details open>
              <summary>Зоны ответственности</summary>
              <ul>
                <li>Осуществление подготовки и сдачи Уведомления о контролируемых сделках с «нуля» с 2013 года, создание ЛНД и документации по ТЦО, контроль соблюдения уровня рентабельности, формулирование рекомендаций по соблюдению рыночного уровня цен.</li>
                <li>Планирование налогов и страховых взносов в рамках бизнес-планирования, финансового планирования до 5 лет.</li>
                <li>Участие в Дью-дилидженс (Due Diligence) в сегменте Tax DD при присоединении обществ и создании филиалов.</li>
                <li>Контроль порядка и сроков уплаты налогов и сборов, в том числе в управляемых Обществах, в иностранных юрисдикциях.</li>
                <li>Сопровождение аудита бухгалтерской, финансовой, управленческой отчетности, участие в проектах по автоматизации процессов, инвентаризации.</li>
              </ul>
            </details>
            <details>
              <summary>Ключевые результаты</summary>
              <ul>
                <li><strong>2022–2026:</strong> и.о. начальника налогового отдела с решением кадровых вопросов по специалистам с функциональным подчинением в 11 филиалах.</li>
                <li>В 15 субъектах РФ по более 300 обособленных подразделений контролировала начисление, уплату налогов и сборов, сдачу отчетности, в том числе согласовывала подачу уточненных деклараций. Результат: отсутствие штрафов за несвоевременную подачу деклараций, непредставление документов и информации по требованиям / запросам налоговых органов, досудебное урегулирование претензий со стороны ОСФР.</li>
                <li>Осуществляла согласование договора с аудитором (SAP, Диадок), организовывала документооборот по запросам аудитора по защищенным каналам связи, включая консолидацию, проверку и предоставление документов и информации по 11 филиалам Общества, обеспечивала устранение замечаний аудитора. Результат — получение немодифицированного аудиторского заключения годовой бухгалтерской (финансовой) отчетности Общества.</li>
                <li><strong>2019–2021:</strong> выполняла работу по получению льготы по 12 филиалам в виде скидки к страховому тарифу на обязательное социальное страхование от несчастных случаев на производстве — ежегодная экономия более 3 млн руб.; по плану финансирования предупредительных мер в ФСС — ежегодная экономия более 10 млн руб.; контролировала сверку с ИФНС, ФСС, ПФР, своевременный возврат / зачет переплат из бюджета.</li>
                <li><strong>2013–2018:</strong> провела налоговое планирование при присоединении 7 Обществ (ООО и АО) и создании 4 филиалов в регионах РФ: ХМАО, Оренбургской области, республике Башкортостан.</li>
                <li>Контролировала сдачу отчетности и уплату налогов в 19 субъектах РФ.</li>
                <li>Успешно лидировала проекты от проведения тендерной закупки до использования ПО: Контур-реформатор для УКС, автоматизация в 1С сбора данных по налогам и сборам в аналитике корпоративного формуляра.</li>
                <li>Реализовала заявительный порядок возмещения НДС — порядка 2 млрд руб.</li>
              </ul>
            </details>
          </div>
        </article>

        <article class="experience-card">
          <div class="period">2009 — 2013</div>
          <div>
            <h3 class="company">ООО «Газпромнефть Бизнес-сервис», г. Ноябрьск</h3>
            <p class="role">ОЦО ПАО «Газпром нефть»<br>Начальник отдела по учету банковских операций и финансовых вложений</p>
            <details>
              <summary>Зоны ответственности и ключевые результаты</summary>
              <ul>
                <li>Координировала работу отдела — 11 человек в подчинении, внедряла принципы «бережливого производства».</li>
                <li>Решала методологические задачи, организовывала качественное ведение бухгалтерского учета по участкам учета: счета 50, 51, 52, 55, 57, 58, 59, 66, 67, 76, 75, 80, 82, 86.</li>
                <li>Обеспечивала проверку и согласование бухгалтерских документов обслуживаемых предприятий добычного блока — нефть, газ, нефтесервисного блока и прочих медиа, связь; обслуживание 16 ДЗО «ГПН».</li>
                <li>Осуществила методологическую оценку, ввод остатков при внедрении ПО SAP 6.0 в ОАО «ГПН-ННГ», ООО «ЗН».</li>
                <li>Осуществляла планирование налогов: налог на прибыль, НДС, НДПИ по видам ежемесячно, на 3 года, в разрезе МВЗ / статей затрат.</li>
                <li>Проводила оценку договоров / хозяйственных ситуаций на предмет налоговых рисков.</li>
                <li>Участвовала в проектах по лоббированию интересов Компании по минимизации налогов в региональной части через заключение социальных соглашений в целях получения скидок по налогу на прибыль, налогу на имущество (ЯНАО).</li>
                <li>Выполняла работу по подготовке отчетности: Уведомления о контролируемых сделках, 4-ФСС, по НДФЛ.</li>
              </ul>
            </details>
          </div>
        </article>

        <article class="experience-card">
          <div class="period">2004 — 2009</div>
          <div>
            <h3 class="company">ОАО «Газпромнефть-Ноябрьскнефтегаз»</h3>
            <p class="role">Ведущий бухгалтер</p>
            <details>
              <summary>Зоны ответственности</summary>
              <ul>
                <li>Ведение бухгалтерского учета по участкам учета: счета 01, 04, 50 (путевки), 60, 69, 76, 86, 97.</li>
                <li>Составление и сдача отчета по форме 4-ФСС.</li>
              </ul>
            </details>
          </div>
        </article>

        <article class="experience-card">
          <div class="period">2003 — 2004</div>
          <div>
            <h3 class="company">«Ноябрьский городской банк», г. Ноябрьск, ЯНАО</h3>
            <p class="role">Ведущий экономист</p>
          </div>
        </article>

        <article class="experience-card">
          <div class="period">2002 — 2003</div>
          <div>
            <h3 class="company">ООО «Аудиторская компания «Финансовое бюро», г. Уфа</h3>
            <p class="role">Ассистент аудитора</p>
          </div>
        </article>
      </div>
    </section>

    <section id="cases">
      <h2 class="section-title">Примеры кейсов</h2>
      <div class="case-grid">
        <article class="case-card">
          <span class="label">НДС</span>
          <h3>Заявительный порядок возмещения НДС</h3>
          <p>Реализовала заявительный порядок возмещения НДС — порядка 2 млрд руб.</p>
        </article>
        <article class="case-card">
          <span class="label">Аудит</span>
          <h3>Сопровождение аудита по 11 филиалам</h3>
          <p>Организовывала документооборот по запросам аудитора, консолидацию, проверку и предоставление документов и информации по 11 филиалам. Результат — немодифицированное аудиторское заключение.</p>
        </article>
        <article class="case-card">
          <span class="label">ФСС</span>
          <h3>Льгота и предупредительные меры</h3>
          <p>Получение льготы по 12 филиалам: ежегодная экономия более 3 млн руб.; по плану финансирования предупредительных мер в ФСС — ежегодная экономия более 10 млн руб.</p>
        </article>
        <article class="case-card">
          <span class="label">Реорганизация</span>
          <h3>Налоговое планирование при присоединениях</h3>
          <p>Провела налоговое планирование при присоединении 7 Обществ и создании 4 филиалов в регионах РФ: ХМАО, Оренбургская область, республика Башкортостан.</p>
        </article>
        <article class="case-card">
          <span class="label">Контроль</span>
          <h3>Отчетность и налоги в регионах</h3>
          <p>Контролировала сдачу отчетности и уплату налогов в 19 субъектах РФ; в 15 субъектах РФ по более 300 обособленных подразделений контролировала начисление, уплату налогов и сборов, сдачу отчетности.</p>
        </article>
        <article class="case-card">
          <span class="label">Автоматизация</span>
          <h3>ПО и корпоративная аналитика</h3>
          <p>Лидировала проекты от проведения тендерной закупки до использования ПО: Контур-реформатор для УКС, автоматизация в 1С сбора данных по налогам и сборам в аналитике корпоративного формуляра.</p>
        </article>
      </div>
    </section>

    <section id="tools">
      <h2 class="section-title">Инструменты и компетенции</h2>
      <div class="card">
        <div class="tags" aria-label="Инструменты">
          <span class="tag">SAP</span>
          <span class="tag">1С</span>
          <span class="tag">Контур Экстерн</span>
          <span class="tag">Диадок</span>
          <span class="tag">СБИС</span>
          <span class="tag">СЭД</span>
          <span class="tag">Личный кабинет налогоплательщика на сайте ФНС</span>
          <span class="tag">Консультант плюс</span>
          <span class="tag">Гарант</span>
          <span class="tag">chatgpt.com</span>
          <span class="tag">perplexity.ai</span>
          <span class="tag">claude.ai</span>
          <span class="tag">giga.chat</span>
          <span class="tag">5 S</span>
        </div>
      </div>
    </section>

    <section id="education">
      <h2 class="section-title">Образование</h2>
      <div class="edu-grid">
        <article class="edu-card">
          <h3>Финансы и кредит</h3>
          <p>Башкирский государственный университет, г. Уфа, 2003.</p>
        </article>
        <article class="edu-card">
          <h3>Консультант по налогам и сборам</h3>
          <p>Российский новый университет, г. Москва, 2019.</p>
        </article>
        <article class="edu-card">
          <h3>Курсы ДипИФР-Рус</h3>
          <p>2018.</p>
        </article>
        <article class="edu-card">
          <h3>Налоговый консультант Палаты налоговых консультантов</h3>
          <p>Сертификат №18417, 2019.</p>
        </article>
        <article class="edu-card">
          <h3>Мастер CFO (Финансовый директор)</h3>
          <p>Онлайн-программа профессиональной переподготовки, 2025–2026. Обучение продолжается.</p>
        </article>
        <article class="edu-card">
          <h3>Фокус обучения</h3>
          <p>Финансовое управление, бюджетирование, управленческая отчетность, финансовый контроль, финансовое моделирование, оценка эффективности бизнеса, стратегическая роль финансовой функции.</p>
        </article>
      </div>
    </section>

    <section id="additional">
      <h2 class="section-title">Другое</h2>
      <div class="card">
        <ul class="clean-list">
          <li>Компетенции в урегулировании налоговых споров, коммуникациях с налоговыми органами, оптимизации налоговой нагрузки в рамках действующего законодательства.</li>
          <li>Владение инструментами бережливого производства 5 S, системный подход к решению задач.</li>
          <li>Проведение презентаций / обучения сотрудников в целях повышения налоговой / финансовой грамотности, наставничество.</li>
        </ul>
      </div>
    </section>

    <footer class="footer">
      <p>Страница подготовлена на основе текста резюме. Для корректного отображения фото файл <strong>Foto.jpg</strong> должен находиться в одной папке с HTML-файлом.</p>
    </footer>
  </main>
</body>
</html>
