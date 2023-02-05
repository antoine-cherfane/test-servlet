# Test Servlet

## Prerequisites
- Java
- Apache Tomcat

## Usage
- git clone the project
- Copy `test-servlet.war` to `webapps` directory in Apache Tomcat
- In Apache Tomcat, navigate to the `bin` folder and run `startup.bat`
- Open `index.html` in your browser

![image](https://user-images.githubusercontent.com/62336052/216839814-8ad08cfd-6212-4687-9fea-b93cab321013.png)
- Click on the link

![image](https://user-images.githubusercontent.com/62336052/216839832-1c201356-b1a0-4055-bf9e-4b8d617081a8.png)

## Create WAR File
In the root of the project:
- Compile the `BonjourServlet.java` file with: `javac -d WEB-INF/classes -cp WEB-INF/lib/servlet-api.jar BonjourServlet.java`
- Generate the WAR file with: `jar -cvf test-servlet.war WEB-INF BonjourServlet.java`

![image](https://user-images.githubusercontent.com/62336052/216839789-4c742de8-31be-464c-8fbf-a959d4f1ee78.png)
