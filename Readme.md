## 🎮 Yummy OMS Devops

### Support
1. Mongodb with Replica setup
2. Kafka and Zookeper
3. Redis
4. Nginx (Optional)
### How to setup
1. copy file `.env.example` into `.env`
2. Install docker and docker compose
3. (Optional) install forever `npm i -g forever`
4. You ready to up container with `docker-compose up -d`

### Note
1. 🦚 Mongodb connection
   - Primary `mongodb://root:password@localhost:27018`
   - Secondary `mongodb://root:password@localhost:27018`
2. 🐚 Kafka ready listen in port `9094`