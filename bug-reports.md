#  Bug Reports

---

## BUG001 - Sessão não persistida após refresh

**Passos:**
1. Acessar login
2. Inserir credenciais válidas
3. Clicar em login
4. Pressionar F5

**Resultado atual:**
Usuário é deslogado

**Resultado esperado:**
Sessão deveria ser mantida

**Severidade:** Média

---

## BUG002 - Tentativas ilimitadas de login

**Passos:**
1. Inserir senha inválida várias vezes
2. Clicar em login repetidamente

**Resultado atual:**
Sistema permite tentativas ilimitadas

**Resultado esperado:**
Sistema deveria limitar tentativas ou bloquear temporariamente

**Severidade:** Alta
