# index.html
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Margareth Sofía Silva Montaña</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-light: #ffffff;
            --text-dark: #212529; /* Darker Charcoal for more intensity */
            --text-medium: #495057;
            --accent-color: #8D4C85; /* Deeper Orchid/Plum for intensity */
            --accent-light-color: #F6F2F8; /* Pale Lavender */
            --border-color: #dee2e6;
        }

        body {
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: var(--text-dark);
            font-family: 'Inter', sans-serif;
            -webkit-print-color-adjust: exact;
            print-color-adjust: exact;
        }

        .container {
            max-width: 1200px; /* Wider layout */
            margin: 25px auto;
            background-color: var(--bg-light);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            border-top: none;
        }
        
        .header-gradient {
            height: 8px;
            background: linear-gradient(90deg, #8D4C85, #C574B9);
        }

        .header {
            padding: 30px 40px;
            text-align: left;
        }

        .header h1 {
            margin: 0;
            font-size: 2.5em;
            font-weight: 700;
            color: var(--text-dark);
        }

        .header h2 {
            margin: 5px 0 15px;
            font-size: 1.3em;
            font-weight: 400;
            color: var(--accent-color);
        }

        .contact-bar {
            display: flex;
            gap: 25px;
            flex-wrap: wrap;
            font-size: 0.9em;
            color: var(--text-medium);
            padding-top: 10px;
            border-top: 1px solid var(--border-color);
        }
        
        .contact-item {
            display: flex;
            align-items: center;
        }

        .contact-item svg {
            fill: var(--accent-color);
            min-width: 18px;
            width: 18px;
            margin-right: 10px;
        }

        .section {
            padding: 20px 40px;
        }

        .grid-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }

        .section-title {
            font-size: 1.3em;
            font-weight: 600;
            color: var(--accent-color);
            margin-top: 0;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
        }
        
        .section-title::before {
            content: '';
            width: 4px;
            height: 20px;
            background-color: var(--accent-color);
            margin-right: 12px;
            border-radius: 2px;
        }
        
        .profile p, .pertinence-section p, .job-description {
            font-size: 1em;
            line-height: 1.7;
            color: var(--text-medium);
        }

        .pertinence-section {
            background-color: var(--accent-light-color);
            border-left: 4px solid var(--accent-color);
            padding: 25px;
            border-radius: 4px;
            height: 100%;
            box-sizing: border-box;
        }
        .pertinence-section h3 {
            color: var(--accent-color);
            margin-top: 0;
            font-size: 1.2em;
        }
        .pertinence-section strong {
            font-weight: 600;
            color: var(--accent-color);
        }

        .skills-list {
            list-style: none;
            padding: 0;
            font-size: 1em;
        }
        .skills-list li {
            margin-bottom: 12px;
            color: var(--text-medium);
            display: flex;
            align-items: flex-start;
        }
        .skills-list li::before {
            content: '›';
            color: var(--accent-color);
            font-weight: 700;
            margin-right: 10px;
            font-size: 1.2em;
            line-height: 1.1;
        }
        
        .job {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid var(--border-color);
        }
        .job:last-child {
            border-bottom: none;
            padding-bottom: 0;
        }

        .job-company {
            font-size: 1.15em;
            font-weight: 700;
            color: var(--text-dark);
            margin: 0;
        }
        .job-title {
            font-size: 1em;
            font-weight: 500;
            color: var(--text-medium);
            margin: 2px 0;
        }
        .job-period {
            font-size: 0.9em;
            color: #718096;
            margin-bottom: 12px;
            font-weight: 500;
        }

        .education-item {
            margin-bottom: 20px;
        }
        .degree {
            font-size: 1.1em;
            font-weight: 600;
            color: var(--text-dark);
            margin: 0;
        }
        .institution {
            font-size: 1em;
            color: var(--text-medium);
            margin: 2px 0;
        }

        @media print {
            body { background-color: #fff; }
            .container { box-shadow: none; border-top: none; width: 100%; max-width: 100%; }
            .header-gradient { background: linear-gradient(90deg, #8D4C85, #C574B9); -webkit-print-color-adjust: exact; print-color-adjust: exact;}
        }

    </style>
</head>
<body>

    <div class="container">
        <div class="header-gradient"></div>
        <header class="header">
            <h1>MARGARETH SOFÍA SILVA MONTAÑA</h1>
            <h2>Abogada | Alta Gerente Pública | Experta en Modernización del Estado</h2>
            <div class="contact-bar">
                <div class="contact-item">
                    <svg viewBox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
                    <span>+57 312 401 5972</span>
                </div>
                <div class="contact-item">
                    <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
                    <span>margarethsilvam@gmail.com</span>
                </div>
                <div class="contact-item">
                    <svg viewBox="0 0 24 24"><path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-7 4a3 3 0 0 0-3 3v5h2v-5a1 1 0 0 1 1-1s1 0 1 1v5h2v-5a3 3 0 0 0-3-3m-4 8v2h2v-2H8m8 0v2h2v-2h-2z" /></svg>
                    <span>linkedin.com/in/margarethsilvam</span>
                </div>
            </div>
        </header>

        <section class="section grid-section">
            <div class="profile">
                <h3 class="section-title">Perfil Directivo</h3>
                <p>
                    Abogada y Magíster con más de 20 años de experiencia ejerciendo la <strong>dirección estratégica</strong> de entidades complejas del Estado. Mi carrera se distingue por liderar transformaciones integrales, con competencias probadas en la <strong>gestión de crisis presupuestal</strong>, la <strong>formulación de políticas públicas</strong> y el <strong>diseño organizacional</strong> para la modernización del sector público.
                </p>
            </div>
            <div class="pertinence-section">
                <h3>Propuesta de Valor para la Administración Judicial</h3>
                <p>
                    Mi trayectoria en la alta gerencia pública me ha permitido liderar transformaciones integrales en los frentes que hoy son críticos para la Rama Judicial: la <strong>ejecución presupuestal, el diseño organizacional y la implementación de tecnologías avanzadas</strong>.
                </p>
                <p>
                    Aporto, por tanto, no solo una visión para la modernización, sino la <strong>experiencia directiva probada</strong> para gobernar la complejidad, administrar los recursos con eficiencia y ejecutar los planes de transformación que la justicia requiere.
                </p>
            </div>
        </section>

        <section class="section grid-section">
            <div>
                <h3 class="section-title">Competencias Estratégicas</h3>
                <ul class="skills-list">
                    <li>Dirección y Gerencia Estratégica</li>
                    <li>Alta Gerencia Financiera y Presupuestal</li>
                    <li>Formulación de Políticas Públicas y Normatividad</li>
                    <li>Diseño y Transformación Organizacional</li>
                    <li>Implementación de Tecnología e IA en la Gestión Pública</li>
                    <li>Gobernanza Corporativa y Liderazgo de Equipos</li>
                    <li>Contratación Estatal de Alta Complejidad</li>
                </ul>
            </div>
            <div>
                <h3 class="section-title">Formación Académica</h3>
                <div class="education-item">
                    <p class="degree">Magíster en Gobierno y Políticas Públicas</p>
                    <p class="institution">Universidad Externado de Colombia</p>
                </div>
                <div class="education-item">
                    <p class="degree">Especialización en Derecho Contractual</p>
                    <p class="institution">Universidad Externado de Colombia</p>
                </div>
                 <div class="education-item">
                    <p class="degree">Especialización en Derecho Procesal</p>
                    <p class="institution">Universidad Nacional de Colombia</p>
                </div>
                <div class="education-item">
                    <p class="degree">Especialización en Derecho Constitucional</p>
                    <p class="institution">Universidad Nuestra Señora del Rosario</p>
                </div>
                <div class="education-item">
                    <p class="degree">Abogada</p>
                    <p class="institution">Universidad Nacional de Colombia</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h3 class="section-title">Trayectoria de Liderazgo Estratégico</h3>
            
            <div class="job">
                <p class="job-company">Ministerio de Justicia y del Derecho</p>
                <p class="job-title">Directora Jurídica</p>
                <p class="job-period">2025 - Actualidad</p>
                <p class="job-description">Ejerzo la dirección estratégica en la <strong>formulación de políticas públicas y normatividad</strong> del sector. Actualmente estoy liderando la implementación de herramientas de automatización e <strong>Inteligencia Artificial</strong> para acelerar procesos de cobro coactivo.</p>
            </div>
            <div class="job">
                <p class="job-company">Instituto Nacional de Vías - INVIAS</p>
                <p class="job-title">Secretaria General</p>
                <p class="job-period">2023 - 2025</p>
                <p class="job-description">Asumí la dirección estratégica de la entidad durante una crisis de déficit presupuestal. Lideré la <strong>planeación y ejecución presupuestal</strong>, incluyendo el trámite de <strong>empréstitos</strong> y el diseño de estrategias para optimizar el flujo de caja. Mi gestión resultó en una <strong>reducción sustancial del déficit</strong>, permitiendo superar momentos críticos de cesación de pagos sin efectos adversos. Paralelamente, lideré la transformación cultural que culminó con la obtención del Sello 'Equipares' y finalicé en tiempo récord el concurso de méritos que vinculó a más de 300 funcionarios de carrera.</p>
            </div>
            <div class="job">
                 <p class="job-company">Ministerio de Tecnologías de la Información y las Comunicaciones</p>
                <p class="job-title">Jefe de la Oficina de Fomento Regional de las TIC</p>
                <p class="job-period">2022 - 2023</p>
                <p class="job-description">Articulé la política nacional de TIC en los territorios, asesorando a gobernaciones y alcaldías en la <strong>formulación de planes regionales</strong> para cerrar la brecha digital. Mi labor se centró en fortalecer la institucionalidad local y gestionar alianzas para la cofinanciación de proyectos, sentando las bases para la <strong>implementación de sistemas tecnológicos</strong> que garantizaran el acceso de todos los ciudadanos a servicios digitales, incluyendo la justicia, con un enfoque diferencial para comunidades estratégicas.</p>
            </div>
             <div class="job">
                 <p class="job-company">ICETEX</p>
                <p class="job-title">Secretaria General</p>
                <p class="job-period">2020 - 2022</p>
                <p class="job-description">Lideré el estudio técnico para la transformación de la <strong>arquitectura organizacional</strong> de la entidad, propuesta aprobada por la Junta Directiva y validada por DAFP y MinHacienda. Impulsé la <strong>estructuración de procedimientos</strong> clave, modernizando la gestión de contratación, la función disciplinaria y el sistema documental con la <strong>implementación de tecnología</strong> (Orfeo). Lideré la transformación del talento humano, implementando la política de teletrabajo y actualizando la OPEC para la provisión de más de 100 cargos por mérito.</p>
            </div>
            <div class="job">
                 <p class="job-company">Ministerio de Defensa Nacional</p>
                <p class="job-title">Directora de Contratación Estatal</p>
                <p class="job-period">2018 - 2020</p>
                <p class="job-description">Ejercí la <strong>dirección estratégica</strong> de la contratación del sector, un componente clave de la <strong>ejecución presupuestal</strong>. Lideré una reorganización interna y actualicé la política de contratación (Directiva 12/2020), generando ahorros significativos en compras estratégicas y promoviendo la contratación centralizada vía Acuerdos Marco de gran escala. Gestioné alianzas estratégicas con el sector minero-energético que representaron aportes multimillonarios.</p>
            </div>
            <div class="job">
                <p class="job-company">Ministerio de Tecnologías de la Información y las Comunicaciones</p>
                <p class="job-title">Directora de Vigilancia y Control / Jefe Oficina Jurídica</p>
                <p class="job-period">2015 - 2018</p>
                <p class="job-description">Dirigí la defensa jurídica del Ministerio y, desde la Dirección de Vigilancia y Control, lideré la creación e implementación de <strong>PrevenTIC</strong>, una innovadora <strong>política pública</strong> (Res. 3160 de 2017) diseñada para transformar el modelo de supervisión tradicional hacia uno preventivo, fomentando la cultura del cumplimiento normativo en el sector. Esta iniciativa fue clave en la <strong>formulación de normatividad</strong> y políticas para la expansión de la infraestructura tecnológica nacional.</p>
            </div>
            <div class="job">
                <p class="job-company">Defensoría del Pueblo</p>
                <p class="job-title">Jefe de Oficina Jurídica</p>
                <p class="job-period">2014 - 2015</p>
                <p class="job-description">Dirigí la estrategia de defensa jurídica de la entidad, <strong>estructurando procedimientos</strong> para la defensa de los derechos humanos ante el sistema judicial y coordinando la representación de la entidad.</p>
            </div>
        </section>

    </div>

</body>
</html>

