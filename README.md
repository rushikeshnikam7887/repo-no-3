# repo-no-3
merge conflicts

sudo nano HelloWorld.java

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

FROM  openjdk:17-alpine

WORKDIR  /my-compose-app

COPY    HelloWorld.java  /my-compose-app

RUN   javac   HelloWorld.java

CMD   ["java",   "HelloWorld"]
<img width="966" height="607" alt="image" src="https://github.com/user-attachments/assets/bcbf4eaa-0e4a-4c65-8430-7e6c8377da2c" />

<img width="1060" height="626" alt="image" src="https://github.com/user-attachments/assets/99a4d94f-5113-4299-884d-ee1feafabdb2" />

<img width="925" height="607" alt="image" src="https://github.com/user-attachments/assets/5c4f9489-9518-450a-ae1d-268f8f97737a" />
