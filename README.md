# PRTG Sensor Monitor

This project provides a Python-based service, operated via Docker, to periodically query PRTG monitoring servers. It collects data from sensors in a "Warning" or "Down" state and stores the results in a PostgreSQL database for further analysis and visualization.

The system is designed as a two-part Docker Compose setup:
1.  **PRTG Monitor Service:** The core application that polls the PRTG API.
2.  **Database Stack:** A supporting stack containing a PostgreSQL database and an Adminer web UI for easy management.

---

## Setup and Documentation

For detailed setup instructions, please choose your preferred language. The documentation files are located in the `/docs` directory.

<p align="center">
  <a href="docs/README-EN.md"><img src="https://img.shields.io/badge/Documentation-English-blue?style=for-the-badge&logo=read-the-docs" alt="English Documentation"></a>
      
  <a href="docs/README-DE.md"><img src="https://img.shields.io/badge/Dokumentation-Deutsch-red?style=for-the-badge&logo=read-the-docs" alt="Deutsche Dokumentation"></a>
</p>