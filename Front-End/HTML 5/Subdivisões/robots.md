![[Pasted image 20250216145818.png#center | 500]]

Esta meta tag controla o comportamento dos motores de busca em relação à indexação e ao rastreamento da página.

Com esta opção podemos dizer se os motores de busca podem ou não indexar o conteúdo da página e seguir os links nela contidos. É comumente usado para permitir ou não a indexação e rastreamento padrão.

###### - SERPs (Search Engine Results Page) - É a página que aparece quando um usuário realiza uma pesquisa na internet.

- ###### "~={yellow}**index**=~" Indexar a página. 
	- Permite que os motores de busca indexem o conteúdo da página.
	- **Nota:** Não é necessário usar a diretiva index se a diretiva noindex não for usada, o rastreador vai considerar a ausência de diretiva como uma instrução para indexar a página. 
- ###### "~={yellow}**noindex**=~" Não indexar a página e não mostrar nas SERPs
	- Não permite que os motores de busca indexem o conteúdo da página. Os links podem ser seguidos, mas a página não é indexada.
- ###### "~={yellow}**follow**=~" Seguir os links na página para descobrir outras páginas
	- Permite que os motores de busca sigam os links presentes na página.
- ###### "~={yellow}**nofollow**=~" Não seguir os links da página.
	- Não permite que os motores de busca sigam os links presentes na página.
- ###### "**~={yellow}all=~**" Um atalho para especificar (index, follow).
	- Valor padrão, significa “vazio”, o robô de busca não recebe nenhuma informação e portanto usa como diretivas index e follow.
- ###### "~={yellow}**none**=~" Um atalho para especificar (noindex, nofollow)
	- Os robôs podem ignorar a página e portanto usa como diretivas noindex e nofollow.
- ###### "~={yellow}**noarchive**=~" (Apenas GoogleBot). A página não é arquivada.


- ~={yellow}**index**=~ indexar a página 
- ~={yellow}**noindex**=~ (não indexar a página e não mostrar nas SERPs) 
- ~={yellow} **follow** =~(seguir os links na página para descobrir outras páginas) 
- ~={yellow}**nofollow**=~ (não seguir os links da página) 
- ~={yellow}**none**=~ (um atalho para especificar noindex, nofollow) 
- ~={yellow}**all**=~ (um atalho para especificar index, follow) 
- ~={yellow}**noimageindex**=~ (não indexar as imagens na página) 
- ~={yellow}**noarchive**=~ (não mostrar uma versão em cache da página nas SERPs) 
- ~={yellow}**nocache**=~ (é o mesmo que noarchive, mas apenas para MSN) 
- ~={yellow}**nositelinkssearchbox**=~ (não mostrar uma caixa de pesquisa para o seu site nas SERPs) 
- ~={yellow}**nopagereadaloud**=~ (não permitir que os serviços de voz leiam sua página em voz alta) 
-  ~={yellow}**notranslate**=~ (não mostrar traduções da página nas SERPs) 
-  ~={yellow}**unavailable_after**=~ (especificar um tempo após o qual a página não deve ser indexada)

###### Para saber mais sobre **robots**: https://pt.semrush.com/blog/robots-meta-tag-x-robots-tag/

