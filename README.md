<p align="center">
  <img src="https://github.com/hildocosta/hildocosta-Curso-Java--Nelio-Alves/blob/main/logo.png" width="300">
</p>

<h1 align="center">📂 Explorando Manipulação de Pastas em Java</h1>

<p>🔥 Bem-vindo ao repositório dedicado à exploração da manipulação de pastas (diretórios) na linguagem de programação Java. Aqui, você encontrará informações e exemplos práticos sobre como usar a classe File para criar, renomear, mover e excluir pastas em seus programas Java.</p>

<p>🎓 Este repositório é voltado para estudantes e desenvolvedores que desejam aprender como manipular pastas de forma eficiente e prática em Java. Aqui, você encontrará explicações detalhadas, exemplos de código e exercícios para aprimorar suas habilidades de manipulação de arquivos e pastas.</p>

<p>💡 Ao explorar a manipulação de pastas em Java, você aprenderá como criar, renomear, mover e excluir pastas usando a classe File. Essa classe fornece métodos simples e eficazes para trabalhar com diretórios, permitindo que você gerencie suas pastas de forma fácil e rápida.</p>

<h2 align="center">🔒 Licença</h2>

<p>⚖️ Este projeto está licenciado sob a <a href="LICENSE">Licença MIT</a>.</p>

<h2 align="center">📧 Contato</h2>

<h3>🔗 Redes Sociais e Contato</h3>

<ul>
  <li>📌 GitHub: <a href="https://github.com/example">example</a></li>
  <li>💼 LinkedIn: <a href="https://www.linkedin.com/in/example/">Example Name</a></li>
  <li>✉️ Email: example@example.com</li>
</ul>

<p>Agora que estamos preparados, vamos explorar como manipular pastas em Java!</p>

<h2 align="center">🚀 Vamos Começar</h2>

<h3>🔥 Manipulação de Pastas em Java</h3>

<p>Para manipular pastas em Java, você pode usar a classe File. Ela permite criar, renomear, mover e excluir pastas de forma eficiente. Veja um exemplo de código para criar uma pasta em Java:</p>

```java
import java.io.File;

public class Main {

    public static void main(String[] args) {
        
        // Caminho da nova pasta a ser criada
        String caminhoPasta = "caminho/da/nova/pasta";
        
        // Instancia um objeto File representando a nova pasta
        File pasta = new File(caminhoPasta);
        
        // Tenta criar a nova pasta
        if (pasta.mkdirs()) {
            System.out.println("Pasta criada com sucesso!");
        } else {
            System.out.println("Falha ao criar a pasta.");
        }
    }
}
```

<p>Este código cria uma nova pasta no caminho especificado. Você pode adaptar esse exemplo para renomear, mover ou excluir pastas, utilizando os métodos apropriados da classe File.</p>

<p>Agora que você entende como manipular pastas em Java usando a classe File, experimente criar e manipular suas próprias pastas para praticar e aprimorar suas habilidades!</p>
