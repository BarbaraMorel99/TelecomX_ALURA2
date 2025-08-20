# TelecomX_ALURA2
♥Conclusión técnica

La tasa global de cancelación es cercana al 26%, lo que indica un problema relevante de retención.
Los modelos entrenados (Regresión Logística y Random Forest) muestran un desempeño aceptable.
Las variables más influyentes son:
Tipo de contrato: los contratos mensuales presentan mucho más churn que los contratos de 1 o 2 años.
Método de pago: el pago con cheque electrónico está muy asociado al churn; los pagos automáticos son más estables.
InternetService: la fibra óptica tiene una tasa de churn más alta que DSL.
Tenure: los clientes más nuevos tienen mayor probabilidad de irse.
Cargos mensuales altos también se relacionan con mayor churn.
El uso de class_weight='balanced' compensó el desbalance de clases.


♥Conclusión ejecutiva

1 de cada 4 clientes se da de baja → es un riesgo alto.
Contratos mensuales = foco rojo → ofrecer descuentos o beneficios para que pasen a contratos anuales o bianuales.
Cheques electrónicos = clientes inestables → incentivar pagos automáticos o bancarios.
Clientes nuevos son frágiles → acompañamiento especial en los primeros 3–6 meses.
Clientes con facturas altas → dar beneficios extra (soporte, bundles, promociones) para fidelizar.
Fibra óptica muestra más deserción → investigar calidad del servicio y reforzar atención a esos clientes.
