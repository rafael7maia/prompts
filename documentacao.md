# Prompt para Documentação Técnica Pragmática

Crie documentação técnica seguindo este padrão minimalista e pragmático:

## Princípios

1. **Zero redundância**: Cada informação aparece apenas uma vez
2. **Ação sobre explicação**: Mostre código/comandos diretos ao invés de descrever o que fazer
3. **Exemplos reais**: Use casos concretos ao invés de placeholders genéricos
4. **Sem adornos**: Nada de emojis, tabelas, checkmarks ou elementos visuais decorativos
5. **Humanizado e profissional**: Tom técnico mas acessível, como se um desenvolvedor experiente estivesse explicando para outro

## Estrutura

### Título e descrição
- Título claro e direto
- Uma única frase descrevendo o objetivo da ferramenta/projeto

### Instalação
- Apenas comandos necessários
- Sem numeração de passos
- Sem explicações óbvias ("isso irá...", "após executar...")

### Configuração
- Comandos direto ao ponto
- Instruções breves apenas onde essencial
- Formatos e permissões em bullets simples

### Sintaxe
- Um único exemplo da estrutura do comando
- Sem múltiplas variações
- Use placeholders descritivos em CAPS

### Exemplo
- Um caso real e concreto
- Prefira dados reais a genéricos
- Sem repetir a sintaxe explicada antes

### Troubleshooting
- Apenas erros comuns que você realmente enfrentou
- Formato: "Erro X" → código correto vs incorreto
- Comentários inline ao invés de parágrafos explicativos
- Remova textos como "certifique-se", "ocorre quando", "isso significa"

### Rodapé
- Link da documentação oficial
- Sem seção separada se for apenas um link

## Anti-padrões (evitar)

❌ Tabelas formatadas (use listas ou código comentado)
❌ Emojis e ícones (📝 ✅ ❌ 🚀)
❌ Seções "Observações importantes" genéricas
❌ Textos explicativos óbvios
❌ Múltiplos exemplos da mesma coisa
❌ Informações duplicadas em seções diferentes
❌ Introduções longas sobre contexto
❌ Listas de requisitos detalhadas (só o essencial)

## Exemplo de tom

**Ruim:** "Antes de realizar a migração definitiva, é uma boa prática executar o modo de relatório para verificar exatamente o que será migrado"

**Bom:** "Visualizar sem migrar: adicione `-report`"

**Ruim:** "O erro 'invalid project' ocorre quando o formato do repositório está incorreto."

**Bom:**
```bash
# Correto
-github-repo=org/repo

# Incorreto  
-github-repo=repo
