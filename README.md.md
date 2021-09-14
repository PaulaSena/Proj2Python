# Automação Web com Python + Selenium

Objetivo entrar no site da maquagine luiza e 

ri.magazineluiza.com.br

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled.png)

pyautogui

[Jupyter e Anaconda](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Jupyter%20e%20Anaconda%20e3475196068e401e90ffcc75129ce583.md)

[Instalando o Selenium](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Instalando%20o%20Selenium%2066e5b02101424f179a7ba164045351a7.md)

[Baixando o WebDriver](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Baixando%20o%20WebDriver%20795ce1ef85304046a260a33e3553720b.md)

# Importando Selenium

from selenium import webdriver // Da biblioteca selenium import Webdriver

navegador = webdriver.Chrome() // Abrir navegador  ou Firefox

Clik em Run

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%201.png)

Abrira o navegador Chrome

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%202.png)

### Abrindo o Site  ri.magazineluiza.com.br

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%203.png)

navegador.get("[https://ri.magazineluiza.com.br/](https://ri.magazineluiza.com.br/)")

# Localizando um elemento na pagina

navegador.find_element_by_xpath()

Selenium Python

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%204.png)

Inspecionar elemento selecionar icone com seta e copiar o xpath

//*[@id="owl-destaques"]/div[1]/div/div[4]/div/a/p

![xpath.png](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/xpath.png)

navegador.find_element_by_xpath('//*[@id="owl-destaques"]/div[1]/div/div[4]/div/a/p')

![xpath2.png](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/xpath2.png)

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%205.png)

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled%206.png)

Clique aqui para fazer o download

Xpath = //*[@id="bWtQ7n6RcQdDDDCgCcH3yg=="]

from selenium import webdriver

navegador = webdriver.Chrome()

navegador.get("[https://ri.magazineluiza.com.br/](https://ri.magazineluiza.com.br/)")
navegador.find_element_by_xpath('//*[@id="owl-destaques"]/div[1]/div/div[4]/div/a/p').click()
navegador.find_element_by_xpath('//*[@id="bWtQ7n6RcQdDDDCgCcH3yg=="]').click()

## 

![Untitled](Automac%CC%A7a%CC%83o%20Web%20com%20Python%20+%20Selenium%20fc0186ddd468481db35d7ef6f90b9ddf/Untitled.gif)

# Sucesso 🤩