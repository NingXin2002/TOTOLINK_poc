# TOTOLINK_poc
TOTOLINK A6000R 命令执行漏洞（CVE-2024-41319）  


 python TOTOLINK_poc.py -h  

                ) (`-.            ) (`-.
         ( OO ).           ( OO ).
        (_/.  \_)-. ,-.-')(_/.  \_)-. ,-.-')
         \  `.'  /  |  |OO)\  `.'  /  |  |OO)
          \     /\  |  |  \ \     /\  |  |  \
           \   \ |  |  |(_/  \   \ |  |  |(_/
          .'    \_),|  |_.' .'    \_),|  |_.'
         /  .'.  \(_|  |   /  .'.  \(_|  |
        '--'   '--' `--'  '--'   '--' `--'

usage: TOTOLINK_poc.py [-h] [-u URL] [-f FILE]  

TOTOLINK A6000R 命令执行漏洞  

optional arguments:  
  -h, --help            show this help message and exit  
  -u URL, --url URL     添加url信息  
  -f FILE, --file FILE  添加txt文件  

example:  
    python3 TOTOLINK_poc.py -u http://xxxx.xxxx.xxxx.xxxx  
    python3 TOTOLINK_poc.py -f x_url.txt  
