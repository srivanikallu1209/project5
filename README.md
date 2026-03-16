1. Prerequisites
Docker & Docker Compose

JDK 21+

Node.js 18+

2. Spin up Infrastructure
Launch the database cluster and search engine:

Bash
docker-compose up -d postgres mongodb elasticsearch redis
3. Run the Backend
Bash
cd analytics-backend
./gradlew bootRun
4. Launch Mobile App
Bash
cd analytics-mobile
npm install
npx expo start
