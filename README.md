# postgresql-universe-database
A relational database built in PostgreSQL modeling the universe (galaxies, stars, planets, and moons) with full foreign key relationships :)

  ## Schema
  <img width="974.25" height="595" alt="Untitled-3" src="https://github.com/user-attachments/assets/36e5fbf3-3a2a-4bbe-8460-54e2f599776c" />
  
  ## Tables
  | Table  | Rows | Description                                      |
  |--------|------|--------------------------------------------------|
  | galaxy | 6    | big galaxies, each star belongs to one          |
  | star   | 6    | stars that anchor their own planetary systems    |
  | planet | 12   | planets orbiting stars, from earth to exoplanets |
  | moon   | 21   | moons tied to their planets                      |
  | comet  | 3    | standalone, no foreign key. no allegiance       |
  
  ## Tech
  - postgreSQL

  ## Setup
  1. clone the repo: `git clone https://github.com/cassmcxi/postgresql-universe-database.git`
  2. create the database: `createdb universe`
  3. run the file: `psql universe < universe.sql` 

---

## Table Data

### <em>Star</em>
<img width="593" height="157" alt="Screenshot 2026-05-15 at 11 20 13 PM" src="https://github.com/user-attachments/assets/10e908f1-cc75-4d6a-8bd7-a6fed97d6865" /> <br>
<img width="789" height="261" alt="Screenshot 2026-05-15 at 11 23 16 PM" src="https://github.com/user-attachments/assets/4d8009c3-456c-47a2-a69a-01722ee86594" /> <br>

### <em>Comet</em>
<img width="591" height="120" alt="Screenshot 2026-05-15 at 11 20 44 PM" src="https://github.com/user-attachments/assets/15beb8cc-8408-487a-a722-2a7161fd8aef" /> <br>
<img width="835" height="177" alt="Screenshot 2026-05-15 at 11 23 33 PM" src="https://github.com/user-attachments/assets/d8ec9ae3-1555-4abf-a1ab-dcde80a09fc5" /> <br>

### <em>Galaxy</em>
<img width="734" height="156" alt="Screenshot 2026-05-15 at 11 21 27 PM" src="https://github.com/user-attachments/assets/f15f3433-e10d-4620-aca9-2e4a73012cb4" /> <br>
<img width="805" height="234" alt="Screenshot 2026-05-15 at 11 23 47 PM" src="https://github.com/user-attachments/assets/ee9ae9ad-2c21-4a80-b79a-f7f3bbeb4355" /> <br>

### <em>Planet</em>
<img width="709" height="241" alt="Screenshot 2026-05-15 at 11 21 44 PM" src="https://github.com/user-attachments/assets/8f1ba8b5-be83-4b5f-a677-cd2bb60cc31e" /> <br>
<img width="802" height="272" alt="Screenshot 2026-05-15 at 11 23 56 PM" src="https://github.com/user-attachments/assets/f47a76a9-68b7-46e5-9f49-e235c6952d18" /> <br>

### <em>Moon</em>
<img width="623" height="369" alt="Screenshot 2026-05-15 at 11 22 03 PM" src="https://github.com/user-attachments/assets/121be396-26bb-4e5a-982d-99af8d04df9c" /> <br>
<img width="622.5" height="173.25" alt="Screenshot 2026-05-15 at 11 24 15 PM" src="https://github.com/user-attachments/assets/18035516-603c-4cc2-b7a5-b6df0ea9f867" /> <br>

  


