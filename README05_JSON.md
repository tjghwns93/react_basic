
![image](https://github.com/tjghwns93/react_basic/assets/129016977/117b4a12-ff8a-45d5-9b2a-9bf5ed500a10)

    npm i json-server
    
# db.json 파일 만들기   
![image](https://github.com/tjghwns93/react_basic/assets/129016977/a876f96f-36be-4f5e-b91e-41095c6061e8)

# db.json파일은 root에 만들어야한다.
![image](https://github.com/tjghwns93/react_basic/assets/129016977/ba130630-e5cf-4eb2-8b69-629da6fe2199)

# db.json 실행하기
![image](https://github.com/tjghwns93/react_basic/assets/129016977/9bd38013-636c-4c9b-9645-d1c30c0d1d85)

# 위와 같이 실행하면 port를 3000번을 사용하기 때문에 react와 중복이 되어버린다.
# 그래서 port를 변경해 주어야 한다.
        npx json-server --watch db.json --port 3004


