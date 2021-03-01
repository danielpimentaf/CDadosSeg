# Exploração de Dados

- Que tipos de dados você tem, majoritariamente (atributos numéricos, textuais)?
O banco possui somente atributos númericos
- Qual seu objetivo com esse dataset?
O objetivo do dataset é identificar Phishing Websites
- Seu dataset é rotulado de que maneira?
O dataset é rotulado de forma binária (1 (Legitimate Website) e -1 (Phishing Website))
- Como é a distribuição dos dados do dataset?
Os resultados encontram-se no notebook (exploração.ipynb)
- Quais colunas/atributos você julga ser interessante manter e remover? Por quê?
Cada atributo comporta-se como um classificador baseado em heurística, portanto mediu-se a acurácia, f1-score e coeficiente de Matthews para cada atributo para se decidir se mantém ou não o atributo (detalhes no exploração.ipynb) <br> 
Manter: Prefix_Suffix, having_Sub_Domain, SSLfinal_State, Request_URL, URL_of_Anchor, Links_in_tags, SFH, web_traffic, Page_Rank, Google_Index, 
<br>
Remover: having_IP_Address, URL_Length, Shortining_Service, having_At_Symbol, double_slash_redirecting, Domain_registeration_length, Favicon, port, HTTPS_token, Submitting_to_email, Abnormal_URL, Redirect, on_mouseover, RightClick, popUpWidnow, Iframe, age_of_domain, DNSRecord, Links_pointing_to_page, Statistical_report
