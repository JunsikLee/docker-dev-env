## 1. μ€ν λ°©λ² 
### π§π» docker-compose μ€ν
<pre>
sh docker-on.sh
</pre>

### π§π» docker-compose μ’λ£
<pre>
sh docker-off.sh
</pre>

</br>

## 2. λ€λ₯Έ λμ»€ Tool λ€νΈμν¬ μ°κ²° νκΈ°
+ λμ»€ λ€νΈμν¬ μ΄λ¦ - network-docker-devtool
+ λμ»€ λ€νΈμν¬ μ°κ²° μμ  μ½λ (μ°κ²°μ νΈμ€νΈ λͺ service μ΄λ¦ μ΄μ©)
```
docker run -d --name ubuntu --network network-docker-devtool ubuont:20.04 bash
```
</br>

## 3. μ€μΉ μ λ³΄
### π§π»βπ» 1.1 Postgresql
```
ν¬νΈ - 5432
μμ΄λ - postgres
ν¨μ€μλ - pass
```
</br>

### π§π»βπ» 1.2. Mariaddb
```
ν¬νΈ - 3306
μμ΄λ - user
ν¨μ€μλ - pass
```
</br>

### π§π»βπ» 2.1 Rabbitmq
```
κ΄λ¦¬νμ΄μ§ - http://127.0.0.1:15672
ν¬νΈ - 5672
μμ΄λ - user
ν¨μ€μλ - pass
```
</br>

### π§π»βπ» 2.2 Kafka, Zookeeper, Kafdrop
```
Kafka ν¬νΈ - 9092
kafdrop μ μ - http://127.0.0.1:9091
```
</br>

### π§π»βπ» 3.1 Radis
```
ν¬νΈ - 6379
```
</br>