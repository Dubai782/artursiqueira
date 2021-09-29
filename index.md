## Artru Siqueira

Meu perfil do [GitHub](https://github.com/Dubai782/artursiqueira/edit/gh-pages/index.md), onde podera ver meus projetos da faculdade e tstes.
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Recursividade

  Faça uma função recursiva que calcula a divisão usando subtrações sucessivas:
int divisao (int numerador, int denominador)
Faça um programa principal que leia dois números, acione a função e exiba o resultado
gerado.

```markdown

#include <stdio.h>
#include  <math.h>

int main(void)
{
    int n = 1; // Variável n = numerador
    int d = 1; // Variável d = denominador

    printf("Digite o numerador: \n");
    scanf("%d", &n);
    printf("Digite o denominador: \n");
    scanf("%d", &d);

    n = n/d;
    printf("O resultado gerado pela divisao dos numeros foi %d \n",n); // Antes tinha colocado mai uma varável, mas depois vi que não precisava.
    return 0;
}
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Dubai782/artursiqueira/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
