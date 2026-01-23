pkg update && pkg upgrade -y && \
pkg install python libcurl openssl -y && \
pip install requests pycurl beautifulsoup4 fake-useragent
git clone https://github.com/Faizi73939/fb-cloning.git
cd fb-cloning
python fb-cloning.py
