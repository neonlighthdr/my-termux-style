```bash
# Clone repo-nya
git clone https://github.com/neonlighthdr/my-termux-style.git

# Hapus folder .termux lama, ganti dengan yang baru dari repo ini
rm -rf .termux && cp -rf my-termux-style/.termux ../home/ && rm -rf my-termux-style && exit
