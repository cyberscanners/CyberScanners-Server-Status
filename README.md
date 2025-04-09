# CyberScanners-Server-Status

# 𝐂𝐘𝐁𝐄𝐑 𝐒𝐂𝐀𝐍𝐍𝐄𝐑𝐒 𝐇𝐀𝐂𝐊𝐈𝐍𝐆 𝐓𝐄𝐑𝐌𝐔𝐗 𝐖𝐄𝐁 𝐒𝐄𝐑𝐕𝐄𝐑 𝐒𝐓𝐀𝐓𝐔𝐒 𝐂𝐇𝐄𝐂𝐊𝐄𝐑.ᴘᴄ ᴏʀ ᴍᴏʙɪʟᴇ

TERMUX INSTALL

$ pkg update && pkg upgrade

$ pkg install -y curl

$ pkg install git

$ git clone https://github.com/cyberscanners/CyberScanners-Server-Status.git

$ cd CyberScanners-Server-Status

$ bash Server-Status.sh

මේකෙන් මොකක්ද වෙන්න ඕනේ.

* HTTP Status Code එක Read කරනවා:උදා÷

• -s = silent.

• -o /dev/null = output discard.

• -w "%{http_code}" = server එකේ response code එක (e.g., 200, 404, 503) print කරනවා.

* Status Code එකට අනුව Response එක:

• 200, 301, 302 => usually "UP":

[+] https://example.com is UP (HTTP 200)

• වෙනත් status code => "maybe DOWN or BLOCKED":

[-] https://example.com might be DOWN or BLOCKED (HTTP 404)

* Useful Use-Cases:

• Web server monitor කරන්න.

• Script වලින් automated status check.

• Server එක අවදිද කියලා ගිහින් බලන්න වෙන වෙනම browser එකක් open කරන්න ඕන නැතුව.
