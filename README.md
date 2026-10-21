# 1. Update & install dependency
pkg update && pkg upgrade -y
pkg install python whois curl git -y

# 2. Clone repo
git clone https://github.com/hai123455/phishdox.git

# 3. Masuk folder
cd phishdox

# 4. Test jalan
python phishdox.py "https://bitly.cx/Penerimabansostahap3_tahun2026"
