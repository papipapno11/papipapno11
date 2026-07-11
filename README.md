# Hallo, ich bin Mirko Messinetti 👋

## Data Analyst / Junior Data Engineer

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-CONNECT-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mirko-messinetti-093221417/)
[![Email](https://img.shields.io/badge/EMAIL-KONTAKT-green?style=for-the-badge&logo=gmail)](mailto:mirco.messinetti@web.de)

## 🚀 Über mich

Ich bin Wirtschaftsinformatiker (B.Sc.) und fokussiere mich voll auf die datengetriebene Business-Analyse. Daten sind für mich kein Selbstzweck. Mich reizt es, verstreute Datenquellen zusammenzuführen und so aufzubereiten, dass operative Teams verlässliche Entscheidungen treffen können.

Durch meine mehr als einjährige Praxiserfahrung als Werkstudent im Bereich Datenanalyse weiß ich, wie man isolierte Datensilos aufbricht. Bei der Getiteasy GmbH lag mein Schwerpunkt darauf, CRM- und Marketingdaten zentral zu verknüpfen, um Marketing-Ausgaben direkt mit echten Vertriebs-Umsätzen abzugleichen und unprofitable Hebel zu eliminieren.

Ich bringe ein starkes logisch-analytisches Fundament aus meinem Studium mit und kombiniere dieses technische Verständnis mit meinen Erfahrungen aus dem Controlling, um Berichte und Datenstrukturen performant, sauber und vor allem geschäftlich sinnvoll aufzubauen.

## 🛠️ Technische Fähigkeiten 

### Datenanalyse & Visualisierung
![SQL](https://img.shields.io/badge/SQL-Intermediate-blue)
![Power BI](https://img.shields.io/badge/Power_BI-Intermediate-yellow)
![DAX](https://img.shields.io/badge/DAX-Intermediate-orange)
![Excel](https://img.shields.io/badge/Excel-Intermediate-brightgreen)
![dbt](https://img.shields.io/badge/dbt-Beginner-orange)

### Programmierung & Automatisierung
![Python](https://img.shields.io/badge/Python-Intermediate-blue)
![Java](https://img.shields.io/badge/Java-Beginner-brown)
![Git](https://img.shields.io/badge/Git-Beginner-black)

### Business Intelligence & Analytics
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-Intermediate-lightblue)
![Data Warehousing](https://img.shields.io/badge/Data_Warehousing-Beginner-blue)
![Snowflake](https://img.shields.io/badge/Snowflake-Beginner-blue)
![Statistische Analyse](https://img.shields.io/badge/Statistische_Analyse-Intermediate-teal)

---

## 🛠️ Woran ich aktuell arbeite

### 📊 End-to-End People Analytics Platform (In Umsetzung)
**Fokus:** Strategische HR-Analyse (Demografischer Wandel & Fluktuation) mit dem Microsoft- & Open-Source-Data-Stack.

* **Das Projektziel:** Schaffung einer datenschutzkonformen „Single Source of Truth“, die unstrukturierte Daten bereinigt, zentralisiert und in gewohnte Excel-Pivot-Umgebungen für die Fachabteilung überführt.
* **Die Pipeline & der Tool-Einsatz:**
  `[Kaggle IBM Data] ──> (Python/Pandas) ──> [PostgreSQL Staging] ── [PostgreSQL Core Schema] ──> [Fabric Lakehouse] ── (Semantisches Modell) ──> [Excel Pivot-Dashboard]`
* **Stufe 1 (Python & Pandas):** Einlesen, transformieren und anonymisieren sensibler Personaldaten (DSGVO-Hashing) sowie Berechnung eines Kündigungsrisikos in %.
* **Stufe 2 (PostgreSQL):** Transformation flacher Tabellen in ein performantes Sternschema (Star Schema) inklusive Erstellung von Dimensionen, Fakten und erweiterten Metriken (z. B. Compa-Ratio via Window Functions & CTEs).
* **Stufe 3 (Microsoft Fabric):** Orchestrierung automatisierter Cloud-Pipelines von PostgreSQL ins Fabric Lakehouse (Delta-Format) und Bereitstellung des zentralen Semantischen Modells.
* **Stufe 4 (Excel Frontend):** Cloud-Direktanbindung ohne lokalen Daten-Download, Implementierung komplexer DAX-Measures für dynamische Fluktuationsquoten sowie der Aufbau interaktiver Pivot-Tabellen und Slicer-Dashboards.

---

## 📂 Ausgewählte Projekte (Abgeschlossen)

### 📈 End-to-End E-Commerce Analytics Platform (Olist)
💻 [**Zum GitHub-Repository**](https://github.com/papipapno11/olist-ecommerce-analytics-snowflake-dbt-powerbi)
* **Stack:** `Snowflake | dbt | SQL | Power BI | DAX | Git`
* **Impact:** Aufbau einer modular skalierbaren Cloud-Datenplattform für 100k Bestellungen. Strukturierung einer modernen ELT-Pipeline über einen dreistufigen dbt-Layer (Staging, Intermediate, Marts) inklusive automatisierter Schema- und Integritätstests zur Sicherung der Datenqualität. Aufdeckung einer kritischen Umsatzkonzentration (76 % Umsatztreiber in den Top 15 Kategorien) via Star-Schema-Dashboard.

### 🔬 Bachelorarbeit: Asymmetrische Dissimilaritäten beim Clustering
💻 [**Zum GitHub-Repository**](https://github.com/papipapno11/asymmetric-graph-clustering)
* **Stack:** `Python | NumPy | Pandas | NetworkX`
* **Impact:** Entwicklung einer vollständig vektorisierten Erweiterung des $k$-Means-Algorithmus zur fehlerfreien Verarbeitung gerichteter Graphstrukturen. Erzielung einer konstanten Laufzeit von 0,020 s pro algorithmischem Restart sowie Steigerung der Clustering-Genauigkeit (ARI) im VBB-Infrastrukturnetzwerk um 5,7 % gegenüber klassischen symmetrischen Algorithmen.

### 🏫 Datenbankgestützte Hochschulverwaltung
* **Stack:** `PostgreSQL | SQL | Python | Streamlit`
* **Impact:** Optimierung der Abbildung komplexer Hochschuldaten durch den Entwurf eines relationalen 3NF PostgreSQL-Schemas mit mehreren verknüpften Entitäten. Effizienzsteigerung bei Analyse- und Abfrageprozessen durch gezielte Indexierung sowie Entwicklung eines interaktiven Streamlit-Dashboards zur intuitiven Visualisierung von Personen-, Raum- und Prüfungsdaten.

---

## 🌱 Woran ich aktuell lerne

* **Microsoft Fabric:** Vertiefung von Cloud-Orchestrierungen, Lakehouse-Architekturen (Delta-Format) und dem Design zentraler semantischer Modelle für Unternehmenseinsätze.
