# πΌ λ°μ΄ν°λ² μ΄μ€

### DB

- DB(λ°μ΄ν°λ² μ΄μ€)λ λ°μ΄ν°μ μ§ν©μ μλ―Έν©λλ€.
- DBMSλ μ΄λ¬ν λ°μ΄ν°λ² μ΄μ€λ₯Ό κ΄λ¦¬ν΄μ£Όλ μννΈμ¨μ΄μλλ€.

### RDB

- RDBλ κ΄κ³ν λ°μ΄ν°λ² μ΄μ€λ₯Ό μλ―Ένλ©° λ°μ΄ν°λ² μ΄μ€κ° κ΄κ³λ₯Ό λ§Ίκ³  μμ΅λλ€.
- 2μ°¨μ νμ΄λΈ ννλ‘ ννλλ©° νμ΄λΈ κ° Joinμ΄ κ°λ₯ν©λλ€.

### NoSQL

- κ΄κ³λ₯Ό μ μνμ§ μμ Joinμ΄ λΆκ°λ₯ νμ§λ§ RDBμ λΉν΄ μλκ° λΉ λ¦λλ€.
- λνμ μΌλ‘ ν€λ²¨λ₯ λ°μ΄ν°λ² μ΄μ€, λ€νλ¨ΌνΈ λ°μ΄ν°λ² μ΄μ€ λ±μ΄ μμ΅λλ€.

### DB Normalization

- DBμ κ·νλ νμ΄λΈμ μ κ·νμ΄λΌκ³  λΆλ¦¬λ ννμ λΆν©νλλ‘ λ§λ€μ΄ κ°λ κ²μ μλ―Έν©λλ€.
- νμ΄λΈμ΄ μ λ§λ€μ΄μ‘λμ§ νμΈνκ³  κ³ μ³λκ°λ κ³Όμ μλλ€.

### μ  1 μ κ·ν

- νμ΄λΈμ μΉΌλΌμ΄ μμκ°μ κ°λλ‘ νμ΄λΈμ λΆν΄ν©λλ€.
- μ¦, μμ± νλλ νλμ μμ±κ°λ§μ κ°μ ΈμΌ ν©λλ€.

### μ  2 μ κ·ν

- μ  1 μ κ·νλ₯Ό μ§νν νμ΄λΈμ λν΄ μμ ν¨μ μ’μμ λ§μ‘±νλλ‘ νμ΄λΈμ λΆν΄ν©λλ€.
- κΈ°λ³Έν€μ λΆλΆμ§ν©μ΄ κ²°μ μκ° λμ΄μλ μλλ€λ κ²μ μλ―Έν©λλ€.

### μ  3 μ κ·ν

- μ  2 μ κ·νλ₯Ό μ§νν νμ΄λΈμ λν΄ μ΄νμ μ’μμ μμ λλ‘ νμ΄λΈμ λΆν΄ν©λλ€.
- Aκ° Bλ₯Ό κ²°μ νκ³  Bκ° Cλ₯Ό κ²°μ νλ©΄ A B , B C λ‘ λΆλ¦¬ν΄μΌ ν©λλ€.

### BCNF μ κ·ν

- μ  3 μ κ·νλ₯Ό μ§νν νμ΄λΈμ λν΄ λͺ¨λ  κ²°μ μκ° νλ³΄ν€κ° λλλ‘ νμ΄λΈμ λΆν΄ν©λλ€.
- λ³΅ν©ν€κ° κΈ°λ³Έν€λ‘ μ¬μ©λμ΄ νΉμ  μΉΌλΌμ κ²°μ ν  κ²½μ°, κ·Έ μΉΌλΌμ΄ λ³΅ν©ν€ μ€ μΌλΆλ₯Ό κ²°μ νλ κ²°μ μλΌλ©΄ λΆλ¦¬ν©λλ€.

### JOIN

- κ΄κ³ν λ°μ΄ν°λ² μ΄μ€μμ λ μ΄μμ νμ΄λΈμ μ°κ²°νμ¬ λ°μ΄ν°λ₯Ό κ²μνλ κ²μ μλ―Έν©λλ€.
- μ μ΄λ νλμ μΉΌλΌμ κ³΅μ νκ³  μμ΄μΌ ν©λλ€.

### INDEX

- μΆκ°μ μΈ κ³΅κ°μ νμ©νμ¬ νμ΄λΈ κ²μμλλ₯Ό ν₯μμν€λ μλ£κ΅¬μ‘°λ‘ μ£Όλ‘ B-Tree κ³μ΄μ νμ©ν©λλ€.
- ν­μ μ΅μ μ μ λ ¬ μνλ‘ μ μ§ν΄μΌ νλ―λ‘ μ½μ μ­μ  μλ°μ΄νΈκ° μμ£Ό μΌμ΄λλ©΄ λΆμ ν©ν©λλ€.

### INDEXμμ ν΄μνμ΄λΈμ μ°μ§ μλμ΄μ 

- ν΄μλ λ¨ νλμ λ°μ΄ν°λ₯Ό μ°Ύμ λλ μμλ³΅μ‘λλ‘ λΉ λ₯Ό μ μμ΅λλ€.
- νμ§λ§ νμ΄λΈμμ λΆλ±νΈμ κ°μ μ‘°κ±΄μΌλ‘ μ¬λ¬ κ°μ μ°Ύμ κ²½μ° μ λ ¬λμ΄ μμ§ μλ κ΅¬μ‘°λ λΉν¨μ¨μ μλλ€.
