<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>CIAMDEG: Misión Data</title>
  <style>
    :root { --bg:#1a1a1a; --panel:#111827; --line:#374151; --text:#e5e7eb; --muted:#9ca3af; --blue:#3b82f6; --red:#ef4444; --gold:#fbbf24; --green:#34d399; }
    * { box-sizing:border-box; }
    body { margin:0; min-height:100vh; background:radial-gradient(circle at top, #262334 0%, var(--bg) 55%); color:var(--text); font-family:Consolas, Monaco, monospace; }
    button { font:inherit; cursor:pointer; }
    .app { width:min(1120px, calc(100% - 28px)); margin:0 auto; padding:26px 0 40px; }
    header { text-align:center; border-bottom:1px solid var(--line); margin-bottom:22px; padding-bottom:18px; }
    h1 { color:var(--gold); font-size:clamp(1.3rem, 4vw, 2.2rem); margin:0 0 8px; letter-spacing:.08em; }
    h2, h3, p { margin-top:0; } .subtitle { color:var(--muted); margin:0; }
    .screen { background:rgba(17,24,39,.92); border:1px solid var(--line); box-shadow:0 14px 45px #0008; padding:clamp(16px,4vw,28px); }
    .class-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:14px; }
    .class-card, .reward { color:var(--text); text-align:left; background:#0b101d; border:1px solid #4b5563; padding:16px; transition:.15s; }
    .class-card:hover, .reward:hover { transform:translateY(-2px); border-color:var(--gold); background:#151d2e; }
    .class-card h3 { color:var(--gold); margin-bottom:7px; } .class-card p { color:var(--muted); font-size:.84rem; line-height:1.45; }
    .class-title { display:flex; align-items:center; gap:11px; }
    .sprite { width:58px; height:70px; flex:0 0 auto; image-rendering:pixelated; filter:drop-shadow(3px 4px 0 #000a); }
    .class-card .sprite { width:43px; height:52px; }
    .sprite.attack-right { animation:attackRight .34s ease-in-out; } .sprite.attack-left { animation:attackLeft .34s ease-in-out; }
    .fighter.hit { animation:hit .26s linear; }
    @keyframes attackRight { 50% { transform:translateX(22px) scale(1.08); filter:drop-shadow(0 0 8px #93c5fd); } }
    @keyframes attackLeft { 50% { transform:translateX(-22px) scale(1.08); filter:drop-shadow(0 0 8px #fca5a5); } }
    @keyframes hit { 25%,75% { transform:translateX(-5px); background:#5b1d23; } 50% { transform:translateX(5px); } }
    .stats { color:#bfdbfe; font-size:.8rem; line-height:1.55; } .passive { color:#ddd6fe !important; }
    .stage-banner { text-align:center; color:var(--gold); font-size:1.05rem; margin-bottom:16px; }
    .combatants { display:grid; grid-template-columns:1fr 1fr; gap:16px; }
    .fighter { background:#0b101d; border:1px solid var(--line); padding:16px; min-width:0; }
    .fighter.player { border-color:var(--blue); } .fighter.enemy { border-color:var(--red); }
    .fighter h2 { font-size:1.05rem; margin-bottom:12px; } .fighter-title { display:flex; align-items:center; gap:12px; } .player h2 { color:var(--blue); } .enemy h2 { color:var(--red); }
    .bar { height:12px; background:#27272a; border:1px solid #4b5563; margin:10px 0 8px; }
    .fill { height:100%; transition:width .35s ease; } .player .fill { background:var(--blue); } .enemy .fill { background:var(--red); }
    .stamina-bar { height:7px; background:#27272a; border:1px solid #4b5563; margin:11px 0 5px; }
    .stamina-fill { height:100%; background:var(--gold); transition:width .35s ease; }
    .details { color:var(--muted); font-size:.82rem; line-height:1.65; }
    .console { background:#05070c; border:1px solid #4b5563; min-height:170px; max-height:270px; overflow:auto; margin:16px 0; padding:12px; font-size:.84rem; line-height:1.6; }
    .boss-dialogue { margin:16px 0; border-left:4px solid var(--red); background:#2a1117; color:#fecaca; padding:12px 15px; font-size:.9rem; line-height:1.55; }
    .boss-dialogue strong { color:var(--red); }
    .material-reveal { max-width:650px; margin:auto; text-align:center; }
    .material-sprite { width:150px; height:150px; image-rendering:pixelated; filter:drop-shadow(5px 7px 0 #0008); margin:8px auto 18px; display:block; }
    .material-description { color:#dbeafe; background:#0b172b; border:1px solid var(--blue); padding:14px; line-height:1.55; text-align:left; }
    .story-team { display:flex; justify-content:center; gap:8px; flex-wrap:wrap; margin:18px 0; padding:12px; background:#0b101d; border:1px solid var(--blue); }
    .story-team .sprite { width:40px; height:48px; }
    .story-dialogue { max-width:780px; margin:12px auto; padding:14px 18px; border-left:4px solid var(--gold); background:#241d0a; color:#fef3c7; line-height:1.6; }
    .log-player { color:#93c5fd; } .log-enemy { color:#fca5a5; } .log-system { color:#fcd34d; } .log-good { color:#6ee7b7; }
    .actions { display:flex; justify-content:center; gap:12px; flex-wrap:wrap; } .action { padding:12px 18px; border:1px solid var(--blue); background:#10234a; color:#dbeafe; }
    .action:hover:not(:disabled) { background:#19366f; } button:disabled { cursor:not-allowed; opacity:.45; }
    .special { border-color:var(--gold); background:#3a2b08; color:#fef3c7; } .special:hover:not(:disabled) { background:#5d450d; }
    .boss-tag { color:var(--gold); font-weight:bold; } .end { text-align:center; max-width:700px; margin:auto; } .end h2 { color:var(--gold); font-size:1.8rem; }
    .rewards { display:grid; grid-template-columns:repeat(3,1fr); gap:14px; } .reward { min-height:160px; } .reward h3 { color:var(--green); }
    .small { font-size:.78rem; color:var(--muted); }
    @media (max-width:650px) { .combatants, .rewards { grid-template-columns:1fr; } .app { width:min(100% - 18px,1120px); padding-top:14px; } }
  </style>
</head>
<body>
  <main class="app">
    <header><h1>CIAMDEG: MISIÓN DATA</h1><p class="subtitle">Roguelike estratégico · Convierte datos en decisiones.</p></header>
    <div id="juego"></div>
  </main>
  <script>
    'use strict';
    const CLASES = {
      'Caballero': { hp:60, atk:50, def:55, vel:40, tipo:'Fisico', pasiva:'Armadura Pesada', desc:'Reduce todo el daño recibido en un valor fijo de 4 puntos.' },
      'Pícaro': { hp:45, atk:65, def:35, vel:65, tipo:'Fisico', pasiva:'Instinto Asesino', desc:'15% de probabilidad de asestar golpe crítico (daño x1.5).' },
      'Arquero': { hp:40, atk:55, def:40, vel:60, tipo:'Fisico', pasiva:'Ojo de Halcón', desc:'Sus ataques tienen 100% de precisión (nunca falla).' },
      'Escudero': { hp:55, atk:45, def:60, vel:45, tipo:'Fisico', pasiva:'Fervor', desc:'Recupera 5 HP automáticamente al final de cada turno.' },
      'Paladín': { hp:55, atk:52, def:50, vel:42, tipo:'Mistico', pasiva:'Escudo Espejo', desc:'Devuelve automáticamente el 15% del daño recibido al atacante.' },
      'Nigromante': { hp:42, atk:60, def:38, vel:55, tipo:'Mistico', pasiva:'Almas en Pena', desc:'Reduce la velocidad del enemigo en un 15% al inicio del combate.' },
      'Clérigo Oscuro': { hp:48, atk:50, def:45, vel:48, tipo:'Mistico', pasiva:'Pacto de Sangre', desc:'Se cura el 20% del daño total infligido al rival.' },
      'Cazador de Brujas': { hp:44, atk:58, def:42, vel:58, tipo:'Mistico', pasiva:'Rastreador', desc:'+25% de probabilidad de crítico contra Jefes, Nigromantes y Clérigos.' }
    };
    const VENTAJAS = { 'Caballero':'Pícaro', 'Pícaro':'Arquero', 'Arquero':'Escudero', 'Escudero':'Caballero', 'Paladín':'Nigromante', 'Nigromante':'Clérigo Oscuro', 'Clérigo Oscuro':'Cazador de Brujas', 'Cazador de Brujas':'Paladín' };
    const DIALOGOS_JEFES = {
      'Verdugo Corpulento':'Las campanas no doblan por los vivos. Arrodíllate, intruso.',
      'Capitán Renegado':'Mi ejército murió… pero aún obedece mi espada.',
      'Caballero de Sangre':'He jurado proteger este castillo con cada gota que derrame.',
      'Rey Usurpador':'Has cruzado mi reino de cadáveres. Ahora serás parte de él.'
    };
    const DIALOGOS_CIAMDEG = {
      'Desorden Operativo':'Sin procesos claros, todo esfuerzo termina perdiéndose.',
      'Silos de Información':'Tus datos están dispersos. Nunca tendrás la visión completa.',
      'Decisión sin Indicadores':'¿Cómo dirigirás si no puedes medir lo que ocurre?',
      'Reto del Mercado':'El mercado cambia cada día. Demuestra que CIAMDEG puede anticiparse.'
    };
    const DIALOGOS_COMPETENCIA = {
      'Competencia del Desorden':'Sus procesos no necesitan orden si nadie puede demostrar que son mejores.',
      'Competencia de los Datos':'La información fragmentada es nuestra mejor aliada. No recuperarás ese material.',
      'Competencia de los Indicadores':'Sin medición no hay dirección. Tu cuadro de mando nunca estará completo.',
      'Competencia del Mercado':'Adaptarse no basta. Hoy pondremos a prueba el valor de tus productos.'
    };
    const ROLES_CIAMDEG = {
      'Caballero':'Analista Estratégico', 'Pícaro':'Especialista de Marketing', 'Arquero':'Gestor de Campañas', 'Escudero':'Gestor de Procesos',
      'Paladín':'Consultor de Business Intelligence', 'Nigromante':'Científico de Datos', 'Clérigo Oscuro':'Especialista CRM', 'Cazador de Brujas':'Auditor Digital'
    };
    const PASIVAS_CIAMDEG = {
      'Caballero':{nombre:'Gestión de Riesgos', desc:'Los controles operativos reducen en 4 el impacto de cada incidente.'},
      'Pícaro':{nombre:'Campaña de Alto Impacto', desc:'15% de probabilidad de lograr una acción crítica (daño x1.5).'},
      'Arquero':{nombre:'Segmentación Precisa', desc:'Sus acciones alcanzan el objetivo siempre: nunca fallan.'},
      'Escudero':{nombre:'Mejora Continua', desc:'Optimiza el proceso y recupera 5 HP al final de cada turno.'},
      'Paladín':{nombre:'Feedback 360', desc:'Devuelve automáticamente el 15% del impacto recibido al reto.'},
      'Nigromante':{nombre:'Integración de Datos', desc:'Reduce la velocidad del reto en 15% al iniciar el análisis.'},
      'Clérigo Oscuro':{nombre:'Fidelización CRM', desc:'Recupera el 20% del impacto total generado al rival.'},
      'Cazador de Brujas':{nombre:'Inteligencia Competitiva', desc:'+25% de crítico ante retos clave y perfiles de datos.'}
    };
    const ESPECIALES = {
      'Caballero':{nombre:'Embate del León', costo:6, clase:'daño', poder:82, tipo:'Fisico'},
      'Pícaro':{nombre:'Danza de Cuchillas', costo:6, clase:'daño', poder:88, tipo:'Fisico'},
      'Arquero':{nombre:'Flecha Perforante', costo:6, clase:'daño', poder:78, tipo:'Fisico', perforar:.35},
      'Escudero':{nombre:'Muralla Viva', costo:5, clase:'buff', defensa:16, turnos:2, tipo:'Fisico'},
      'Paladín':{nombre:'Juicio Radiante', costo:6, clase:'daño', poder:82, tipo:'Magico'},
      'Nigromante':{nombre:'Maleficio de Huesos', costo:6, clase:'daño', poder:84, tipo:'Magico'},
      'Clérigo Oscuro':{nombre:'Misa Carmesí', costo:5, clase:'buff', ataque:12, cura:12, turnos:2, tipo:'Magico'},
      'Cazador de Brujas':{nombre:'Bala de Plata', costo:6, clase:'daño', poder:86, tipo:'Magico'}
    };
    const ESPECIALES_ENEMIGOS = [
      {nombre:'Tajo Sombrío', costo:5, clase:'daño', poder:72, tipo:'Fisico'},
      {nombre:'Hexa de Ceniza', costo:6, clase:'daño', poder:76, tipo:'Magico'},
      {nombre:'Guardia Macabra', costo:5, clase:'buff', defensa:12, turnos:2, tipo:'Fisico'},
      {nombre:'Furia Profana', costo:5, clase:'buff', ataque:10, turnos:2, tipo:'Magico'}
    ];
    const STAGES = [
      { nombre:'Diagnóstico Empresarial', combates:2, jefe:'Competencia del Desorden', materialId:'wpc', material:'Listones WPC tipo madera', producto:'Revestimiento Elegancia' },
      { nombre:'Marketing y Big Data', combates:3, jefe:'Competencia de los Datos', materialId:'marmol', material:'Plancha PVC marmoleada', producto:'Muro Lujo Marmoleado' },
      { nombre:'Cuadro de Mando', combates:3, jefe:'Competencia de los Indicadores', materialId:'melamina', material:'Tablero de melamina', producto:'Anaqueles a la Medida' },
      { nombre:'Transformación CIAMDEG', combates:1, jefe:'Competencia del Mercado', materialId:'herrajes', material:'Kit de herrajes y bisagras', producto:'Puerta Funcional a Medida' }
    ];
    const DESCRIPCIONES_MATERIALES = {
      wpc:'Listones resistentes con acabado tipo madera. Son la base para crear revestimientos modernos y duraderos.',
      marmol:'Panel ligero de PVC con apariencia de mármol. Permite crear paredes elegantes, limpias y de fácil mantenimiento.',
      melamina:'Tablero versátil para cortes precisos. Se transforma en anaqueles funcionales adaptados a cada espacio.',
      herrajes:'Bisagras y fijaciones de calidad. Dan apertura suave, firmeza y seguridad a puertas hechas a medida.'
    };
    const DESCRIPCIONES_PRODUCTOS = {
      wpc:'Revestimiento decorativo con textura de madera, ideal para renovar paredes con estilo y resistencia.',
      marmol:'Pared marmoleada ligera y elegante que transforma cualquier ambiente en pocos pasos.',
      melamina:'Anaqueles personalizados que aprovechan el espacio y mantienen todo ordenado.',
      herrajes:'Puerta a medida con apertura suave y herrajes firmes para el uso diario.'
    };
    const $ = (selector) => document.querySelector(selector);
    const legible = (texto) => { try { return decodeURIComponent(escape(texto)); } catch { return texto; } };
    const pasivaCiamdeg = (nombre) => PASIVAS_CIAMDEG[legible(nombre)] || {nombre:'Capacidad CIAMDEG', desc:'Una habilidad estratégica del equipo.'};
    const juego = $('#juego');
    let estado = { jugador:null, etapa:0, ganados:0, enemigo:null, ocupado:false, transicion:false, materiales:[] };
    const esperar = (ms) => new Promise(resolve => setTimeout(resolve, ms));
    const azar = (min,max) => Math.floor(Math.random() * (max - min + 1)) + min;
    function sprite(nombre, enemigo=false) {
      const nombreVisual=legible(nombre);
      const diseños={
        'Caballero':['#2563eb','#e6c2a5','laptop','cap'], 'Pícaro':['#ec4899','#d8ad8e','megaphone','hood'],
        'Arquero':['#0f766e','#d9b78b','tablet','cap'], 'Escudero':['#475569','#d5c2a1','clipboard','cap'],
        'Paladín':['#ca8a04','#e7c6aa','dashboard','cap'], 'Nigromante':['#6d28d9','#d4c2b2','dataorb','hood'],
        'Clérigo Oscuro':['#be123c','#e1c6b7','crm','cap'], 'Cazador de Brujas':['#92400e','#e6c295','scanner','hat']
      };
      const d=diseños[nombreVisual] || (enemigo ? ['#7a2830','#d1b3a4','warning','helm'] : ['#4b5563','#e5d0bd','laptop','cap']);
      const [ropa,piel,arma,cabeza]=d;
      const extra={
        laptop:'<rect x="28" y="28" width="13" height="9" fill="#1e293b"/><rect x="30" y="29" width="9" height="5" fill="#60a5fa"/><rect x="27" y="37" width="16" height="2" fill="#94a3b8"/>',
        megaphone:'<path d="M28 27l12-5v12l-12-5z" fill="#f9a8d4"/><rect x="25" y="28" width="5" height="5" fill="#fce7f3"/>',
        tablet:'<rect x="29" y="25" width="10" height="14" rx="1" fill="#172554"/><rect x="31" y="27" width="6" height="8" fill="#5eead4"/><path d="M32 34l2-3 2 1" stroke="#0f766e" stroke-width="1"/>',
        clipboard:'<rect x="29" y="24" width="10" height="15" fill="#d6d3d1"/><rect x="32" y="22" width="4" height="3" fill="#60a5fa"/><path d="M31 29h6M31 32h6M31 35h4" stroke="#475569" stroke-width="1"/>',
        dashboard:'<rect x="28" y="24" width="13" height="14" fill="#172554"/><rect x="30" y="26" width="2" height="8" fill="#fbbf24"/><rect x="34" y="29" width="2" height="5" fill="#34d399"/><rect x="38" y="27" width="2" height="7" fill="#60a5fa"/>',
        dataorb:'<rect x="34" y="18" width="2" height="26" fill="#a78bfa"/><rect x="30" y="13" width="10" height="10" fill="#8b5cf6"/><rect x="33" y="16" width="4" height="4" fill="#ddd6fe"/>',
        crm:'<rect x="28" y="25" width="13" height="12" fill="#4c0519"/><circle cx="32" cy="30" r="2" fill="#fda4af"/><circle cx="37" cy="30" r="2" fill="#fda4af"/><path d="M31 34h7" stroke="#fda4af" stroke-width="1"/>',
        scanner:'<rect x="30" y="26" width="10" height="10" fill="#1f2937"/><rect x="32" y="28" width="6" height="4" fill="#fbbf24"/><path d="M28 38l5-4" stroke="#fbbf24" stroke-width="2"/>',
        warning:'<path d="M35 20l7 15H28z" fill="#f59e0b"/><rect x="34" y="25" width="2" height="5" fill="#451a03"/><rect x="34" y="32" width="2" height="2" fill="#451a03"/>'
      }[arma] || '';
      const cubre=cabeza==='hood' ? `<path d="M14 9q6-8 13 0v10H14z" fill="${ropa}"/>` : cabeza==='hat' ? `<path d="M12 11h18l-5-7h-8z" fill="#372820"/><rect x="9" y="11" width="22" height="3" fill="#8e6138"/>` : cabeza==='helm' ? `<path d="M14 8h13v11H14z" fill="#9ba5ad"/><path d="M13 13h15" stroke="#39434b" stroke-width="2"/>` : '';
      return `<svg class="sprite" viewBox="0 0 44 52" aria-hidden="true"><rect x="17" y="10" width="8" height="9" fill="${piel}"/>${cubre}<rect x="13" y="19" width="16" height="16" fill="${ropa}"/><rect x="11" y="23" width="4" height="12" fill="${ropa}"/><rect x="28" y="23" width="4" height="12" fill="${ropa}"/><rect x="15" y="35" width="5" height="12" fill="${ropa}"/><rect x="23" y="35" width="5" height="12" fill="${ropa}"/><rect x="14" y="46" width="7" height="3" fill="#1a1a1a"/><rect x="22" y="46" width="7" height="3" fill="#1a1a1a"/>${extra}</svg>`;
    }
    function spriteMaterial(id) {
      const artes={
        wpc:'<rect x="22" y="18" width="12" height="70" fill="#8b5a2b"/><rect x="40" y="18" width="12" height="70" fill="#a66d36"/><rect x="58" y="18" width="12" height="70" fill="#7c4a22"/><path d="M25 30h6m-6 15h6m12-15h6m-6 15h6m12-15h6m-6 15h6" stroke="#d6a66d" stroke-width="2"/>',
        marmol:'<rect x="20" y="20" width="60" height="66" fill="#e5e7eb"/><path d="M23 34q15-14 27 2t27-5M23 61q16-17 28-2t26-8" fill="none" stroke="#a78b7b" stroke-width="4"/><path d="M27 25l42 55" stroke="#cbd5e1" stroke-width="3"/>',
        melamina:'<rect x="18" y="25" width="64" height="14" fill="#b98a60"/><rect x="18" y="47" width="64" height="14" fill="#9b704c"/><rect x="18" y="69" width="64" height="14" fill="#b98a60"/><rect x="20" y="20" width="5" height="68" fill="#70452e"/><rect x="75" y="20" width="5" height="68" fill="#70452e"/>',
        herrajes:'<rect x="28" y="22" width="18" height="58" fill="#94a3b8"/><rect x="54" y="22" width="18" height="58" fill="#cbd5e1"/><circle cx="37" cy="33" r="3" fill="#334155"/><circle cx="37" cy="68" r="3" fill="#334155"/><circle cx="63" cy="33" r="3" fill="#334155"/><circle cx="63" cy="68" r="3" fill="#334155"/>'
      };
      return `<svg class="material-sprite" viewBox="0 0 100 105" aria-hidden="true"><rect x="10" y="10" width="80" height="85" fill="#111827" stroke="#3b82f6" stroke-width="4"/>${artes[id] || artes.wpc}</svg>`;
    }
    function spriteProducto(id) {
      const artes={
        wpc:'<rect x="18" y="18" width="64" height="70" fill="#334155"/><path d="M28 20v66M40 20v66M52 20v66M64 20v66M76 20v66" stroke="#b77942" stroke-width="8"/><rect x="35" y="42" width="30" height="20" fill="#dbeafe" stroke="#fbbf24" stroke-width="3"/>',
        marmol:'<rect x="17" y="18" width="66" height="70" fill="#f1f5f9"/><path d="M20 35q17-17 30 1t30-6M19 65q20-17 33-1t27-8" fill="none" stroke="#a78b7b" stroke-width="4"/><rect x="17" y="18" width="66" height="70" fill="none" stroke="#7c4a22" stroke-width="5"/>',
        melamina:'<rect x="20" y="20" width="60" height="68" fill="#a66d36"/><rect x="25" y="28" width="50" height="8" fill="#ead6b8"/><rect x="25" y="48" width="50" height="8" fill="#ead6b8"/><rect x="25" y="68" width="50" height="8" fill="#ead6b8"/>',
        herrajes:'<rect x="27" y="18" width="46" height="70" fill="#9b704c"/><path d="M50 18v70" stroke="#334155" stroke-width="4"/><rect x="44" y="49" width="12" height="5" fill="#fbbf24"/>'
      };
      return `<svg class="material-sprite" viewBox="0 0 100 105" aria-hidden="true"><rect x="10" y="10" width="80" height="85" fill="#111827" stroke="#34d399" stroke-width="4"/>${artes[id] || artes.wpc}</svg>`;
    }
    class Personaje {
      constructor(nombre, datos, nivel=1, jefe=false) {
        this.nombre=nombre; this.datos={...datos}; this.nivel=nivel; this.jefe=jefe;
        const m=jefe ? 1.4 : 1;
        this.maxHp=Math.round(datos.hp*m); this.hp=this.maxHp; this.atk=Math.round(datos.atk*m); this.def=Math.round(datos.def*m); this.mdef=Math.round((datos.mdef || datos.def)*m); this.vel=Math.round(datos.vel*m);
        this.maxStamina=10; this.stamina=this.maxStamina; this.especiales=datos.especiales || (ESPECIALES[legible(nombre)] ? [ESPECIALES[legible(nombre)]] : []); this.buffAtaque=0; this.buffDefensa=0; this.buffTurnos=0;
      }
      subirNivel(cantidad=1) { for(let i=0;i<cantidad;i++) { this.nivel++; this.maxHp+=6; this.atk+=4; this.def+=3; this.mdef+=3; this.vel+=2; } this.hp=Math.min(this.maxHp, this.hp+cantidad*6); }
      calcularDanio(objetivo, potencia=48, tipo='Fisico', perforar=0) {
        const defensaBase=tipo==='Magico' ? objetivo.mdef : objetivo.def;
        const defensa=Math.max(1,defensaBase+objetivo.buffDefensa*(1-perforar));
        let dano=(((2*this.nivel/5)+2)*potencia*((this.atk+this.buffAtaque)/defensa))/50+2;
        if(VENTAJAS[this.nombre]===objetivo.nombre) dano*=1.5;
        if(VENTAJAS[objetivo.nombre]===this.nombre) dano*=.7;
        let critico=false;
        if(legible(this.nombre)==='Pícaro' && Math.random()<.15) critico=true;
        if(legible(this.nombre)==='Cazador de Brujas' && (objetivo.jefe || legible(objetivo.nombre)==='Nigromante' || legible(objetivo.nombre)==='Clérigo Oscuro') && Math.random()<.25) critico=true;
        if(critico) dano*=1.5;
        return { dano:Math.max(1,Math.round(dano)), critico };
      }
    }
    function crearEnemigo(jefe=false) {
      const stage=STAGES[estado.etapa];
      if(jefe) { const base={ hp:50+estado.etapa*12, atk:52+estado.etapa*7, def:43+estado.etapa*6, mdef:48+estado.etapa*6, vel:42+estado.etapa*4, tipo:'Jefe', danoBase:'Magico', pasiva:'Furia del Trono', desc:'Una voluntad que no conoce piedad.', especiales:[ESPECIALES_ENEMIGOS[1],ESPECIALES_ENEMIGOS[3]] }; return new Personaje(stage.jefe,base,estado.jugador.nivel+estado.etapa,jefe); }
      const nombres=['Hater de Datos','Hater de Procesos','Competencia de Marketing','Hater de Indicadores','Competencia de Reportes'];
      const base={ hp:36+estado.etapa*9, atk:42+estado.etapa*6, def:34+estado.etapa*5, mdef:38+estado.etapa*5, vel:36+estado.etapa*4, tipo:'Reto', danoBase:estado.etapa%2===0?'Fisico':'Magico', pasiva:'—', desc:'Una barrera que requiere análisis y acción.', especiales:[ESPECIALES_ENEMIGOS[0],ESPECIALES_ENEMIGOS[2]] };
      return new Personaje(nombres[azar(0,nombres.length-1)],base,Math.max(1,estado.jugador.nivel+estado.etapa-1));
    }
    function renderHistoria() {
      juego.innerHTML='';
      const equipo=Object.keys(CLASES).map(nombre=>sprite(nombre)).join('');
      const pantalla=document.createElement('section');
      pantalla.className='screen end';
      pantalla.innerHTML=`
        <p class="stage-banner">INICIO DE MISIÓN · CIAMDEG</p>
        <h2>La campaña que no pudo esperar</h2>
        <div class="story-team">${equipo}</div>
        <div class="story-dialogue"><strong>Equipo CIAMDEG:</strong> El equipo se reúne para planear la próxima campaña: nuevos revestimientos, paneles, anaqueles y puertas a medida.</div>
        <div class="story-dialogue"><strong>Jefe de Operaciones:</strong> “Atención. La Competencia ha robado los materiales que necesitamos para terminar nuestros productos. Debemos recuperarlos antes de que la campaña se detenga.”</div>
        <div class="story-dialogue"><strong>Jefe de Operaciones:</strong> “Solo una persona liderará esta misión. Elige con cuidado: cada perfil tiene una capacidad distinta para superar los retos.”</div>
        <button class="action" id="continuar-historia" type="button">CONTINUAR</button>`;
      juego.append(pantalla);
      $('#continuar-historia').onclick=renderSeleccion;
    }
    function renderSeleccion() {
      juego.innerHTML='';
      const pantalla=document.createElement('section'); pantalla.className='screen';
      pantalla.innerHTML='<h2>Elige tu perfil de transformación</h2><p class="subtitle">Cada perfil aporta una fortaleza. Supera cuatro retos de gestión y demuestra el potencial de los datos para CIAMDEG.</p><div class="class-grid" id="clases"></div>';
      juego.append(pantalla); const lista=$('#clases');
      Object.entries(CLASES).forEach(([nombre,d])=>{ const b=document.createElement('button'); const pasiva=pasivaCiamdeg(nombre); b.className='class-card'; b.innerHTML=`<div class="class-title">${sprite(nombre)}<div><h3>${ROLES_CIAMDEG[legible(nombre)] || 'Perfil CIAMDEG'}</h3><p>${legible(nombre)} · ${d.tipo}</p></div></div><div class="stats">HP ${d.hp} · ATQ ${d.atk} · DEF ${d.def} · VEL ${d.vel}</div><p class="passive">${pasiva.nombre}: ${pasiva.desc}</p>`; b.addEventListener('click',()=>iniciar(nombre)); lista.append(b); });
    }
    function iniciar(nombre) { estado={ jugador:new Personaje(nombre,CLASES[nombre]), etapa:0, ganados:0, enemigo:null, ocupado:false, transicion:false, materiales:[] }; prepararCombate(false); }
    function prepararCombate(esJefe) { estado.transicion=false; estado.enemigo=crearEnemigo(esJefe); if(legible(estado.jugador.nombre)==='Nigromante') estado.enemigo.vel=Math.max(1,Math.round(estado.enemigo.vel*.85)); renderCombate(esJefe); agregarLog(esJefe ? `¡Reto crítico: ${estado.enemigo.nombre}!` : `${estado.enemigo.nombre} requiere tu atención.`, 'system'); if(legible(estado.jugador.nombre)==='Nigromante') agregarLog('Integración de Datos ralentiza al reto.', 'good'); }
    function ficha(p, lado) { const hp=Math.max(0,Math.round(p.hp)); const extra=p.jefe ? '<span class="boss-tag">JEFE</span>' : p.datos.tipo; const buff=p.buffTurnos>0 ? `<br><span class="boss-tag">BUFF ${p.buffTurnos}T</span>` : ''; const titulo=lado==='player' ? (ROLES_CIAMDEG[legible(p.nombre)] || 'Perfil CIAMDEG') : p.nombre; const subtitulo=lado==='player' ? `${legible(p.nombre)} · ${extra}` : extra; const pasiva=lado==='player' ? pasivaCiamdeg(p.nombre).nombre : p.datos.pasiva; return `<article class="fighter ${lado}"><div class="fighter-title">${sprite(p.nombre,lado==='enemy')}<h2>${titulo} · ${subtitulo}</h2></div><div class="bar"><div class="fill" style="width:${Math.max(0,p.hp/p.maxHp*100)}%"></div></div><strong>${hp} / ${p.maxHp} HP</strong><div class="stamina-bar"><div class="stamina-fill" style="width:${p.stamina/p.maxStamina*100}%"></div></div><div class="details">EST ${p.stamina} / ${p.maxStamina}<br>Nv. ${p.nivel}<br>ATQ ${p.atk} · DEF F ${p.def} · DEF M ${p.mdef} · VEL ${p.vel}${buff}<br>${pasiva}</div></article>`; }
    function actualizarBotones() { const especial=$('#especial'); if(especial) { const habilidad=estado.jugador.especiales[0]; especial.disabled=estado.ocupado || estado.jugador.stamina<habilidad.costo; especial.textContent=`✦ ${habilidad.nombre.toUpperCase()} (${habilidad.costo} EST)`; } }
    function renderCombate(esJefe) { const dialogo=esJefe ? `<aside class="boss-dialogue"><strong>${estado.enemigo.nombre}:</strong> “${DIALOGOS_COMPETENCIA[estado.enemigo.nombre] || 'Analiza el reto y toma una decisión.'}”</aside>` : ''; juego.innerHTML=`<section class="screen"><div class="stage-banner">[ ${STAGES[estado.etapa].nombre.toUpperCase()} ] · ${esJefe?'RETO CLAVE':'Reto '+(estado.ganados+1)+'/'+STAGES[estado.etapa].combates} · Materiales: ${estado.materiales.length}/${STAGES.length}</div><div class="combatants">${ficha(estado.jugador,'player')}${ficha(estado.enemigo,'enemy')}</div>${dialogo}<div class="console" id="consola" aria-live="polite"></div><div class="actions"><button class="action" id="atacar" type="button">⚔ ACCIÓN BASE</button><button class="action special" id="especial" type="button"></button></div><p class="small" style="text-align:center;margin:14px 0 0">Acción base: +3 EST. Daño físico usa DEF F; daño mágico usa DEF M.</p></section>`; $('#atacar').onclick=()=>turno(false); $('#especial').onclick=()=>turno(true); actualizarBotones(); }
    function agregarLog(texto,tipo='system') { const c=$('#consola'); if(!c) return; const l=document.createElement('div'); l.className='log-'+tipo; l.textContent='> '+texto; c.append(l); c.scrollTop=c.scrollHeight; }
    function animarAtaque(atacante, objetivo) {
      const esJugador=atacante===estado.jugador;
      const spriteAtacante=$(`.${esJugador?'player':'enemy'} .sprite`);
      const fichaObjetivo=$(`.${objetivo===estado.jugador?'player':'enemy'}`);
      if(spriteAtacante) { const clase=esJugador?'attack-right':'attack-left'; spriteAtacante.classList.remove(clase); void spriteAtacante.offsetWidth; spriteAtacante.classList.add(clase); }
      if(fichaObjetivo) { fichaObjetivo.classList.remove('hit'); void fichaObjetivo.offsetWidth; fichaObjetivo.classList.add('hit'); }
    }
    function refrescarFichas() { const consoleHTML=$('#consola')?.innerHTML || ''; const panel=$('.screen'); if(!panel) return; const combatants=$('.combatants'); combatants.innerHTML=ficha(estado.jugador,'player')+ficha(estado.enemigo,'enemy'); $('#consola').innerHTML=consoleHTML; actualizarBotones(); }
    function elegirEspecialEnemigo(enemigo) { const disponibles=enemigo.especiales.filter(e=>enemigo.stamina>=e.costo); return disponibles.length && Math.random()<.55 ? disponibles[azar(0,disponibles.length-1)] : null; }
    async function turno(usaraEspecial=false) {
      if(estado.ocupado) return;
      const especialJugador=usaraEspecial ? estado.jugador.especiales[0] : null;
      if(especialJugador && estado.jugador.stamina<especialJugador.costo) return;
      estado.ocupado=true;
      const boton=$('#atacar'); if(boton) boton.disabled=true;
      const botonEspecial=$('#especial'); if(botonEspecial) botonEspecial.disabled=true;
      try {
        const orden=estado.jugador.vel>=estado.enemigo.vel ? [estado.jugador,estado.enemigo] : [estado.enemigo,estado.jugador];
        for(const atacante of orden) { const objetivo=atacante===estado.jugador?estado.enemigo:estado.jugador; const especial=atacante===estado.jugador ? especialJugador : elegirEspecialEnemigo(atacante); if(atacante.hp<=0 || objetivo.hp<=0) continue; await accion(atacante,objetivo,especial); if(atacante.hp<=0 || objetivo.hp<=0) break; await esperar(420); }
        if(estado.jugador.hp<=0) { gameOver(); return; }
        if(estado.enemigo.hp<=0) { victoriaCombate(); return; }
        aplicarFinalTurno(); refrescarFichas();
        if(estado.jugador.hp<=0) { gameOver(); return; }
      } catch(error) {
        console.error(error);
        agregarLog('La acción fue interrumpida. Puedes volver a atacar.', 'system');
      } finally {
        estado.ocupado=false;
        const siguienteBoton=$('#atacar'); if(siguienteBoton && !estado.transicion) siguienteBoton.disabled=false;
        actualizarBotones();
      }
    }
    async function accion(atacante,objetivo,especial=null) {
      animarAtaque(atacante,objetivo); await esperar(260);
      if(especial && especial.clase==='buff') {
        atacante.stamina-=especial.costo; atacante.buffAtaque=Math.max(atacante.buffAtaque,especial.ataque || 0); atacante.buffDefensa=Math.max(atacante.buffDefensa,especial.defensa || 0); atacante.buffTurnos=Math.max(atacante.buffTurnos,especial.turnos || 1);
        if(especial.cura) atacante.hp=Math.min(atacante.maxHp,atacante.hp+especial.cura);
        agregarLog(`${atacante.nombre} usa ${especial.nombre}: recibe un buff${especial.cura?` y recupera ${especial.cura} HP`:''}.`, atacante===estado.jugador?'player':'enemy'); refrescarFichas(); return;
      }
      let falla=atacante.nombre!=='Arquero' && Math.random()<.10;
      if(falla) { agregarLog(`${atacante.nombre} falla su ataque.`, atacante===estado.jugador?'player':'enemy'); if(!especial) atacante.stamina=Math.min(atacante.maxStamina,atacante.stamina+3); refrescarFichas(); return; }
      if(especial) atacante.stamina-=especial.costo;
      const tipo=especial?.tipo || atacante.datos.danoBase || (atacante.datos.tipo==='Mistico' ? 'Magico' : 'Fisico');
      const golpe=atacante.calcularDanio(objetivo,especial?.poder || 48,tipo,especial?.perforar || 0); let dano=golpe.dano;
      if(legible(objetivo.nombre)==='Caballero') dano=Math.max(1,dano-4);
      objetivo.hp=Math.max(0,objetivo.hp-dano);
      agregarLog(`${atacante.nombre}${especial?` usa ${especial.nombre}`:' ataca'}: ${dano} de daño ${tipo==='Magico'?'mágico':'físico'} a ${objetivo.nombre}${golpe.critico?' — ¡CRÍTICO!':''}.`, atacante===estado.jugador?'player':'enemy');
      if(!especial) { atacante.stamina=Math.min(atacante.maxStamina,atacante.stamina+3); agregarLog(`${atacante.nombre} recupera 3 EST con el golpe base.`, 'good'); }
      if(legible(atacante.nombre)==='Clérigo Oscuro') { const cura=Math.max(1,Math.round(dano*.2)); atacante.hp=Math.min(atacante.maxHp,atacante.hp+cura); agregarLog(`Fidelización CRM recupera ${cura} HP.`, 'good'); }
      if(legible(objetivo.nombre)==='Paladín' && dano>0) { const rebote=Math.max(1,Math.round(dano*.15)); atacante.hp=Math.max(0,atacante.hp-rebote); agregarLog(`Feedback 360 devuelve ${rebote} de impacto.`, 'enemy'); }
      refrescarFichas();
    }
    function aplicarFinalTurno() { [estado.jugador,estado.enemigo].forEach(p=>{ if(p.buffTurnos>0) { p.buffTurnos--; if(p.buffTurnos===0) { p.buffAtaque=0; p.buffDefensa=0; agregarLog(`El buff de ${p.nombre} se desvanece.`, 'system'); } } }); if(legible(estado.jugador.nombre)==='Escudero' && estado.jugador.hp>0) { const antes=estado.jugador.hp; estado.jugador.hp=Math.min(estado.jugador.maxHp,estado.jugador.hp+5); if(estado.jugador.hp>antes) agregarLog(`Mejora Continua recupera ${estado.jugador.hp-antes} HP.`, 'good'); } }
    function victoriaCombate() { estado.transicion=true; const jefe=estado.enemigo.jefe; agregarLog(`${estado.enemigo.nombre} ha sido superado.`, 'good'); if(!jefe) { estado.ganados++; estado.jugador.subirNivel(1); setTimeout(()=> estado.ganados>=STAGES[estado.etapa].combates ? prepararCombate(true) : prepararCombate(false), 900); return; } const zona=STAGES[estado.etapa]; const recuperado={id:zona.materialId,material:zona.material,producto:zona.producto}; estado.materiales.push(recuperado); agregarLog(`Material recuperado: ${zona.material}. Es esencial para ${zona.producto}.`, 'good'); setTimeout(()=> mostrarMaterialRecuperado(recuperado),1000); }
    function mostrarMaterialRecuperado(recuperado) { juego.innerHTML=`<section class="screen material-reveal"><p class="stage-banner">MATERIA PRIMA ${estado.materiales.length} DE ${STAGES.length} RECUPERADA</p>${spriteMaterial(recuperado.id)}<h2>${recuperado.material}</h2><h3>Lista para crear: ${recuperado.producto}</h3><p class="material-description">${DESCRIPCIONES_MATERIALES[recuperado.id]}</p><button class="action special" id="convertir-material">✦ CONVERTIR EN PRODUCTO</button></section>`; $('#convertir-material').onclick=()=>mostrarProductoCreado(recuperado); }
    function mostrarProductoCreado(recuperado) { recuperado.convertido=true; const esFinal=estado.etapa===STAGES.length-1; juego.innerHTML=`<section class="screen material-reveal"><p class="stage-banner">PRODUCTO TERMINADO</p>${spriteProducto(recuperado.id)}<h2>${recuperado.producto}</h2><p class="material-description">${DESCRIPCIONES_PRODUCTOS[recuperado.id]}</p><button class="action" id="continuar-producto">${esFinal?'VER RESULTADO DE LA MISIÓN':'ELEGIR MEJORA'}</button></section>`; $('#continuar-producto').onclick=()=> esFinal ? pantallaFinal(true) : menuRecompensa(); }
    function menuRecompensa() { juego.innerHTML=''; const opciones=[ {t:'Optimización de Recursos',d:'Recupera el 100% de capacidad y aumenta tu HP máximo en +10.',a:()=>{estado.jugador.maxHp+=10;estado.jugador.hp=estado.jugador.maxHp;}}, {t:'Capacitación Estratégica',d:'Aumenta tu capacidad de acción permanentemente en +7 ATQ.',a:()=>estado.jugador.atk+=7}, {t:'Inteligencia de Negocio',d:'Sube 2 niveles y mejora tus indicadores.',a:()=>estado.jugador.subirNivel(2)} ]; const s=document.createElement('section'); s.className='screen end'; s.innerHTML='<h2>Hito alcanzado</h2><p>Selecciona una mejora para afrontar el siguiente reto de CIAMDEG.</p><div class="rewards" id="recompensas"></div>'; juego.append(s); const c=$('#recompensas'); opciones.sort(()=>Math.random()-.5).forEach(o=>{const b=document.createElement('button');b.className='reward';b.innerHTML=`<h3>${o.t}</h3><p>${o.d}</p>`;b.addEventListener('click',()=>{o.a();estado.etapa++;estado.ganados=0;prepararCombate(false);});c.append(b);}); }
    function gameOver() { pantallaFinal(false); }
    function pantallaFinal(victoria) { const inventario=estado.materiales.map(x=>`<li>${x.material} · ${x.producto}</li>`).join(''); juego.innerHTML=`<section class="screen end"><h2>${victoria?'¡MISIÓN COMPLETADA!':'RETO NO SUPERADO'}</h2><p>${victoria?'CIAMDEG recuperó los materiales de sus productos y transforma datos, indicadores y estrategia en decisiones que generan valor.':'Revisa los indicadores, refuerza tu estrategia y vuelve a intentarlo.'}</p>${victoria?`<h3>Materiales recuperados</h3><ul style="text-align:left;display:inline-block">${inventario}</ul>`:''}<button class="action" id="reiniciar">↻ NUEVA MISIÓN</button></section>`; $('#reiniciar').addEventListener('click',renderHistoria); }
    renderHistoria();
  </script>
</body>
</html>
