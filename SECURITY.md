# Política de Segurança

## Objetivo

Este repositório reúne documentação técnica e evidências sanitizadas de laboratórios realizados em ambientes temporários da AWS.

Nenhuma credencial ou informação sensível deve ser necessária para compreender ou reproduzir os conceitos apresentados.

## Dados que não devem ser publicados

* chaves de acesso, senhas, tokens ou secrets;
* arquivos `.env` ou arquivos de configuração com credenciais;
* identificadores completos de sessões;
* URLs temporárias de autenticação;
* cookies e cabeçalhos de autorização;
* endereços de e-mail ou outros dados pessoais;
* chaves privadas, certificados ou arquivos de credenciais;
* informações que permitam acesso a contas ou recursos AWS.

## Tratamento das evidências

Antes de adicionar capturas de tela, logs ou arquivos ao repositório:

1. revisar toda a imagem ou conteúdo;
2. ocultar credenciais e informações pessoais;
3. remover URLs e identificadores temporários;
4. confirmar que nenhum segredo aparece no histórico do Git;
5. publicar somente a parte necessária para comprovar o laboratório.

IDs de recursos temporários podem aparecer quando forem necessários para explicar a arquitetura e não fornecerem acesso ao ambiente.

## Ambientes utilizados

Os recursos apresentados foram criados em ambientes educacionais e temporários da AWS.

As evidências deste repositório não representam uma infraestrutura de produção e não devem conter credenciais válidas ou recursos ativos.

## Correção de exposição acidental

Caso uma informação sensível seja publicada:

1. revogar ou substituir imediatamente a credencial;
2. remover o conteúdo do arquivo;
3. apagar o dado de todo o histórico do Git;
4. revisar commits, logs e capturas relacionadas;
5. registrar as ações corretivas realizadas.

Apagar o segredo somente em um novo commit não é suficiente, pois ele continuará disponível no histórico anterior.

## Relato de problemas

Se você identificar alguma informação sensível ou risco de segurança neste repositório, não abra uma issue pública contendo os dados encontrados.

Entre em contato diretamente com o responsável pelo repositório por meio dos canais disponibilizados em seu perfil do GitHub.
