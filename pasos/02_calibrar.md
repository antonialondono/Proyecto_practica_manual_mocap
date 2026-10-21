# 2. Configurar y calibrar en Motive

**Objetivo:** dejar el espacio calibrado, con la calidad verificada y una referencia espacial consistente.

## Antes de empezar
- [ ] Proyecto de captura abierto en OptiTrack Motive
- [ ] Cámaras conectadas y detectando el espacio de trabajo

## Pasos
1. Abre el proyecto de captura en Motive y comprueba que las cámaras estén conectadas y detectando el espacio de trabajo.
2. Inicia una nueva calibración desde el panel de calibración.
   ![Panel de calibración](img/02_panel_calibracion.png)
3. Si una cámara capta un reflejo o ruido y muestra el icono de advertencia, pulsa **Mask**: se creará una máscara sobre el objeto que causa el problema.
4. Cuando todas las cámaras estén sin advertencias, inicia el **wanding**: mueve la vara por la zona de captura, incluyendo movimientos amplios en forma de ocho, para que las cámaras registren suficientes muestras.
   ![Movimiento en ocho con la vara](img/02_wanding.png)
5. Finaliza la calibración y verifica la calidad obtenida.
6. Establece el plano del suelo y el origen y la orientación del espacio, para que la referencia espacial sea consistente entre capturas. Se recomienda que el eje Z sea el eje principal por el que se va a desplazar el participante.

## ✅ Cómo saber que quedó bien
- Todas las cámaras sin advertencias.
- Idealmente, entre **4.000 y 10.000 muestras** por cámara.
- Error medio de rayo (**Mean Ray Error**) menor a **0,6 mm**.
- Plano del suelo y origen definidos.

## ⚠️ Punto crítico
Define el plano del suelo, el origen y la orientación de la misma forma en todas las sesiones: de eso depende que las capturas sean consistentes entre sí.

## 🛠️ Si algo falla
| Síntoma | Qué hacer |
|---|---|
| Una cámara muestra el icono de advertencia | Pulsa **Mask** para enmascarar el objeto que causa el reflejo o ruido |
| Menos de 4.000 muestras en alguna cámara | [completar] |
| Mean Ray Error de 0,6 mm o más | [completar] |
