# scraperSpiders
The name said it all. i Use some tech as python crawlers, wget tool, javascript and web sites like webscraper.io. But ... why, why? the curious boy asked me. -Well, i am learning and evolving. 

Since while i was looking in some frameworks as BS4 python and getting to know the use affairs of it. Each website is unique and there are a lot os customizations inside the code to get exactly what i want. I understood that and start to save on my machine the standart ctrl+u html code, file it and just grab the strings i want... tsc, tsc ... Well, it a process. Learning curve from hell. (get the reference ??) 

Once upon a time...
The most basic search is google and its dorks. There are tons of it. how cool is to find some specific pdf about programming language? Most of are all out dated, but some techs never change, like Latin. If u want to learn cobol, mainframes, assembly, programming logic, algorithms, etc. You got it, Babe!! If you are lucky, most recent information about anything you want. 

intitle:index.of?pdf|txt|docx|odt|csv webscraping is just an example. PS: use in chrome|firefox|etc search bar. 

I just needed some samples to populate my oracle database, for my simulations. 
Simulation of what? Well. Lets suppose there is an e-commerce hanging around in some web server (old school). 
All the transactions have infos. that i can simulate. Can use dockers, vms, VPN´s and all that things. 
But, for now, i won´t go too far. My point is to show to employees what i can do ultimately 

WGET thing: 

wget.exe -r -nv --no-check-certificate --spider https://www.dicionariodenomesproprios.com.br/nomes-femininos/1/

I used a spider to get all links from this website https://www.dicionariodenomesproprios.com.br/nomes-femininos/1/
Recursive mode and all. I picked up over 8000 first different names in a single column text file. To import. 

Notice that i am using windows powershell. I love linux and it really would make it easy for me just use shell script. 
But right now, my linuxes installations are all in vm´s. I gotta know the performance when scraping something. 
The main reason to use wget spider is the website´s structure. All the names are part of the URL. No need to dive deep 
inside selectors, elements, attributes and all. I will hold my breath and dive down in due time. Promisse. For now, i do have 
the file, the table to receive this data through sql*loader or even compiling sql script with insert command. 

There is another data that i have to get. The brazilian social security number or as we call CPF. Fortunately, i can solve this puzzle 
with an algorithm. I will make pl/sql from inside oracle and run a for loop to separate a valid cpf within a range of number. I imagine 
this is not the best approach. It can cost computer resources. I´ll think about it later. 

