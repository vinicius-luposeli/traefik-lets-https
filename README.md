# traefik-lets-https
Repo para guardar arquivos do proxy reverso traefik, um pouco melhorado.

Contem:
    - Redirecionamento de HTTP para HTTPS
    - Geração de certificado com Letsencrypt
    - Integração dos certificados com o Godaddy
    - Utilização dos secrets para passar secret e key da API
    - Armazenamento via NFS para os certificados do LetsEncrypt
    - Comentado mas tem como criar o certificado para o dominio coringa