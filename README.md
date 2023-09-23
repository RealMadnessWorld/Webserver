<div align=center>
  <h1>
    Webserv
  </h1>
<img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" title="CPP" alt="CPP Logo" width="55" height="55" align="right" />&nbsp;  

> The primary function of a web server is to store, process, and deliver web pages to
> clients. The communication between client and server takes place using the Hypertext Transfer Protocol (HTTP).
</div>

---

<h2 align=center>
	Description
</h2>

 <p> Webserv is a web server that uses http protocol, written from scratch in C++ (C++98), capable of handling multiple servers, stress tests and uploads. </p>
 
> Disclaimer: Only tested on Firefox

Project done in collaboration with:  
- [Rodrigo Ramos](https://github.com/ramos21rodrigo)  
- [Nuno Carvalho](https://github.com/Kuninoto)  

![](./extras/logs_showcase.png)

---

<h2 align=center>
	Features
</h2>

- NGINX-like configuration file
- Handling of the **GET**, **POST** and **DELETE** HTTP request methods  
- File upload  
- Python CGI support   

<h2 align=center>
	How to run
</h2>

- Installing webserv dependencies:  

		sudo apt-get install c++ make  
- Clone this repository:  

		git clone https://github.com/RealMadnessWorld/Webserver
- Navigate to Webserv and run `make`

		cd Webserv/lvl_5_webserv
		make
- Run webserv

		./webserv <config_file>
		or
		./webserv
		which is the same as:
		./webserv config/default.conf

- Open Firefox and search for localhost:8080

###  Subject (v20.4): [webserv en_subject](./extras/en.subject_webserv.pdf)

<h4>
  Makefile commands:
</h4>

`make` or `make all` - compiles webserv  
`make clean` - wipes all object files  
`make fclean` - deletes webserv and all object files  
`make re` - fclean  + all  

---

<div align="center">
	<img src="https://user-images.githubusercontent.com/76601093/193692098-d4b16956-1dab-40b8-9aae-31b254efc5ee.jpg" width=340> <img src="https://github.com/RealMadnessWorld/Inception/assets/76601093/b9621474-0a34-4e08-be66-426ab97e8232">

</div>
