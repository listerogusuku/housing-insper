# :cloud: **O (GIGANTESCO) UNIVERSO DA COMPUTAÇÃO EM NUVEM**

<!-- # :cloud: **AWS SERVELESS APPLICATION S3, LAMBDA, API GATEWAY E CLOUDWATCH** -->

<!-- - **Aluno:** Lister Ogusuku Ribeiro
- **Curso:** Engenharia de Computação
- **Semestre:** 6º
- **Contato:** listeror@al.insper.edu.br
- **Ano:** 2023 -->

<div align="center" style="max-width:300rem;">
<table>
<tr>
<th>Sobre o Desenvolvedor</th>
<th>Github</th>
</tr>
<tr>
<td>
<pre>
Aluno: Lister Ogusuku Ribeiro
Contato: listeror@al.insper.edu.br
Curso: Engenharia de Computação
Disciplina: Computação em Nuvem
Semestre: 6º (2023.1)
Profº: Rodolfo Avelino
Profº Auxiliar: Tiago Demay
</pre>
</td>
<td>

<div align="center" style="max-width:200rem;">
<table>
  <tr>
   <td align="center"><a href="https://github.com/listerogusuku"><img style="border-radius: 80%;" src="https://avatars.githubusercontent.com/listerogusuku" width="60px;" alt=""/><br /><sub><b>Lister Ogusuku</b></sub></a><br /><a href="https://github.com/listerogusuku" title="Lister Ogusuku Ribeiro"></a>Developer</td>

  </tr>
</table>
</div>

</td>
</tr>
</table>

</div>

<!--

## Começando

Para seguir esse tutorial é necessário: -->

