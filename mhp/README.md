# MySQL 성능 최적화 : 고성능 시스템 구축을 위한 전략과 최적화 기법(book-high-performance-mysql)

# 실행
## 컨테이너 기동
```
cd 
git clone https://github.com/Finfra/mysqlHpCourse
cd ~/mysqlHpCourse/mhp
docker-compose up -d
```

## 컨테이너 접속
### Console Container
```
docker exec -it mhp_v8.0_1  bash
  mysql -uroot -proot -hv5.6
  # or
  mysql -uroot -proot -hv5.7
  # or
  mysql -uroot -proot -hv8.0
```
### Mysql Version : 5.6
```
docker exec -it mhp_v5.6_1 bash
# or
docker exec -it mhp_v5.6_1 mysql -uroot -proot
```
### Mysql Version : 5.7
```
docker exec -it mhp_v8.0_1 bash
# or
docker exec -it mhp_v8.0_1 mysql -uroot -proot

```
### Mysql Version : 8.0
```
docker exec -it mhp_v5.7_1 bash
# or
docker exec -it mhp_v5.7_1 mysql -uroot -proot
```


## 컨테이너 제거
```
cd ~/mysqlHpCourse/mhp
docker-compose down -d
```
