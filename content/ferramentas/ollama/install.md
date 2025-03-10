# Guia de Instalação Ollama

- Versão em Vídeo: [https://youtu.be/hCAJJ071WFA](https://youtu.be/hCAJJ071WFA)<br>

---
## Acesse o Site Oficial  

- Site Oficial: [https://ollama.com/](https://ollama.com/)  

Visite o site para obter informações sobre o Ollama e acessar os links de instalação.  

---
## Instale o Ollama no Seu Sistema 

### **Para Linux:**  
Execute o seguinte comando no terminal:  
```shell
curl -fsSL https://ollama.com/install.sh | sh
```  

### **Para Windows/MacOS:**  
Baixe o instalador diretamente do site oficial e siga as instruções.  

---
## Verifique a Instalação

```shell
ollama
```  
Se tudo estiver certo, o terminal exibirá informações sobre o Ollama.  

---
## Executando um Modelo no Ollama  

Agora, você pode escolher um modelo para rodar. O comando básico para rodar um modelo é:  
```shell
ollama run <modelo>
```  

Exemplo:  
```shell
ollama run deepseek-r1:1.5b
```  

**Observação:** Se o modelo ainda não estiver instalado, o Ollama o baixará automaticamente antes de executá-lo.  

---
## Comandos Essenciais do Ollama

Aqui estão alguns comandos úteis para gerenciar modelos no Ollama:  

**Listar Modelos Instalados**  
```shell
ollama list
```  

**Baixar um Modelo Específico**  
```shell
ollama pull <modelo>
```  
O comando *pull* faz o download manual de um modelo antes do uso. Exemplo:  
```shell
ollama pull deepseek-r1:1.5b
```  

---
## Próximos Passos - VSCode e Python  

Nos próximos tutoriais, veremos como integrar o Ollama ao **VSCode** e usá-lo com **Python** para criar aplicações com IA.  
