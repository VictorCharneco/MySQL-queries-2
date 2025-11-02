# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 21 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.53 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor,id_grado, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,9 +1,13 @@
 nombre
-Informática
+Matemáticas
 Matemáticas
 Economía y Empresa
+Economía y Empresa
+Educación
+Educación
 Educación
 Agronomía
+Química y Física
 Química y Física
 Filología
 Derecho
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | tipo | total_creditos
+grau | tipus | total_creditos
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_grado

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,6 @@
 anyo_inicio | total
 2014.00 | 3.00
+2015.00 | 0.00
+2016.00 | 0.00
+2017.00 | 0.00
 2018.00 | 3.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_curso_escolar

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -2,12 +2,12 @@
 14.00 | Manolo | Hamill | Kozey | 11.00
 3.00 | Zoe | Ramirez | Gea | 10.00
 5.00 | David | Schmidt | Fisher | 0.00
-15.00 | Alejandro | Kohler | Schoen | 0.00
 8.00 | Cristina | Lemke | Rutherford | 0.00
-16.00 | Antonio | Fahey | Considine | 0.00
 10.00 | Esther | Spencer | Lakin | 0.00
 12.00 | Carmen | Streich | Hirthe | 0.00
+13.00 | Alfredo | Stiedemann | Morissette | 0.00
+15.00 | Alejandro | Kohler | Schoen | 0.00
+16.00 | Antonio | Fahey | Considine | 0.00
 17.00 | Guillermo | Ruecker | Upton | 0.00
 18.00 | Micaela | Monahan | Murray | 0.00
-13.00 | Alfredo | Stiedemann | Morissette | 0.00
 20.00 | Francesca | Schowalter | Muller | 0.00
```

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-id | nif | nombre | apellido1 | apellido2 | ciudad | direccion | telefono | fecha_nacimiento | sexo | tipo
-4.00 | 17105885A | Pedro | Heller | Pagac | Almería | C/ Estrella fugaz | NULL | 2000-10-05 | H | alumno
+id | nif | nombre | apellido1 | apellido2 | ciudad | direccion | telefono | telefono | fecha_nacimiento | sexo | tipo
+4.00 | 17105885A | Pedro | Heller | Pagac | Almería | C/ Estrella fugaz | NULL | NULL | 2000-10-05 | H | alumno
```

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---
