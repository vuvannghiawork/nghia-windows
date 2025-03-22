# CaiLaiWinLaptopCongTy

- Chỉnh lại múi giờ thời gian
- Chỉnh lại hiển thị đuôi file và hiện file ẩn
- Chỉnh lại TaskBar: icon search + thời tiết
- Thêm Vân tay + Không thêm face id

##

- Chrome
- Winrar
- Everything
- Postman
- DBeaver
- VSCode + Cursor

ngrok: https://dashboard.ngrok.com/get-started/setup/windows

```bash
ngrok config add-authtoken   xxxxxxxxxxxxxxxxxxx
ngrok http 8000
```

- Git
  <!-- C:\Program Files\Git\usr\bin -->
  <!-- + tree  -->
  <!-- tree-1.5.2.2-setup.exe -->
  <!-- jq -->
  <!-- https://github.com/jqlang/jq/releases/latest/download/jq-win64.exe -->
  <!-- Gợi ý -->
  <!-- curl -o ~/.git-completion.bash https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash -->
  <!-- source ~/.git-completion.bash -->
  <!--  -->

```bash
if [ -f ~/.git-completion.bash ]; then
    source ~/.git-completion.bash
fi

_git_checkout() {
    local cur=${COMP_WORDS[COMP_CWORD]}
    local -a prefixes=(main develop feature bugfix release)
    COMPREPLY=($(compgen -W "${prefixes[*]}" -- "$cur"))
}
complete -F _git_checkout 'git checkout -b'


source ~/.bashrc
```

Cấu hình:

```bash
git --version
git config --global user.email "nghiavv@xtransform.vn"
git config --global user.name "Vu Van Nghia"
git config --global core.editor "code --wait"
git config --global pull.rebase true
git config --global pull.autostash true
git clone https://github.com/vuvannghiawork/nghia-windows
git clone https://github.com/vuvannghiawork/nghia-clone-github
```

Cài đặt Docker

```bash
wsl --install

docker --version
docker compose -f docker-compose.yml up -d
```

python

<!-- Add to PATH -->
<!-- python --version -->
<!-- ms-python.python -->
<!-- Thử dùng python hello.py -->

<!-- Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Apps > Advanced app settings > App execution aliases. -->
<!-- https://stackoverflow.com/questions/65348890/python-was-not-found-run-without-arguments-to-install-from-the-microsoft-store -->
<!-- Thử lại python hello.py -->

Tải xuống giọng nói tiếng Việt + Kích hoạt file tiếng Việt

java: jdk + maven
amazon-corretto-21.0.6.7.1-windows-x64
IntelliJ IDEA 2024.3.3

<!-- Cài đặt Java + IntelliJ IDEA 2023.3.2 -->
<!-- Cài đặt Java -->
<!-- https://aws.amazon.com/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc -->
<!-- java --version -->
<!-- Cài đặt maven -->
<!-- Cài đặt IntelliJ -->
<!-- git clone https://github.com/vuvannghiawork/api -->

FDM
SubtitleEdit-4.0.11-Setup
ffmpeg-master-latest-win64-gpl-shared

<!-- Tạo folder NghiaGithub -->
<!-- Tạo folder **Link** -->
<!-- Thêm link Startup -->
<!-- Tạo StartupCopy -->
<!-- Thêm link Screenshots -->

<!-- Lỗi tạo link windows home bật chế độ Developer   -->
<!--Win 11 https://www.youtube.com/watch?v=-2rXAzGgpJA -->
<!-- Win 10   https://www.youtube.com/watch?v=nw1wMabaMx4 -->

<!-- nghia-git-auto-commit -->
<!-- nghia-windows-manager-screenshots -->
<!-- nghia-vscode -->
<!-- nghia-windows-autohotkey -->
<!-- nghia-windows-unikey -->

<!-- nghia-docker-compose -->

<!-- Java -->

Cấu hình trả thông tin khi bị lỗi validate + lỗi chương trình
Java realtime webflux = camera kiểu gì đó

<!-- Github có các quản lý + Git 5 nhánh + Xem thêm git main develop feature bugfix release; -->

<!--Xem VIDEO Reset index + Bạn có chắc k -->
<!--Học  tele bot -->
