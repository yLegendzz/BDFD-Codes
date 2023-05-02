$c[Comando deve estar no BDScript 2.]
$c[troque APIKEY abaixo pela sua key da OpenAI. veja esse vídeo para saber como pegar sua key: https://youtu.be/VFBzh4YPOpU]

$var[key;APIKEY]

$nomention
$reply
$botTyping

$var[mensagem;$replaceText[$replaceText[$message;";';-1];
; ;-1]]

$argsCheck[>1;> **Informe alguma pergunta para o chatgpt!**]

$title[Chat GPT 3.5]
$color[9A81FF]
$httpAddHeader[Content-Type;application/json]
$httpAddHeader[Authorization;Bearer $var[key]]
$httpPost[https://api.openai.com/v1/chat/completions;{
   "model": "gpt-3.5-turbo",
   "max_tokens": 700,
   "temperature": 0,
   "top_p": 1,
   "n": 1,
   "messages": [{"role": "user", "content": "$var[mensagem]"}\]
}]

$if[$httpResult[error;message]==You exceeded your current quota, please check your plan and billing details.]
$description[Olá, se você está vendo esta mensagem então o dono do comando colocou uma Chave que não possui créditos na OpenAI, você pode comprar créditos no mesmo site que criou a key.
*OBS: antigamente a OpenAI dava uma quantia de créditos gratuito para usar, atualmente acho que isso não acontece mais.*]
$elseif[$httpResult[error;message]==Incorrect API key provided: $var[key]. You can find your API key at https://platform.openai.com/account/api-keys.]
$description[a key adicionada ao comando está errada.

$httpResult[error;message]]
$else
$description[$httpResult[choices;0;message;content]]
$endif
