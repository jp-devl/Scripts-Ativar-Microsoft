<p align="center">
  <img src="https://raw.githubusercontent.com/jp-devl/Scripts-Ativar-Microsoft/main/logo-img.jpeg" alt="MAS Logo" width="180">
</p>


<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Ativador de código aberto para Windows e Office com métodos de ativação por HWID, Ohook, TSforge e KMS online, além de recursos avançados de solução de problemas.</p>

<hr>

## Como ativar o Windows / Office / Atualizações Estendidas (ESU)?

### Método 1 - PowerShell ⚡


1. **Abra o PowerShell**

Clique no **Menu Iniciar**, digite `PowerShell` e abra-o.

2. **Copie e cole o código abaixo e pressione Enter.**

  - Para **Windows 8, 10 e 11**: 📌
  ```
  irm https://get.activated.win | iex
  ```
  Se o método acima estiver bloqueado (pelo seu provedor de internet/DNS), tente este (requer Windows 10 ou 11 atualizado):
  ```
  iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
  ```
  - Para **Windows 7** e versões posteriores:
  ```
  iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))
  ```

- **O script não está sendo executado? Use o Método 2 listado abaixo.**

3. O menu de ativação será exibido. **Escolha as opções destacadas em verde** para ativar o Windows ou o Office.

4. **Pronto!**

---

### Método 2 - Tradicional (Windows Vista e posterior) 🏛️

1. Baixe o script: [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) ou o [arquivo ZIP completo](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip).
2. Execute o arquivo chamado `MAS_AIO.cmd`.
3. Você verá as opções de ativação. Siga as instruções na tela.
4. Pronto!

---

> [DICA]
> - Alguns ISPs/DNS bloqueiam o acesso aos nossos domínios. Você pode contornar isso ativando o [DNS sobre HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) no seu navegador.
> - **Está com problemas**❓Visite a [página de solução de problemas](https://massgrave.dev/troubleshoot) ou abra uma solicitação no [GitHub](https://github.com/jp-devl/Scripts-Ativar-Microsoft/issues).

---

- Para ativar produtos adicionais como **Office para macOS, Visual Studio, CALs de RDS e Windows XP**, consulte [aqui](https://massgrave.dev/unsupported_products_activation).
- Para executar os scripts em modo não interativo, consulte [aqui](https://massgrave.dev/command_line_switches).

---

> [NOTE]
>
> - O comando IRM no PowerShell baixa um script de um URL especificado e o comando IEX o executa.
> - Sempre verifique o URL antes de executar o comando e verifique a origem se estiver baixando arquivos manualmente.
> - Tenha cuidado, pois alguns espalham malware disfarçado de MAS usando URLs diferentes no comando IRM.

---


```
Última versão: 3.9
Data de lançamento: 19/11/2025
```

### [Download Original Windows & Office](https://massgrave.dev/genuine-installation-media)

<div align="center">

[![1.1]][1]

</div>

<div align="center">
  


</div>

[1.1]: https://massgrave.dev/img/logo_github.png (GitHub)


[1]: https://github.com/jp-devl/Scripts-Ativar-Microsoft


---

<p align="center">Obrigado ❤️</p>

