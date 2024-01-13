# Ddos-Attack- 
# Usage: git clone https://github.com/lucthienphong1120/EagleEye.git
python3 eagleeye.py --help

Options : python3 eagleeye.py <url> <options>

Options            Description                                      Default
-u, --useragents   Type of user-agents to generate                  (default: randomly generated)
                   (see in http://www.useragentstring.com/)
-w, --workers      Number of concurrent workers to attack           (default: 50)
-s, --sockets      Number of concurrent sockets                     (default: 100)
-m, --method       HTTP Method to use                               (default: get)
                   (get/post/random)
-d, --debug        Enable Debug Mode (more verbose output)          (default: False)
                   (True/False)
-n, --nosslcheck   Do not verify SSL Certificate                    (default: True)
                   (True/False)
-h, --help         Shows this help

Example: python3 eagleeye.py https://example.com -w 1000 -s 1000 -m post
