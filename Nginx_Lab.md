

- Install Nginx

![Screenshot from 2022-12-17 12-45-26](https://user-images.githubusercontent.com/110255978/208238087-5988fbc5-fd53-4559-9497-c65c56b2746a.png)

![Screenshot from 2022-12-17 12-46-33](https://user-images.githubusercontent.com/110255978/208238093-b35d1dbc-b757-4207-9e67-1f360fc5fdac.png)


- Change the default file (index.html) to (yourName.html)

![Screenshot from 2022-12-17 13-21-42](https://user-images.githubusercontent.com/110255978/208239352-371737c5-e190-49c1-809d-0efc4394ba8e.png)

![Screenshot from 2022-12-17 13-22-17](https://user-images.githubusercontent.com/110255978/208239356-7ec7f88c-0848-4b3a-a75b-a5a760809910.png)

![Screenshot from 2022-12-17 13-23-09](https://user-images.githubusercontent.com/110255978/208239365-e345f166-c767-496d-a8fa-2042aa222e47.png)

![Screenshot from 2022-12-17 13-23-41](https://user-images.githubusercontent.com/110255978/208239373-89e55372-6518-4046-92df-e7d1dd063c8b.png)

![Screenshot from 2022-12-17 13-23-53](https://user-images.githubusercontent.com/110255978/208239376-ca0cedb4-6b6b-46c5-b41f-f560baeeb071.png)


- Make two html files, and change the configuration file to access the first file on port 81, and access the second file on port 82.

![Screenshot from 2022-12-17 14-55-31](https://user-images.githubusercontent.com/110255978/208242965-90b35bab-e65e-4d05-8ff4-6b188f2d60ba.png)

![Screenshot from 2022-12-17 14-55-54](https://user-images.githubusercontent.com/110255978/208242972-8042900f-182f-4544-9ec6-ec2568f9f0a9.png)


![Screenshot from 2022-12-17 14-56-06](https://user-images.githubusercontent.com/110255978/208242976-1857c029-7f57-4b25-8afe-698f56e5e5b0.png)

![Screenshot from 2022-12-17 14-56-21](https://user-images.githubusercontent.com/110255978/208242979-b34fbce7-18b7-4fb0-afc9-804f669068f5.png)

![Screenshot from 2022-12-17 14-56-35](https://user-images.githubusercontent.com/110255978/208242984-2464140d-cec6-41b6-90a5-085aa827ce2e.png)


- Tell me the main differences between Apache & Nginx
- Apache:
1.  is an open-source web server.
2.	It is mostly used for Unix, Linux, Windows and Solaris platforms.
3.	It was developed by Apache group and initially released on 25 March 1999.
4.	Apache is written in C and XML.
5.	It is designed for web server.
6.	In heavy web traffic, it cannot support multiple requests.
7.	In Apache, modules are dynamically fixed that make it more complex.
8.	It follows Multi-Threaded approach to process client requests.
9.	In Apache, there is a dynamic content in web server itself.
10.	Apache’s performance for static content is lower than that of Nginx.
11.	Less security provided as compared to Nginx and also the codebase is very high.
12.	File system location are passed to interpret the client requests.
13.	Complex configuration system as compared to Nginx.

- Nginx: 
1. is a web server. It is also used as a reverse proxy server which revices the request from client and send the request to proxy server.
2. It is mostly used for Unix like systems, and does not completely support Windows.
3. It was developed by Nginx.inc and initially released on 4 october 2004.
4. Nginx is written in C language.
5. It is designed for proxy server as well as web server.
6. It can support multiple client requests with limited hardware resources.
7. In Nginx, modules cannot be loaded dynamically as there is a core software in which they are complied .
8. It follows Event-Driven approach to process client requests.
9. It does not support provide dynamic content.
10. Nginx’s performance of static content is two times faster than that of Apache as it can simultaneously run thousands of connections and it uses less memory comparatively.
11. It provides better security with a smaller codebase.
12. It passes Uniform Resource Identifier (URI) to interpret the client requests.
13. It has relatively simpler configuration system.

