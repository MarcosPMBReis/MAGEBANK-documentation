# Guia de Branches e Boas Práticas

Este documento descreve a estrutura recomendada de branches e as boas práticas para o uso de branches no nosso projeto.

## Estrutura de Branches

- **Branch Principal**
  - **Nome:** `main`
  - **Descrição:** Contém o código estável e pronto para produção.

- **Branches de Desenvolvimento**
  - **Nome:** `develop`
  - **Descrição:** Usada para integrar novas funcionalidades e melhorias em desenvolvimento.

- **Branches de Funcionalidade**
  - **Nome:** `feature/nome-da-feature`
  - **Descrição:** Criadas para o desenvolvimento de novas funcionalidades específicas. Cada branch representa uma funcionalidade isolada.

- **Branches de Correção de Bugs**
  - **Nome:** `fix/nome-do-bug`
  - **Descrição:** Utilizadas para corrigir bugs e problemas identificados no código. Cada branch aborda um problema específico.

- **Branches de Hotfix**
  - **Nome:** `hotfix/nome-do-hotfix`
  - **Descrição:** Usadas para corrigir problemas críticos em produção rapidamente. Estas são correções urgentes.

- **Branches de Release**
  - **Nome:** `release/nome-da-release`
  - **Descrição:** Criadas para preparar novas versões do software. Serve para testes finais e ajustes antes de liberar a versão para produção.

## Boas Práticas com Branches

1. **Crie Branches de Forma Clara e Descritiva**
   - Nomeie suas branches de forma a refletir claramente o propósito da alteração.

2. **Mantenha Branches Pequenas e Focadas**
   - Cada branch deve se concentrar em uma única tarefa ou funcionalidade para facilitar a revisão e integração.

3. **Atualize Regularmente**
   - Atualize suas branches com as últimas mudanças da branch `main` para evitar conflitos.

4. **Faça Commits Frequentes e Significativos**
   - Realize commits pequenos e frequentes, com mensagens claras sobre as alterações realizadas.

5. **Use Pull Requests para Integração**
   - Sempre use pull requests para mesclar branches na `main` ou em `dev`. Isso permite revisão e testes antes da integração.

6. **Revise o Código**
   - Revise o código de pull requests de outros membros da equipe e forneça feedback construtivo.

7. **Elimine Branches Antigas**
   - Após a integração de uma branch, exclua-a para manter o repositório limpo e organizado.

8. **Proteja Branches Importantes**
   - Configure regras de proteção para branches críticas, como `main` e `dev`, para evitar alterações não autorizadas.

## Como Contribuir

1. **Crie um Fork**: Faça um fork do repositório principal.
2. **Crie uma Nova Branch**: Crie uma nova branch para suas alterações.
   - Utilize a estrutura de branch apropriada para seu trabalho.
3. **Faça Alterações**: Implemente suas mudanças seguindo as boas práticas.
4. **Teste suas Alterações**: Verifique se suas alterações não introduzem novos problemas.
5. **Enviando Pull Request**: Envie um pull request para a branch `dev` ou `main` com uma descrição detalhada das suas alterações.

## Contato

Para mais informações, entre em contato com seu lider de equipe, ou com algum lider do projeto

---

Obrigado por seguir estas diretrizes e por contribuir para o sucesso do projeto!
