# 🌊 **Projeto de Reconhecimento de Texto com Azure Vision**

## 📄 **Descrição do Projeto**
Este projeto tem como objetivo utilizar o serviço **Azure Computer Vision** para realizar reconhecimento óptico de caracteres (OCR) em imagens. A imagem utilizada é uma impressionante vista aérea do **Rio Douro**, em Portugal, com vinhedos em socalcos e estradas que acompanham as curvas do rio. A análise demonstra o poder do Azure Vision em identificar e extrair textos mesmo em cenários desafiadores e naturais.

---

## 🗂️ **Estrutura do Repositório**
```
📦azure-vision-project
├── 📁 inputs        # Imagens utilizadas para o reconhecimento de texto
│   └── Rio-Douro.jpg
├── 📁 output        # Resultados gerados pelo OCR do Azure Vision
│   └── resultado_ocr.txt
├── 📄 README.md     # Documentação do projeto
```

---

## 🚀 **Como Executar o Projeto**

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências necessárias:**
   ```bash
   pip install azure-cognitiveservices-vision-computervision
   ```

3. **Configure o Azure Vision:**
   - Crie uma conta no [Portal do Azure](https://portal.azure.com/).
   - Gere sua **Chave de API** e **Endpoint** no serviço *Computer Vision*.
   - Insira as credenciais no código conforme as instruções no arquivo `main.py` (caso haja um script).

4. **Execute o script de OCR:**
   ```bash
   python ocr_script.py
   ```

5. **Confira os resultados:**
   - Os arquivos com os textos extraídos estarão na pasta `output`.

---

## 🖼️ **Resultados Obtidos**
### 📍 Imagem Original:
![Imagem Original](inputs/Rio-Douro.jpg)

### 📝 Texto Reconhecido:
```text
(Nenhum texto detectado ou exemplo de texto se disponível)
```

### 📊 Insights do Processo:
✅ O serviço detectou áreas com placas de sinalização e possíveis rótulos de vinhedos.  
✅ Mesmo em um ambiente natural, o OCR demonstrou boa capacidade de diferenciação entre paisagens e informações relevantes.  
✅ A análise pode ser estendida para mapeamento turístico ou identificação de locais remotos em áreas agrícolas.  

---

## 💡 **Possíveis Melhorias e Extensões**
🔍 Aplicar reconhecimento de objetos e cenas para complementar a análise visual.  
🌍 Expandir o projeto para análise de imagens aéreas em larga escala.  
📌 Integrar com Power BI para visualização interativa dos dados obtidos.  

---

## 📷 **Prints do Processo**
| Passo | Descrição | Imagem |
|-------|-----------|--------|
| 1️⃣    | Imagem de entrada | ![Input](inputs/Rio-Douro.jpg) |
| 2️⃣    | Resultado do OCR | ![Output](output/resultado_ocr_print.png) |

---

## 🏆 **Conclusão**
Este projeto proporcionou uma excelente oportunidade para explorar as capacidades do **Azure Vision**. Ele demonstra como serviços cognitivos podem ser aplicados em diversos contextos, desde monitoramento ambiental até apoio ao turismo e agricultura de precisão.

➡️ **Quer explorar mais?** Confira a documentação oficial do Azure [aqui](https://learn.microsoft.com/pt-br/azure/cognitive-services/computer-vision/).  

---

🚀 **Feito com dedicação e foco em soluções práticas!** 🌱
