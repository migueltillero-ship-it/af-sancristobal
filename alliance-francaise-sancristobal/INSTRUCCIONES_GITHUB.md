# 🚀 GUÍA DE IMPLEMENTACIÓN EN GITHUB

## Alliance Française de San Cristóbal de Las Casas

---

## 📁 ESTRUCTURA DE TU REPOSITORIO

Tu repositorio en GitHub debe verse así:

```
tu-repositorio/
├── index.html          ← El archivo que te proporcioné
└── images/             ← Carpeta con todas las imágenes
    ├── 2.png
    ├── 3.png
    ├── 4.png
    ├── Alejandro_AVENDA_æO.png
    ├── Allison_Chau.jpg
    ├── CAVILAM_Viaje_linguistico.jpg
    ├── CAvilam_firma.jpg
    ├── Club_de_conversation.png
    ├── Con_Cl__mence_Mayoral.jpg
    ├── Con_la_Directora_de_la_Salle.jpg
    ├── DELF.jpg
    ├── Director_1.jpg
    ├── Director_2.jpg
    ├── Director__coordinadora_del_centro_de_lenguas_unicach_consul_honorario.jpg
    ├── Director_con_la_presidenta_de_la_FIPF.jpg
    ├── Director_san_cristobal_con_director_Cavilam.jpg
    ├── Director_y_Michel_BOIRON.jpg
    ├── Entrada_de_la_AF.jpg
    ├── FEI_delf_logO.jpg
    ├── Fachada_externa_de_noche.jpg
    ├── Logo_AF_c__rculo_ROJO.png
    ├── Presidenta_en_la_casa_de_la_embajadora.jpg
    ├── Tour_de_Cine_Franc__s.jpg
    ├── Tour_de_Cine_Franc__s1.jpg
    ├── UNICACH_Y_C__nsul_honorario.jpg
    ├── aulas_1.jpg
    ├── aulas_2.jpg
    ├── aulas_3.jpg
    ├── cavilam_firma_de_acuerdo.jpg
    ├── entrada.jpg
    ├── entrega_DELF.jpg
    ├── entrega_DELF1.jpg
    ├── estudiantes_de_gastronomia_Parmentier.jpg
    ├── evento_gastronomia_con_parmentier.jpg
    ├── fachada.png
    ├── foto_huerto.jpg
    ├── huerto.jpg
    ├── huerto_riego.jpg
    ├── huertos_en_la_entrada.jpg
    ├── jardin.jpg
    ├── mediateca.jpg
    ├── mediateca2.jpg
    ├── parmentier_conociendo_el_huerto.jpg
    ├── presidenta_aF_con_Embajadora_FR.jpg
    └── visita_de_la_D__l__gation_du_qu__bec.png
```

---

## 📋 PASOS PARA IMPLEMENTAR

### Paso 1: Crear la carpeta `images`
En tu repositorio de GitHub, crea una carpeta llamada `images`

### Paso 2: Subir las imágenes
Sube TODAS las imágenes a la carpeta `images/`

### Paso 3: Subir el index.html
Copia el contenido del `index.html` y pégalo en tu archivo index.html en GitHub

### Paso 4: Verificar
Abre tu sitio y verifica que todas las imágenes carguen correctamente

---

## ⚠️ IMÁGENES USADAS EN EL SITIO

Estas son las imágenes que SÍ se usan en el código HTML:

