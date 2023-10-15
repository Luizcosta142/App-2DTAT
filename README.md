# App para visualização de dados (Streamlit)

1º passo: Instalar ambientes e criar pasta com arquivos necessários do projeto (requirements.txt + base de dados)
- Versão do python 3.10
- Baixar VSCODE.

2º passo: Criar ambiente virtual
python -m venv venv
Set-ExecutionPolicy Unrestricted -scope process
venv\Scripts\activate

2º passo: Instalar dependências
pip install -r requirements.txt
pip install streamlit

3º passo: Criar seu arquivo .py e começar a criar sua aplicação :)


Links úteis:

https://docs.streamlit.io/library/api-reference/widgets
https://www.alura.com.br/artigos/ambientes-virtuais-em-python
https://www.alura.com.br/artigos/streamlit-compartilhando-sua-aplicacao-de-dados-sem-dor-de-cabeca
https://blog.streamlit.io/deploy-a-private-app-for-free/


# Para esconder código notebook
from IPython.display import HTML

HTML('''<script>
code_show=true; 
function code_toggle() {
 if (code_show){
 $('div.input').hide();
 } else {
 $('div.input').show();
 }
 code_show = !code_show
} 
$( document ).ready(code_toggle);
</script>
<form action="javascript:code_toggle()"><input type="submit" value="Click here to toggle on/off the raw code."></form>''')
