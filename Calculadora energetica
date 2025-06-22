`index.html`
``html
<!DOCTYPE html>
<html lang="es">
<cabeza>
  <meta charset="UTF-8" />
  <meta name="viewport" content="ancho=ancho-del-dispositivo, escala-inicial=1" />
  <title>Calculadora Energética y Macronutrientes</title>
  <estilo>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');

    * {
      tamaño de caja: caja de borde;
    }
    cuerpo {
      familia de fuentes: 'Inter', sans-serif;
      fondo: gradiente lineal (135 grados, #d8d9ff, #f5e9fa);
      margen: 0;
      relleno: 2rem 1rem;
      pantalla: flex;
      justificar-contenido: centro;
      altura mínima: 100vh;
      color: #194d33;
    }
    .contenedor {
      ancho máximo: 480px;
      ancho: 100%;
      fondo: #fff;
      radio del borde: 12px;
      caja-sombra: 0 8px 20px rgb(0 0 0 / 0.12);
      relleno: 2rem 2.5rem 3rem;
      desbordamiento: automático;
    }
    h1 {
      peso de la fuente: 700;
      alinear texto: centro;
      margen inferior: 1.5rem;
      tamaño de fuente: 1.8rem;
      color: #1a3e3d;
    }
    etiqueta {
      peso de la fuente: 600;
      margen inferior: 0,25rem;
      pantalla: bloque;
      color: #222;
    }
    entrada[tipo="número"], seleccione {
      ancho: 100%;
      relleno: 0.5rem 1rem;
      radio del borde: 12px;
      borde: 1,5 px sólido #ddd;
      tamaño de fuente: 1.1rem;
      color: #333;
      margen inferior: 1.3rem;
      transición: facilidad de color del borde 0,3 s;
      fondo: gradiente lineal (a la derecha, #f2f0ff, #e8dff5);
    }
    entrada[tipo="número"]:enfoque, seleccionar:enfoque {
      contorno: ninguno;
      color del borde: #7854f7;
      fondo: #faf7ff;
    }
    botón {
      ancho: 100%;
      fondo: gradiente lineal (90 grados, #00af91, #8547f4);
      borde: ninguno;
      relleno: 0.8rem 0;
      radio del borde: 20px;
      color: #fff;
      peso de la fuente: 700;
      tamaño de fuente: 1.1rem;
      cursor: puntero;
      transición: fondo 0,3 s facilidad;
      pantalla: flex;
      alinear-elementos: centro;
      justificar-contenido: centro;
      brecha: 0,5rem;
      selección de usuario: ninguno;
    }
    botón:hover {
      fondo: gradiente lineal (90 grados, #008f71, #662fcf);
    }
    .cuadro de resultados {
      margen superior: 2rem;
      fondo: #d5f0e0;
      borde: 2px sólido #3ea170;
      radio del borde: 10px;
      relleno: 1.5rem 1.8rem;
      color: #134d3e;
      alinear texto: centro;
      caja-sombra: inserción 0 2px 12px rgb(0 0 0 / 0.04);
    }
    .result-box h2 {
      peso de la fuente: 700;
      margen inferior: 0.5rem;
      tamaño de fuente: 1.6rem;
    }
    .result-box p {
      tamaño de fuente: 0.95rem;
      ancho máximo: 100%;
      margen: 0 auto;
      altura de línea: 1.3;
    }

    /* Barras calóricas coloreadas */
    .barras-caloricas {
      margen superior: 2rem;
      pantalla: flex;
      justificar-contenido: espacio-entre;
      brecha: 1rem;
    }
    .bar {
      flexión: 1;
      color: #fff;
      radio del borde: 12px;
      relleno: 1rem 0.7rem;
      pantalla: flex;
      flexión-dirección: columna;
      alinear-elementos: centro;
      peso de la fuente: 700;
      alinear texto: centro;
      selección de usuario: ninguno;
      caja-sombra: 0 8px 15px rgb(0 0 0 / 0.1);
      tamaño de fuente: 0.9rem;
      altura de línea: 1.2;
      ancho mínimo: 70px;
      ancho máximo: 90px;
      cursor: predeterminado;
    }
    .bar .icono {
      tamaño de fuente: 1.6rem;
      margen inferior: 0.3rem;
    }
    .bar p {
      peso de la fuente: 700;
      tamaño de fuente: 1.4rem;
      margen: 0.3rem 0;
    }
    .bar span {
      peso de la fuente: 400;
      tamaño de fuente: 0.8rem;
    }
    .bar.basale {
      fondo: gradiente lineal (135 grados, #3a7bd5, #00d2ff);
      caja-sombra: 0 8px 14px #2990d0aa;
    }
    .bar.actividad {
      fondo: gradiente lineal (135 grados, #00c853, #5dfc36);
      caja-sombra: 0 8px 14px #27af3faa;
    }
    .bar.termo {
      fondo: gradiente lineal (135 grados, #ff6600, #ff9a00);
      caja-sombra: 0 8px 14px #d35700aa;
    }
    .bar.ejercicio {
      fondo: gradiente lineal (135 grados, #d50061, #ff4081);
      caja-sombra: 0 8px 14px #b30053aa;
    }

    /*Recomendación Peso*/
    .recomendación {
      margen superior: 2rem;
      radio del borde: 12px;
      relleno: 1.5rem 2rem;
      peso de la fuente: 600;
      pantalla: flex;
      brecha: 1rem;
      alinear-elementos: centro;
      tamaño de fuente: 1rem;
      caja-sombra: inserción 0 0 14px rgb(0 0 0 / 0.07);
    }
    .recomendacion.perdida-de-peso {
      fondo: #fce6e6;
      borde: 2px sólido #e44c4c;
      color: #8b1616;
      justificar-contenido: espacio-entre;
    }
    .recomendacion.perdida-de-peso ul {
      relleno-izquierdo: 1rem;
      margen: 0;
      tipo-de-estilo-de-lista: ninguno;
      peso de la fuente: 400;
      tamaño de fuente: 0.9rem;
      altura de línea: 1.3;
    }
    .recomendación.pérdida de peso ul li {
      margen inferior: 0,55rem;
      relleno izquierdo: 1.8rem;
      posición: relativa;
      color: #a43030;
    }
    .recomendacion.perdida-de-peso ul li::antes {
      contenido: "âœ”ï¸ ";
      posición: absoluta;
      izquierda: 0;
      arriba: 0;
    }
    .recomendación.pérdida-de-peso ul li:last-child::before {
      contenido: "â Œ";
    }
    .recomendacion.perdida-de-peso img {
      altura máxima: 90px;
      altura: 80px;
      ancho:auto;
      objeto-apto: contener;
      selección de usuario: ninguno;
    }

    /* Recomendación Masa Muscular */
    .recomendación.ganancia-muscular {
      fondo: #dbf1db;
      borde: 2px sólido #3da65e;
      color: #2f5b23;
      margen superior: 1rem;
      justificar-contenido: centro;
      flex-wrap: envolver;
    }
    .recomendación.ganancia-muscular ul {
      relleno-izquierdo: 1rem;
      margen: 0;
      tipo-de-estilo-de-lista: ninguno;
      peso de la fuente: 400;
      tamaño de fuente: 0.9rem;
      altura de línea: 1.3;
      flexión: 1 1 65%;
    }
    .recomendación.ganancia muscular ul li {
      margen inferior: 0,55rem;
      relleno izquierdo: 1.6rem;
      posición: relativa;
      color: #2a6a27;
    }
    .recomendación.ganancia-muscular ul li::antes {
      contenido: "ðŸ' ";
      posición: absoluta;
      izquierda: 0;
      arriba: 0;
    }
    .recomendación.ganancia-muscular p {
      flexión: 1 1 30%;
      peso de la fuente: 600;
      tamaño de fuente: 1.8rem;
      margen izquierdo: 1rem;
      selección de usuario: ninguno;
    }

    /* Distribución Macronutrientes */
    .macro-contenedor {
      margen superior: 2.5rem;
      fondo: #fff;
      radio del borde: 12px;
      caja-sombra: 0 6px 20px rgb(0 0 0 / 0.06);
      relleno: 1.8rem 2.2rem 2.2rem;
      color: #222;
    }
    .macro-contenedor h3 {
      margen superior: 0;
      margen inferior: 0.8rem;
      peso de la fuente: 700;
      tamaño de fuente: 1.3rem;
      color: #1a2d3d;
    }
    .macro-contenedor p.descripción {
      tamaño de fuente: 0.9rem;
      color: #555;
      margen inferior: 1.4rem;
    }
    etiqueta .macro-contenedor {
      peso de la fuente: 600;
      pantalla: bloque;
      margen inferior: 0.4rem;
    }
    .macro-contenedor seleccionar {
      relleno: 0,5rem 0,75rem;
      radio del borde: 12px;
      borde: 1,5 px sólido #ccc;
      tamaño de fuente: 1rem;
      ancho: 100%;
      margen inferior: 1rem;
      fondo: #fefefe;
      transición: facilidad de color del borde 0,3 s;
    }
    .macro-contenedor seleccionar:enfoque {
      contorno: ninguno;
      color del borde: #664cff;
    }
    Botón contenedor de macros {
      ancho: 100%;
      relleno: 0,65rem 0;
      radio del borde: 18px;
      peso de la fuente: 700;
      tamaño de fuente: 1.1rem;
      cursor: puntero;
      fondo: gradiente lineal (90 grados, #2a5bff, #a245f7);
      color: blanco;
      borde: ninguno;
      transición: fondo 0,3 s facilidad;
      selección de usuario: ninguno;
      margen inferior: 1.3rem;
    }
    .macro-contenedor botón:hover {
      fondo: gradiente lineal (90 grados, #1e3aab, #6d2db4);
    }
    .macro-resultado {
      radio del borde: 12px;
      relleno: 1rem 1rem 1.5rem;
      peso de la fuente: 600;
      tamaño de fuente: 1rem;
      color: #722;
      fondo: #fce6e6;
      borde: 2px sólido #e44c4c;
      caja-sombra: inserción 0 0 10px rgb(0 0 0 / 0.05);
      selección de usuario: ninguno;
    }
    .macro-resultado fuerte {
      tamaño de fuente: 1.4rem;
      color: #b93030;
    }
    .macronutrientes {
      pantalla: flex;
      brecha: 1rem;
      margen superior: 1rem;
      margen inferior: 1rem;
    }
    .nutrient-box {
      flexión: 1;
      relleno: 1rem 1rem;
      radio del borde: 12px;
      pantalla: flex;
      flexión-dirección: columna;
      alinear-elementos: centro;
      caja-sombra: 1px 1px 8px rgb(0 0 0 / 0.05);
      peso de la fuente: 700;
      tamaño de fuente: 1.1rem;
      cursor: predeterminado;
      selección de usuario: ninguno;
      ancho mínimo: 70px;
    }
    .nutrient-box fuerte {
      tamaño de fuente: 1.4rem;
      margen inferior: 0.1rem;
    }
    .nutrient-box span {
      peso de la fuente: 400;
      tamaño de fuente: 0.9rem;
    }
    .nutrient-box.protein {
      fondo: #d1dafb;
      borde: 2px sólido #576fd8;
      color: #2d3e8f;
    }
    .nutrient-box.carbs {
      fondo: #ddf0e0;
      borde: 2px sólido #4cb349;
      color: #2d623a;
    }
    .nutrient-box.fat {
      fondo: #fff4d4;
      borde: 2px sólido #c8a154;
      color: #72602a;
    }
    .macro-recomendaciones {
      peso de la fuente: 500;
      tamaño de fuente: 0.9rem;
      margen superior: 0.8rem;
      color: #722;
      altura de línea: 1.3;
      altura máxima: 160px;
      desbordamiento-y: automático;
      relleno-derecho: 8px;
    }
    .macro-recomendaciones li {
      margen inferior: 0.4rem;
    }
    .macro-recomendaciones li::marker {
      color: #b93030;
      peso de la fuente: 700;
    }

    /*Responsivo*/
    @media (ancho máximo: 520px) {
      .barras-caloricas {
        flexión-dirección: columna;
        brecha: 0,8rem;
      }
      .bar {
        ancho máximo: 100%;
        tamaño de fuente: 0.85rem;
        flexión-dirección: fila;
        justificar-contenido: inicio-flexible;
        espacio: 8px;
        relleno: 1rem 1rem;
        ancho mínimo: automático;
      }
      .bar p {
        tamaño de fuente: 1.2rem;
      }
      .bar .icono {
        tamaño de fuente: 1.4rem;
        margen inferior: 0;
        margen derecho: 0.6rem;
      }
      .recomendación.ganancia-muscular {
        flexión-dirección: columna;
        tamaño de fuente: 0.95rem;
      }
      .recomendación.ganancia-muscular p {
        margen izquierdo: 0;
        margen superior: 0.8rem;
      }
      .macronutrientes {
        flexión-dirección: columna;
      }
      .nutrient-box {
        ancho: 100%;
      }
    }

  </estilo>
</cabeza>
<cuerpo>
  <main class="container" role="main" aria-label="Calculadora calórica y distribución de macronutrientes">
    <h1>Calculadora Energética y Macronutrientes</h1>

    <form id="energyForm" aria-describedby="descForm">
      <div id="descForm" style="display:none;">Formulario para ingreso de datos personales y nivel de actividad para calcular el consumo calórico.</div>
      
      <label for="age">Edad</label>
      <input type="number" id="age" name="age" min="10" max="120" value="26" required aria-required="true" />

      <label for="weight">Peso (kg)</label>
      <input type="number" id="weight" name="weight" min="20" max="300" value="80" step="0.1" required />

      <label for="height">Altura (cm)</label>
      <input type="number" id="height" name="height" min="100" max="250" value="169" required />

      <label for="gender">Género</label>
      <select id="género" name="género" requerido>
        <option value="male" selected>Masculino</option>
        <option value="female">Femenino</option>
      </seleccionar>

      <label for="actividad">Nivel de Actividad</label>
      <select id="actividad" nombre="actividad" requerido>
        <option value="1.2">Sedentaria (poco o ningún ejercicio)</option>
        <option value="1.375">Ligera (ejercicio ligero 1-3 días/sem)</option>
        <option value="1.55" selected>Moderada (ejercicio moderado-intenso 3-5 días/sem)</option>
        <option value="1.725">Alta (ejercicio intenso 6-7 días/sem)</option>
        <option value="1.9">Muy alta (ejercicio intenso diario + trabajo físico)</option>
      </seleccionar>

      <button type="submit" aria-label="Calcular consumo energético diario">ðŸš€ Calculadora</button>
    </form>

    <section id="resultSection" aria-live="polite" tabindex="-1" style="display:none;">
      <article class="result-box" id="energyResult" role="region" aria-label="Resultado consumo energético diario estimado">
        <h2><span aria-hidden="true">ðŸŽ¯</span> Tu consumo energético diario estimado es:</h2>
        <p><strong id="totalCalories">0</strong> calorías</p>
        <p>Este es un estimado basado en la ecuación de Harris-Benedict y tu nivel de actividad física.</p>
      </article>

      <div class="calorías-bars" aria-label="Desglose de consumo calórico estimado">
        <div class="bar basale" aria-label="Metabolismo basal">
          <div class="icono" aria-hidden="verdadero
```
