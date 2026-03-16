# Telemedicine Intake System
**High-efficiency patient data acquisition and screening platform using Google Sheets.**

## Overview

The **Telemedicine Intake System** is engineered to eliminate manual bottlenecks in patient registration. By digitizing the initial intake process, the system ensures that healthcare providers receive structured clinical data and signed consents before the consultation begins, reducing administrative latency and improving data accuracy.

The system is used to support telemedicine services operated by **Kamphaeng Phet Municipality** in Thailand, where healthcare teams provide remote consultations and monitoring for community patients, including elderly and homebound individuals.

Evidence of municipal telemedicine deployment:
https://www.kppmu.go.th/news-detail?hd=1&id=124000


## Architecture

| Layer | Description |
| :--- | :--- |
| **Pattern** | Stateless Layered Architecture |
| **Flow** | [User] -> [Frontend] -> [API] -> [Google Sheets] |
| **Integrations** | Google Sheets API |

## Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | Next.js (App Router), TailwindCSS |
| **Backend** | Node.js (REST APIs) |
| **Database** | Google Sheets |

## Project Structure

| Directory | Description |
| :--- | :--- |
| `app/` | Core application logic, routing, UI components, and API handlers. |

## License
Distributed under the MIT License.
