
## 📌 Instruções  

1. **Faça um Fork deste repositório**;  

2. **Clone o repositório localmente**:  
   ```sh
   git clone https://github.com/SEUUSERNAME/dio-lab-open-source.git
   ```  

3. **Adicione o remote upstream para manter seu repositório local atualizado**:  
   ```sh
   git remote add upstream https://github.com/digitalinnovationone/dio-lab-open-source.git
   ```  
   Para baixar e mesclar as alterações do repositório original, utilize:  
   ```sh
   git pull upstream main
   ```  
   Ou, para apenas baixar sem mesclar:  
   ```sh
   git fetch upstream main
   ```  
   Veja mais em: ["Primeiros Passos com Git e GitHub"](https://www.dio.me)  

4. **Crie uma nova branch** e nomeie como `feat/community/seunomedeusuario` :  ` git checkout -b feat/community/seunomedeusuario`
   Exemplo:  
   ```sh
   git checkout -b feat/community/falvojr
   ```  

6. **Dentro da pasta "community", crie um arquivo em Markdown (`.md`)** e nomeie com o mesmo nome do seu usuário no GitHub. Exemplo:  
   ```sh
   community/falvojr.md
   ```  

7. **Desenvolva o seu perfil**:  
   - Veja exemplos na pasta **"community"**;  
   - Adicione alguns dos utilitários presentes na pasta **"utils"**;  
   - **Atenção:** Use os outros exemplos como inspiração, **não copie**!  

8. **Adicione suas alterações à "staging area"**:  
   ```sh
   git add community/seunomedeusuario.md
   ```  

9. **Crie um commit com uma mensagem indicando a adição do seu perfil**:  
   ```sh
   git commit -m "feat: add seunomedeusuario profile"
   ```  

10. **Envie as alterações para o seu repositório remoto**:  
   ```sh
   git push origin feat/community/seunomedeusuario
   ```  

11. **Crie um Pull Request** no GitHub e pronto! 🚀  

