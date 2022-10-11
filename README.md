# FATIA SUSANTI

# REFERENSI PENGERJAAN CHALLENGE 05 dari YT : https://youtu.be/W7JG8P_BY6w

# Keterangan:
nodemon: npm run start-dev
akses localhost/homepage: http://localhost:5000/
post, put, delete menggunakan postman : http://localhost:5000/notes/
"dependencies": 
    "cli": "^1.0.1",
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "dotenv": "^16.0.0",
    "express": "~4.16.1",
    "fastest-validator": "^1.12.0",
    "morgan": "~1.9.1",
    "mysql2": "^2.3.3",
    "sequelize": "^6.19.0",
    "sequelize-cli": "^6.4.1"

erd: |notes               |
     |--------------------|
     |id: integer         |
     |title: string       |
     |description: string |
     |createdAt: date     |
     |updatedAt: date     |
     |--------------------|
