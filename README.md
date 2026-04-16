wget -O - https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(grep -oP '(?<=UBUNTU_CODENAME=).*' /etc/os-release || lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
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




sudo nano docker-compose.yml

services:
  java-helloworld:
    build: .
    container_name: java-helloworld-container
    command: ["java", "HelloWorld"]

https://github.com/newdelthis/demo/blob/main/pod_1.yml



<!DOCTYPE html>
<html>
<head>
    <title>IACSD Institute</title>
</head>

<body style="margin:0; font-family:Arial, sans-serif; background:#f4f6f9;">

    <!-- Header -->
    <div style="background:#0d47a1; color:white; padding:20px; text-align:center;">
        <h1 style="margin:0;">IACSD Institute</h1>
        <p style="margin:5px;">Empowering Students with Technology</p>
    </div>

    <!-- Navbar -->
    <div style="background:#1565c0; padding:10px; text-align:center;">
        <a href="#" style="color:white; margin:15px; text-decoration:none; font-weight:bold;">Home</a>
        <a href="#" style="color:white; margin:15px; text-decoration:none; font-weight:bold;">Courses</a>
        <a href="#" style="color:white; margin:15px; text-decoration:none; font-weight:bold;">About</a>
        <a href="#" style="color:white; margin:15px; text-decoration:none; font-weight:bold;">Contact</a>
    </div>

    <!-- Hero Section -->
    <div style="padding:50px; text-align:center; background:linear-gradient(to right,#42a5f5,#1e88e5); color:white;">
        <h2 style="font-size:40px;">Welcome to IACSD</h2>
        <p style="font-size:18px;">Learn Programming, Networking & AI from Experts</p>
        <button style="padding:12px 25px; background:white; color:#1565c0; border:none; border-radius:5px; font-weight:bold; cursor:pointer;">
            Explore Courses
        </button>
    </div>

    <!-- Courses Section -->
    <div style="padding:40px; text-align:center;">
        <h2>Our Courses</h2>

        <div style="display:flex; justify-content:center; gap:20px; flex-wrap:wrap;">

            <div style="background:white; padding:20px; width:250px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
                <h3>Full Stack Development</h3>
                <p>HTML, CSS, JS, React, Node.js</p>
            </div>

            <div style="background:white; padding:20px; width:250px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
                <h3>Networking</h3>
                <p>CCNA, Routing, Switching</p>
            </div>

            <div style="background:white; padding:20px; width:250px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
                <h3>Artificial Intelligence</h3>
                <p>ML, Deep Learning, NLP</p>
            </div>

        </div>
    </div>

    <!-- About Section -->
    <div style="background:#e3f2fd; padding:40px; text-align:center;">
        <h2>About IACSD</h2>
        <p style="max-width:700px; margin:auto;">
            IACSD Institute provides industry-level training in software development, networking, and AI.
            Our mission is to make students job-ready with practical skills.
        </p>
    </div>

    <!-- Contact Section -->
    <div style="padding:40px; text-align:center;">
        <h2>Contact Us</h2>

        <input type="text" placeholder="Your Name"
            style="padding:10px; width:250px; margin:10px; border-radius:5px; border:1px solid #ccc;"><br>

        <input type="email" placeholder="Your Email"
            style="padding:10px; width:250px; margin:10px; border-radius:5px; border:1px solid #ccc;"><br>

        <textarea placeholder="Your Message"
            style="padding:10px; width:250px; height:100px; margin:10px; border-radius:5px; border:1px solid #ccc;"></textarea><br>

        <button style="padding:10px 20px; background:#1565c0; color:white; border:none; border-radius:5px;">
            Send Message
        </button>
    </div>

    <!-- Footer -->
    <div style="background:#0d47a1; color:white; text-align:center; padding:15px;">
        <p>© 2026 IACSD Institute | All Rights Reserved</p>
    </div>

</body>
</html>
    
<img width="1180" height="626" alt="image" src="https://github.com/user-attachments/assets/88a8ee17-654f-44d5-9b86-aba13beea5ff" />

<img width="966" height="607" alt="image" src="https://github.com/user-attachments/assets/bcbf4eaa-0e4a-4c65-8430-7e6c8377da2c" />

<img width="1060" height="626" alt="image" src="https://github.com/user-attachments/assets/99a4d94f-5113-4299-884d-ee1feafabdb2" />

<img width="925" height="607" alt="image" src="https://github.com/user-attachments/assets/5c4f9489-9518-450a-ae1d-268f8f97737a" />