| Sección | Archivo |
|---------|---------|
| Hero (fondo) | `Fachada_externa_de_noche.jpg` |
| Logo header | `Logo_AF_c__rculo_ROJO.png` |
| Nosotros | `huertos_en_la_entrada.jpg` |
| Instalaciones | `aulas_1.jpg` |
| Instalaciones | `mediateca.jpg` |
| Instalaciones | `jardin.jpg` |
| Instalaciones | `foto_huerto.jpg` |
| Instalaciones | `fachada.png` |
| Instalaciones | `Entrada_de_la_AF.jpg` |
| Alianzas | `cavilam_firma_de_acuerdo.jpg` |
| Alianzas | `estudiantes_de_gastronomia_Parmentier.jpg` |
| Alianzas | `Con_la_Directora_de_la_Salle.jpg` |
| Alianzas | `aulas_3.jpg` |
| Alianzas | `UNICACH_Y_C__nsul_honorario.jpg` |
| Alianzas | `DELF.jpg` |
| Reconocimientos | `Director_y_Michel_BOIRON.jpg` |
| Reconocimientos | `Director_con_la_presidenta_de_la_FIPF.jpg` |
| Reconocimientos | `Presidenta_en_la_casa_de_la_embajadora.jpg` |
| Reconocimientos | `Con_Cl__mence_Mayoral.jpg` |
| Reconocimientos | `visita_de_la_D__l__gation_du_qu__bec.png` |
| Reconocimientos | `Tour_de_Cine_Franc__s1.jpg` |
| Equipo | `2.png` (Miguel) |
| Equipo | `3.png` (Nancy) |
| Equipo | `4.png` (Cayro) |
| Equipo | `Allison_Chau.jpg` |
| Footer | `Logo_AF_c__rculo_ROJO.png` |

**Total: 25 imágenes usadas**

---

## 🔧 SI LAS IMÁGENES NO CARGAN

### Problema común: Los nombres de archivo tienen caracteres especiales

Los archivos con caracteres especiales como `__` o `æ` pueden causar problemas.

**Solución:** Renombra los archivos problemáticos y actualiza el HTML:

| Nombre actual | Nombre sugerido |
|---------------|-----------------|
| `Logo_AF_c__rculo_ROJO.png` | `Logo_AF_circulo_ROJO.png` |
| `Con_Cl__mence_Mayoral.jpg` | `Con_Clemence_Mayoral.jpg` |
| `UNICACH_Y_C__nsul_honorario.jpg` | `UNICACH_Y_Consul_honorario.jpg` |
| `Tour_de_Cine_Franc__s.jpg` | `Tour_de_Cine_Frances.jpg` |
| `Tour_de_Cine_Franc__s1.jpg` | `Tour_de_Cine_Frances1.jpg` |
| `visita_de_la_D__l__gation_du_qu__bec.png` | `visita_de_la_Delegation_du_quebec.png` |
| `Alejandro_AVENDA_æO.png` | `Alejandro_AVENDANO.png` |

---

## ✅ VERIFICACIÓN FINAL

Después de subir todo, verifica que:

- [ ] El logo aparece en el header
- [ ] El logo aparece en el footer
- [ ] La imagen de fondo del hero se ve
- [ ] Las 6 imágenes de instalaciones cargan
- [ ] Las 6 imágenes de alianzas cargan
- [ ] Las 6 imágenes de reconocimientos cargan
- [ ] Las 4 fotos del equipo cargan
- [ ] El mapa de Google Maps funciona
- [ ] El botón de WhatsApp funciona
- [ ] Los enlaces de redes sociales funcionan
- [ ] El sitio es responsive (se ve bien en móvil)

---

## 📧 INFORMACIÓN DE CONTACTO INCLUIDA

### Correos (NUEVOS - confirmados):
- administracionsancristobal@alianzafr.edu.mx (Nancy)
- comunicacionsancristobal@alianzafr.edu.mx (Cayro)
- direccionsancristobal@alianzafr.edu.mx (Miguel)

### Canales oficiales:
- Facebook: facebook.com/alianzafrancesasancristobal
- Instagram: instagram.com/afdesancristobal
- Messenger: m.me/alianzafrancesasancristobal
- WhatsApp: 967 172 1870

### Datos bancarios:
- ALIANZA FRANCO MEXICANA DE SAN CRISTÓBAL A.C.
- BBVA
- Cuenta: 0186832806
- CLABE: 012130001868328069

---

## 🎉 ¡LISTO!

Tu sitio está completo y profesional. Solo sube los archivos a GitHub y activa GitHub Pages.

Para activar GitHub Pages:
1. Ve a Settings de tu repositorio
2. Busca "Pages" en el menú lateral
3. En "Source" selecciona tu rama (main o master)
4. Guarda y espera unos minutos
5. Tu sitio estará en: https://tu-usuario.github.io/tu-repositorio/
