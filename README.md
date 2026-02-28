# Houses4Us

A full-stack app to automate the preparation of **Affirmative Fair Housing Marketing Plans (AFHMP)** for the Department of Housing, Economic Development, and Commerce Division of Affordable Housing in Jersey City.  

Given a location, the app fetches and analyzes demographic data, then generates ready-to-use PDF and Excel reports to streamline compliance and save time.

---

## Tech Stack

- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Python / FastAPI  
- **Serverless / Orchestration:** Docker + Docker Compose (optional Redis cache)  
- **Data Sources:** U.S. Census Bureau ACS API  

---

## Features

- Enter a location to automatically fetch relevant demographic information.  
- Generate **AFHMP-ready reports** in PDF and Excel formats.  
- Auto-fill official forms to reduce manual work and errors.  
- Interactive dashboard to visualize demographic data before export.  

---

## APIs & Services

- [U.S. Census Bureau ACS API](https://www.census.gov/data/developers/data-sets.html) – demographic data  
- Geocoding service for location parsing (Google Maps or similar)  
- AWS Cognito (optional) for authentication  

---

## Deployment

- **Local development:** `docker-compose up` to run frontend + backend (+ Redis cache if needed)  
- **Frontend deployment:** [Vercel](https://vercel.com/)  
- **Backend deployment:** [AWS SAM](https://aws.amazon.com/serverless/sam/) or containerized via Docker  

---

## License

MIT