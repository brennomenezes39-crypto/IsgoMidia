# IsgoMidia

Mídia pública da **IsGo! | Comunicação Digital** para publicação no Instagram.

## Por que este repositório existe

A API de publicação do Instagram **não aceita upload de arquivo**: ela busca a
imagem ou o vídeo por URL pública. Este repositório é público justamente para
que `raw.githubusercontent.com` sirva os arquivos sem autenticação, que é o
que a API precisa.

Só entra aqui mídia que já vai ao ar publicamente de qualquer forma. **Nada
privado, nada de cliente sem autorização, nenhuma credencial.**

## Organização

Uma pasta por post, nomeada `AAAA-MM-DD-assunto`. Dentro, os arquivos
numerados na ordem em que aparecem no carrossel.

## Formato

Do que a API aceita:

| | |
|---|---|
| Imagem | **JPEG**, até 8 MB, proporção entre 4:5 e 1.91:1 |
| Carrossel | 2 a 10 imagens, sem vídeo no meio |
| Vídeo | MP4 ou MOV, até 1 GB, de 3 s a 15 min |

## Como a URL é montada

```
https://raw.githubusercontent.com/brennomenezes39-crypto/IsgoMidia/main/<pasta>/<arquivo>
```
