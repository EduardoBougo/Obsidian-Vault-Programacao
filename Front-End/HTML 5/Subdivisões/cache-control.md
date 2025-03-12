![[Pasted image 20250218174428.png#center | 700]]

Define diretivas para o controle de cache da página.

Evita o armazenamento em cache da página, garantindo que o navegador sempre busque a versão mais recente do conteúdo a partir do servidor. O uso dessas instruções é especialmente útil quando se deseja assegurar que os usuários sempre vejam a versão mais atualizada de uma página, sem depender do cache do navegador.

Atributos:

- "~={yellow}**no-cache**=~": Indica que o navegador não deve armazenar em cache uma versão temporária da página.
- "~={yellow}**must-revalidate**=~": Instrui o navegador a revalidar a página antes de utilizá-la a partir do cache, garantindo que a versão armazenada seja a mais recente.
- "~={yellow}**post-check=0, pre-check=0**=~": Especifica o comportamento do cache para os navegadores que suportam os cabeçalhos HTTP post-check e pre-check.
  


