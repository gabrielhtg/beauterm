# Cara Membuat Terminal Linux Lebih Elegan dan Banyak Fitur

## Preview

![ss](Screenshot%20from%202022-04-15%2012-47-56.png) <br>
![ss1](Screenshot%20from%202022-04-15%2012-52-46.png) <br>
![ss2](Screenshot%20from%202022-04-15%2012-55-37.png) <br>

## How to make it?

Pertama-tama, kalian harus memiliki zsh untuk menggantikan bash. Dalam kasus ini saya menggunakan Arch Linux. Berikut langkah-langkah yang harus kalian lakukan.
1. Ketikkan `sudo pacman -S zsh`
2. Buat zsh menjadi shell default kalian. `chsh -s $(which zsh)`
3. Restart terminal.
4. Ketikkan `echo $SHELL`. Apabila zsh sudah terpasang, seharusnya akan keluar output seperti berikut `/usr/bin/zsh`
5. Pasang Oh My Zsh dengan mengetikkan
   ```
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
   ```
6. Pasang PowerLevel10k dengan cara clone dari repo berikut
   ```
    git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
   ```
7. Install Nerd Patched Fonts. Kalian bisa mendownloadnya dari <button><a href="https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/FiraMono/Regular/complete/Fura%20Mono%20Regular%20Nerd%20Font%20Complete.otf?raw=true">sini</a></button>. Kalian juga pasang FiraMono Fonts untuk terminal gnome. Untuk memasang FaraMono font, bisa kalian cek google. Karena itu tergantung pada distro linux yang kalian gunakan. Untuk arch `yay -S nerd-fonts-complete`.
8. Clone juga repo ini
   ```
    git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
   ```
9. Edit `.zshrc` kalian untuk menggunakan fitur-fitur yang sudah kita download sebelumnya. Atau kalian bisa langsung [download .zshrc disini](.zshrc). Simpan file itu di folder home.
10. Ganti font terminal kalian menggunakan nerd font yang sudah di install sebelumnya.
11. Restart terminal kalian.
12. Setelah itu akan muncul seperti berikut.
    [p10k](Screenshot%20from%202022-04-15%2013-19-06.png) <br>
    Silakan kalian configure sesuai selera kalian.
13. Apabila tampilan seperti di langkah 12 tidak muncul, ketikkan `p10k configure`. Nanti akan muncul tampilan configurasinya.

Selamat mencoba :smile:

## <b>About Me</b>

I'm a student at Del Institute of Technology. <br>
Bachelor of Informatics study program. <br>


<button><a href="https://www.instagram.com/gabrielhtg77/">My Instagram</a></button>
<br>
<button><a href="https://www.del.ac.id/">Institut Teknologi Del</a></button>