<!--
- **Hardware:** DE10-Standard e acessórios
- **Softwares:** Quartus 18.01
- **Documentos:** [DE10-Standard_User_manual.pdf](https://github.com/Insper/DE10-Standard-v.1.3.0-SystemCD/tree/master/Manual) -->

<!-- ## :man: Desenvolvedor

<div align="center" style="max-width:68rem;">
<table>
  <tr>
   <td align="center"><a href="https://github.com/listerogusuku"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/listerogusuku" width="100px;" alt=""/><br /><sub><b>Lister Ogusuku</b></sub></a><br /><a href="https://github.com/listerogusuku" title="Lister Ogusuku Ribeiro"></a>Developer</td>

  </tr>
</table>
</div> -->

## :globe_with_meridians: O que é e para que serve a Computação em Nuvem?

A computação em nuvem é um modelo de tecnologia de informação que permite o acesso sob demanda a um conjunto compartilhado de recursos de computação, como servidores, armazenamento, aplicativos e serviços, por meio da internet. Em outras palavras, a computação em nuvem é uma **_forma de disponibilizar recursos computacionais através da internet, em vez de ter todos os recursos armazenados localmente em um único computador ou servidor._** Esses recursos são gerenciados e mantidos por provedores de serviços em nuvem, como a **_Amazon Web Services, Microsoft Azure e Google Cloud Platform._**

A computação em nuvem pode ser utilizada para diversas finalidades, como **_armazenar arquivos e documentos, hospedar aplicativos, desenvolver e testar software, processar dados em larga escala, entre outras._** A principal vantagem da computação em nuvem é que ela permite que as empresas e usuários finais utilizem recursos computacionais de forma flexível e escalável, sem precisar investir em infraestrutura de TI própria. Além disso, a computação em nuvem oferece maior disponibilidade e segurança de dados do que soluções locais, já que os provedores de serviços em nuvem costumam ter data centers redundantes e medidas de segurança avançadas para proteger os dados dos usuários.

![](https://pimages.toolbox.com/wp-content/uploads/2021/07/09134159/38-3.png)



<iframe width="1480" height="546" src="https://www.youtube.com/embed/M988_fsOSWo" title="Cloud Computing In 6 Minutes | What Is Cloud Computing? | Cloud Computing Explained | Simplilearn" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!-- === "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

Inserir vídeo:

- Abra o youtube :arrow_right: clique com botão direito no vídeo :arrow_right: copia código de incorporação:

<iframe width="630" height="450" src="https://www.youtube.com/embed/UIGsSLCoIhM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

!!! tip
Eu ajusto o tamanho do vídeo `width`/`height` para não ficar gigante na página

Imagens você insere como em plain markdown, mas tem a vantagem de poder mudar as dimensões com o marcador `{width=...}`

![](icon-elementos.png)

![](icon-elementos.png){width=200} -->

















<!-- # Getting started

Material for MkDocs is a theme for [MkDocs], a static site generator geared
towards (technical) project documentation. If you're familiar with Python, you
can install Material for MkDocs with [`pip`][pip], the Python package manager.
If not, we recommend using [`docker`][docker].

  [MkDocs]: https://www.mkdocs.org
  [pip]: #with-pip
  [docker]: #with-docker

## Installation

### with pip <small>recommended</small> { #with-pip data-toc-label="with pip" }

Material for MkDocs is published as a [Python package] and can be installed with
`pip`, ideally by using a [virtual environment]. Open up a terminal and install
Material for MkDocs with:

=== "Latest"

    ``` sh
    pip install mkdocs-material
    ```

=== "9.x"

    ``` sh
    pip install mkdocs-material=="9.*" # (1)!
    ```

    1.  Material for MkDocs uses [semantic versioning][^1], which is why it's a
        good idea to limit upgrades to the current major version.

        This will make sure that you don't accidentally [upgrade to the next
        major version], which may include breaking changes that silently corrupt
        your site. Additionally, you can use `pip freeze` to create a lockfile,
        so builds are reproducible at all times:

        ```
        pip freeze > requirements.txt
        ```

        Now, the lockfile can be used for installation:

        ```
        pip install -r requirements.txt
        ```

  [^1]:
    Note that improvements of existing features are sometimes released as
    patch releases, like for example improved rendering of content tabs, as
    they're not considered to be new features.

This will automatically install compatible versions of all dependencies:
[MkDocs], [Markdown], [Pygments] and [Python Markdown Extensions]. Material for
MkDocs always strives to support the latest versions, so there's no need to
install those packages separately.

---

:fontawesome-brands-youtube:{ style="color: #EE0F0F" }
__[How to set up Material for MkDocs]__ by @james-willett – :octicons-clock-24:
15m – Learn how to create and host a documentation site using Material for 
MkDocs on GitHub Pages in a step-by-step guide.

  [How to set up Material for MkDocs]: https://www.youtube.com/watch?v=Q-YA_dA8C20

---

__Tip__: If you don't have prior experience with Python, we recommend reading 
[Using Python's pip to Manage Your Projects' Dependencies], which is a really
good introduction on the mechanics of Python package management and helps you
troubleshoot if you run into errors.

  [Python package]: https://pypi.org/project/mkdocs-material/
  [virtual environment]: https://realpython.com/what-is-pip/#using-pip-in-a-python-virtual-environment
  [semantic versioning]: https://semver.org/
  [upgrade to the next major version]: upgrade.md
  [Markdown]: https://python-markdown.github.io/
  [Pygments]: https://pygments.org/
  [Python Markdown Extensions]: https://facelessuser.github.io/pymdown-extensions/
  [Using Python's pip to Manage Your Projects' Dependencies]: https://realpython.com/what-is-pip/

### with docker

The official [Docker image] is a great way to get up and running in a few
minutes, as it comes with all dependencies pre-installed. Open up a terminal
and pull the image with:

=== "Latest"

    ```
    docker pull squidfunk/mkdocs-material
    ```

=== "9.x"

    ```
    docker pull squidfunk/mkdocs-material:9
    ```

The `mkdocs` executable is provided as an entry point and `serve` is the 
default command. If you're not familiar with Docker don't worry, we have you
covered in the following sections.

The following plugins are bundled with the Docker image:

- [mkdocs-minify-plugin]
- [mkdocs-redirects]

  [Docker image]: https://hub.docker.com/r/squidfunk/mkdocs-material/
  [mkdocs-minify-plugin]: https://github.com/byrnereese/mkdocs-minify-plugin
  [mkdocs-redirects]: https://github.com/datarobot/mkdocs-redirects

??? question "How to add plugins to the Docker image?"

    Material for MkDocs only bundles selected plugins in order to keep the size
    of the official image small. If the plugin you want to use is not included, 
    create a new `Dockerfile` and extend the official Docker image:

    ``` Dockerfile
    FROM squidfunk/mkdocs-material
    RUN pip install ...
    ```

    Next, you can build the image with the following command:

    ```
    docker build -t squidfunk/mkdocs-material .
    ```

    The new image can be used exactly like the official image.

### with git

Material for MkDocs can be directly used from [GitHub] by cloning the
repository into a subfolder of your project root which might be useful if you
want to use the very latest version:

```
git clone https://github.com/squidfunk/mkdocs-material.git
```

The theme will reside in the folder `mkdocs-material/material`. After cloning
from `git`, you must install all required dependencies with:

```
pip install -e mkdocs-material
```

  [GitHub]: https://github.com/squidfunk/mkdocs-material -->
