<h1 align="center">IA y Ciberseguridad</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Adversarial%20ML-BC8CFF?style=flat-square" />
  <img src="https://img.shields.io/badge/OWASP%20LLM%20Top%2010-000000?style=flat-square&logo=owasp&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/MITRE%20ATLAS-58A6FF?style=flat-square" />
</p>

---

## Sobre este módulo

La IA es a la vez **herramienta defensiva, superficie de ataque y arma ofensiva**. Este módulo cubre las tres caras: cómo la IA potencia la seguridad, cómo se ataca a los propios modelos, y los riesgos específicos de los LLM.

**Temas cubiertos:** machine learning aplicado a detección · adversarial ML (evasión, envenenamiento, extracción de modelo) · seguridad de LLM (prompt injection, jailbreaking) · OWASP Top 10 para LLM · MITRE ATLAS · IA para red y blue team.

---

## Concepto clave — Ataque adversarial (FGSM)

Una perturbación imperceptible para el ojo humano, calculada en la dirección del gradiente de la pérdida, hace que un clasificador confiado falle por completo. Demuestra por qué un modelo con alta precisión no es necesariamente robusto.

![Ataque FGSM](fgsm-attack.png)

---

## Temas destacados

- **Adversarial ML** — evasión (FGSM, PGD), envenenamiento de datos de entrenamiento, robo de modelo por consultas.
- **Seguridad de LLM** — prompt injection directa e indirecta, fuga de datos, el usuario como adversario no confiable.
- **Marcos de referencia** — OWASP Top 10 para LLM (2025) y MITRE ATLAS para mapear amenazas a sistemas de IA.
- **Doble uso** — la IA acelera tanto la detección de anomalías como la generación de phishing y malware.

---

## Stack

`Python` · `PyTorch` · `scikit-learn` · `OWASP LLM Top 10` · `MITRE ATLAS`

---

## Módulo relacionado

- **[Blue Team](https://github.com/juanmalbran/blue-team)** — el ML aplicado a detección de anomalías se integra en el pipeline del SOC.

---

<div align="center">
  <sub>Parte del portfolio de <a href="https://github.com/juanmalbran">Juan Malbrán · M4LBYTE</a></sub>
</div>
