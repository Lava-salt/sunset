print("Welcome to SunSet Editor! ©2025, @Lava-salt\nAn open source Vim-based code editor.\nThis is a side project of @Lava-salt, who made Froggy OS.\nTo download FOS, go to https://raw.githubusercontent.com/Lava-salt/fos/refs/heads/main/read_me_plz website.\nTo access SunSet Editor's code, go to https://www.github.com/Lava-salt/sunset.git/ website.\nType \"docs [ss/py/bat]\", \"help()\", or \"help\" to see SunScript documentation,\nthe documentation of the shell/command prompt language of SunSet Editor.\nWhile coding in Python, please do not start any of the variable, list, tuple, dict e.t.c. names with \"data_\" string.\nUsing this could cause unintentional arbitrary code execution or code corruptions.\n")
data_codelang = []
data_code = []
data_sng = {"sng": 1, "dbl" : 2, "trp" : 3, "qdr" : 4, "qnt" : 5, "sxt" : 6, "spt" : 7, "nnp" : 8, "oct" : 9, "dcp" : 10}
data_coding = "Null"
from os import system, name, getcwd
from sys import platform
from subprocess import call, Popen, PIPE, run
from webbrowser import open as wopen
from random import random
from datetime import datetime
from calendar import TextCalendar, MONDAY
from time import sleep
if name == "nt":
    while True:
        data_orgrawinput = input(">>> ")
        data_rawinput = data_orgrawinput.lower()
        data_input = data_rawinput.strip()
        data_list = data_input.split(" ")
        data_cmd = data_list[0]
        data_data = data_list[1 :]
        data_orginput = data_orgrawinput.strip()
        data_orglist = data_orginput.split(" ")
        data_orgcmd = data_orglist[0]
        data_orgdata = data_orglist[1: len(data_orglist)]
        if data_rawinput == "docs ss":
            print("""
Welcome to SunScript Documentation!
Here's the current SS functions:
docs [obj] = Displays the documentation of given object
    For [obj]:
        ss = SunScript Documentation
        py = Python Documentation
        pym = Python Module List
        pykw = Python Keyword List
        pys = Python Symbol List
        pyt = Python Topic List
        bat = Batch Documentation
r [obj] = Displays the code that you've written
    For [obj]:
        <nothing> / norm = Normally
        int = Display using numbers
        ls = As a Python list
        eval = Only the code that is in "eval" format
        exec = Only the Python code
        bat = Only the Batch code
a [lang] [obj] = Writes new code to the code you've written
    For [lang]:
        eval = Write code in "eval" format, which evaluates the written text to Python code and prints it, basically
            print(eval(input(">>> ")))
        exec = Write Python code
        bat = Write Batch code
    For [obj]:
        sng = Write only one line
        dbl = Write only two lines
        trp = Write only three lines
        qdr = Write only four lines
        qnt = Write only five lines
        sxt = Write only six lines
        spt = Write only seven lines
        oct = Write only eight lines
        nnp = Write only nine lines
        dcp = Write only ten lines
        uq = Write until "q", "quit" or "exit" is written to the terminal
        1 = Write only 1 lines (works for every integer)
w [lang] = Replaces the code you've written with given code
    For [lang]:
        eval = Replace code with eval format code
        exec = Replace code with Python code
        bat = Replace code with Batch code
new = Deletes code you've written.
run = Run code you've written.
os = Displays operating system information
call [obj] = Runs given program
ping [obj] = Pings given I.P. address
fr [file] = Displays given directory's file's contents
fw [file] [txt] = Replaces given directory's file's contents with given text
fa [file] [txt] = Appends given directory's file's contents with given text
fa nl = Appends newline to given directory's file's contents
web [obj] = Opens given link
rand = Displays random decimal from 0 to 1
rand [lowest] [highest] = Displays random number between given values 
tm = Displays the time
tm [obj] = Displays a specific time
    For [obj]:
        yr = Year
        mon = Month
        d = Day
        ho = Hour
        min = Minute
        sec = Second
        ms = Microsecond
cl mo [month] [year] = Displays given time's monthly calendar
cl yr [year] = Displays given time's yearly calendar
slp [sec] = Temporarily lock the terminal for given time as seconds
ps [txt] = Temporarily lock the terminal until given text is written to terminal
dsh [obj] = Displays the shell for given language
    For [obj]:
        eval = Eval code format
        py = Python
        exec = Python
        bat = Batch
        cmd = Windows "cmd.exe"
sh [lang] [obj] = Opens a shell for given lang
    For [lang]:
        eval = Eval code format
        py = Python
        exec = Python
        bat = Batch
        cmd = Windows "cmd.exe"
    For [obj]:
        sng = Write only one line
        dbl = Write only two lines
        trp = Write only three lines
        qdr = Write only four lines
        qnt = Write only five lines
        sxt = Write only six lines
        spt = Write only seven lines
        oct = Write only eight lines
        nnp = Write only nine lines
        dcp = Write only ten lines
        uq = Write until "q", "quit" or "exit" is written to the terminal
        1 = Write only 1 lines (works for every integer)
ptf [file] [obj] = Put code you've written to the given file
    For [obj]:
        eval = Eval code format
        exec = Python
        bat = Batch
ins = Inserts code at a specific line of the code you've written
rep = Replaces code of a specific line of the code you've written
del = Deletes code of a specific line of the code you've written
gff [file] = Turn the code you've written to the given file's contents
echo [obj] = Displays given text in the console
cmd exe = Opens Windows Command Prompt
wmic = Opens WMI information shell
zop = Displays the Zen of Python
ag = Opens Python antigravity comic
gh = Opens geohashing comic
qrsh [lang] = Opens a shell for given language until "q", "quit" or "exit" is written to the console; and quickly runs it as a single code block
    For [lang]:
        exec = Python
        py = Python
        bat = Batch
        ps = PowerShell
You can run these external commands:
    1. File compiling:
        You can compile any file in any language with this:
        File "file.txt" contents: print("test")
        SS shell: >>> python3 file.txt
        SS Output: test
        The logic: exec('import subprocess\\nsubprocess.run(input(">>> ").split(" "))')
    2. Python code execution and evaluation printing:
        You can run Python codes and print evaluated Python strings:
        SS Shell:
            >>> x = 66
            >>> print(x)
            66
            >>> x # in a "while True: exec(input('>>> '))" code IDE, this command would print nothing. 
            66
            >>> x = int(input("Number 1: "))
            Number 1: 13
            >>> y = int(input("Number 2: "))
            Number 2: 21
            >>> z = x + y
            >>> z
            34
    3. Batch execution:
        You can even run Batch code:
        SS Shell:
            >>> echo I can run Batch!
            I can run Batch!
            >>> ver
            Microsoft Windows [Version 10.0.26100.3476]
It also comes with these Python Standard Library functions pre-installed:
/*
from os import system, name, getcwd
from sys import platform
from subprocess import call, Popen, PIPE, run
from webbrowser import open as wopen
from random import random
from datetime import datetime
from calendar import TextCalendar, MONDAY
from time import sleep
*/
            """)
        elif data_rawinput == "docs py":
            help()
        elif data_rawinput == "docs pym":
            help("modules")
        elif data_rawinput == "docs pykw":
            help("keywords")
        elif data_rawinput == "docs pys":
            help("symbols")
        elif data_rawinput == "docs pyt":
            help("topics")
        elif data_rawinput == "docs bat":
            system("help")
        elif data_rawinput == "r" or data_rawinput == "r norm":
            for data_i in data_code:
                print(data_i)
        elif data_rawinput == "r int":
            for data_i in range(len(data_code)):
                print(f"{data_i}. {data_code[data_i]}")
        elif data_rawinput == "r ls":
            print(data_code)
        elif data_rawinput == "r eval":
            for data_i in range(len(data_code)):
                if data_codelang[data_i] == "eval":
                    print(data_code[data_i])
        elif data_rawinput == "r exec":
            for data_i in range(len(data_code)):
                if data_codelang[data_i] == "exec":
                    print(data_code[data_i])
        elif data_rawinput == "r bat":
            for data_i in range(len(data_code)):
                if data_codelang[data_i] == "bat":
                    print(data_code[data_i])
        elif data_cmd == "a":
            data_ainput = data_list[1:3]
            data_alang = data_ainput[0]
            data_acode = data_ainput[1]
            if data_acode == "uq":
                while True:
                    data_coding = input("> ")
                    if data_coding == "q" or data_coding == "quit" or data_coding == "exit":
                        break
                    else:
                        data_code.append(data_coding)
                        data_codelang.append(data_alang)
            elif data_acode.isnumeric():
                for data_i in range(int(data_acode)):
                    data_code.append(input("> "))
                    data_codelang.append(data_alang)
            else:
                for data_i in range(data_sng[data_acode]):
                    data_code.append(input("> "))
                    data_codelang.append(data_alang)
        elif data_cmd == "w":
            data_code = [input("> ")]
            data_codelang = [data_data[0]]
        elif data_rawinput == "new":
            data_code = []
            data_codelang = []
        elif data_rawinput == "run":
            for data_i in range(len(data_code)):
                if data_codelang[data_i] == "eval":
                    try: print(eval(data_code[data_i]))
                    except Exception as e: print(e)
                elif data_codelang[data_i] == "exec":
                    try: exec(data_code[data_i])
                    except Exception as e: print(e)
                elif data_codelang[data_i] == "bat":
                    try: system(data_code[data_i])
                    except Exception as e: print(e)
        elif data_rawinput == "os":
            system("systeminfo")
            print(f"Operating System Name: {name}")
            print(f"Platform: {platform}")
        elif data_cmd == "call":
            data_file = data_data[0]
            call(data_file)
        elif data_cmd == "ping":
            data_ip = ".".join(data_data)
            data_ipping = Popen(args = f"ping {data_ip}", stdout = PIPE)
            if data_ipping.poll():
                print("Passive")
            else:
                print("Active")
        elif data_cmd == "fr":
            data_file = "\\".join(data_data)
            with open(data_file, "r") as data_openf:
                print(data_openf.read())
                data_openf.close()
        elif data_cmd == "fw":
            data_file = data_data[0]
            data_txt = data_data[1]
            with open(data_file, "w") as data_openf:
                data_openf.write(data_txt)
                data_openf.close()
        elif data_cmd == "fa":
            data_file = data_data[0]
            data_txt = data_data[1]
            with open(data_file, "a") as data_openf:
                data_openf.write(data_txt)
                data_openf.close()
        elif data_cmd == "web":
            data_link = " ".join(data_data)
            wopen(data_link)
        elif data_rawinput == "rand":
            print(random())
        elif data_cmd == "rand":
            data_min = int(data_data[0])
            data_max = int(data_data[1])
            print(((data_max - data_min) * random()) - data_min)
        elif data_rawinput == "tm":
            print(datetime.now())
        elif data_cmd == "tm":
            data_time = data_data[0]
            if data_time == "yr":
                print(datetime.now().year)
            elif data_time == "mo":
                print(datetime.now().month)
            elif data_time == "d":
                print(datetime.now().day)
            elif data_time == "ho":
                print(datetime.now().hour)
            elif data_time == "min":
                print(datetime.now().minute)
            elif data_time == "sec":
                print(datetime.now().second)
            elif data_time == "ms":
                print(datetime.now().microsecond)
        elif data_rawinput.startswith("cl mo "):
            data_mon = int(data_data[1])
            data_yr = int(data_data[2])
            data_c = TextCalendar(MONDAY)
            data_c.prmonth(data_yr, data_mon)
        elif data_rawinput.startswith("cl yr "):
            data_mon = int(data_data[1])
            data_yr = int(data_rawinput.strip("cl yr "))
            data_c = TextCalendar(MONDAY)
            data_c.pryear(data_yr)
        elif data_cmd == "sec":
            data_sleep = int(data_data[0])
            sleep(data_sleep)
        elif data_cmd == "ps":
            data_ps = " ".join(data_data)
            data_try = 0
            while not(data_try == data_ps):
                data_try = input()
        elif data_cmd == "dsh":
            data_shlang = data_data[0]
            if data_shlang == "ss":
                print("Welcome to SunSet Editor! ©2025, @Lava-salt\nAn open source Vim-based code editor.\nThis is a side project of @Lava-salt, who made Froggy OS.\nTo download FOS, go to https://raw.githubusercontent.com/Lava-salt/fos/refs/heads/main/read_me_plz website.\nTo access SunSet Editor's code, go to https://www.github.com/Lava-salt/sunset.git/ website.\nType \"help\" to see SunScript documentation,\nthe documentation of the shell/command prompt language of SunSet Editor.\nWhile coding in Python, please do not start any of the variable, list, tuple, dict e.t.c. names with \"data_\" string.\nUsing this could cause unintentional arbitrary code execution or code corruptions.\n")
            elif data_shlang == "py":
                print(f'Python 3.8.5 (default, Jul 20 2020, 23:11:29)\n[GCC 9.3.0] on {platform}\nType "help", "copyright", "credits" or "license" for more information.')
            elif data_shlang == "bat" or data_shlang == "cmd":
                print(f"Windows PowerShell\nCopyright (C) Microsoft Corporation. All rights reserved.\n\nInstall the latest PowerShell for new features and improvements! https://aka.ms/PSWindows\n\n(.venv) PS {getcwd}> ")
        elif data_cmd == "sh":
            data_ainput = data_list[1:3]
            data_alang = data_ainput[0]
            data_acode = data_ainput[1]
            if data_alang == "eval" or data_alang == "exec" or data_alang == "py":
                print(f'Python 3.8.5 (default, Jul 20 2020, 23:11:29)\n[GCC 9.3.0] on {platform}\nType "help", "copyright", "credits" or "license" for more information.')
            elif data_alang == "bat":
                print(f"Windows PowerShell\nCopyright (C) Microsoft Corporation. All rights reserved.\n\nInstall the latest PowerShell for new features and improvements! https://aka.ms/PSWindows\n\n")
            if data_acode == "uq":
                while True:
                    if data_alang == "eval" or data_alang == "exec" or data_alang == "py":
                        data_coding = input(">>> ")
                    elif data_alang == "bat":
                        data_coding = input(f"(.venv) PS {getcwd}> ")
                    elif data_alang == "cmd":
                        system("cmd")
                    if data_coding == "q" or data_coding == "quit" or data_coding == "exit":
                        break
                    else:
                        if data_alang == "exec" or data_alang == "py":
                            try: exec(data_coding)
                            except Exception as e: print(e)
                        elif data_alang == "eval":
                            try: eval(data_coding)
                            except Exception as e: print(e)
                        elif data_alang == "bat" or data_alang == "cmd":
                            system(data_coding)
            elif data_acode.isnumeric():
                data_ainput = data_list[1:3]
                data_alang = data_ainput[0]
                data_acode = data_ainput[1]
                if data_alang == "eval" or data_alang == "exec" or data_alang == "py":
                    print(f'Python 3.8.5 (default, Jul 20 2020, 23:11:29)\n[GCC 9.3.0] on {platform}\nType "help", "copyright", "credits" or "license" for more information.')
                elif data_alang == "bat" or data_alang == "cmd":
                    print(f"Windows PowerShell\nCopyright (C) Microsoft Corporation. All rights reserved.\n\nInstall the latest PowerShell for new features and improvements! https://aka.ms/PSWindows\n\n")
                if data_acode == "uq":
                    for data_i in range(int(data_acode)):
                        if data_alang == "eval" or data_alang == "exec" or data_alang == "py":
                            data_coding = input(">>> ")
                        elif data_alang == "bat" or data_alang == "cmd":
                            data_coding = input(f"(.venv) PS {getcwd}> ")
                        if data_coding == "q" or data_coding == "quit" or data_coding == "exit":
                            break
                        else:
                            if data_alang == "exec" or data_alang == "py":
                                try:
                                    exec(data_coding)
                                except Exception as e:
                                    print(e)
                            elif data_alang == "eval":
                                try:
                                    eval(data_coding)
                                except Exception as e:
                                    print(e)
                            elif data_alang == "bat" or data_alang == "cmd":
                                system(data_coding)
            else:
                for data_i in range(data_sng[data_acode]):
                    data_code.append(input("> "))
                    data_codelang.append(data_alang)
        elif data_rawinput == "ins":
            for data_i in range(len(data_code)):
                print(f"Line {data_i}: {data_code[data_i]}")
            data_insint = int(input("Insert code at line: "))
            data_inscode = input("Code to insert: ")
            data_inslang = input("Its language: (lowercase, one of \"exec\", \"eval\", \"bat\") ")
            data_inslang = data_inslang.lower()
            data_code.insert(data_insint, data_inscode)
            data_codelang.insert(data_insint, data_inslang)
        elif data_rawinput == "rep":
            for data_i in range(len(data_code)):
                print(f"Line {data_i}: {data_code[data_i]}")
            data_repint = int(input("Replace code of line: "))
            data_repcode = input("Code to replace with: ")
            data_replang = input("Its language: (lowercase, one of \"exec\", \"eval\", \"bat\") ")
            data_replang = data_replang.lower()
            data_code[data_repint] = data_repcode
            data_codelang[data_repint] = data_replang
        elif data_rawinput == "del":
            for data_i in range(len(data_code)):
                print(f"Line {data_i}: {data_code[data_i]}")
            data_delint = int(input("Delete code of line: "))
            del data_code[data_delint]
        elif data_cmd == "gff":
            data_file = data_data[0]
            with open (data_file, "r") as data_f:
                data_code = data_f.readlines()
                data_f.close()
        elif data_cmd == "ptf":
            data_file = data_data[0]
            data_lang = data_data[1]
            if data_lang == "*":
                with open(data_file, "r") as data_f:
                    for data_i in data_code:
                        data_f.write(data_i + "\n")
                    data_f.close()
            else:
                with open(data_file, "r") as data_f:
                    for data_i in range(len(data_code)):
                        if data_codelang == data_lang:
                            data_f.write(data_code[data_i] + "\n")
                    data_f.close()
        elif data_rawinput == "cmd exe":
            system("start")
        elif data_rawinput == "zop":
            print("The Zen of Python, by Tim Peters\n\nBeautiful is better than ugly.\nExplicit is better than implicit.\nSimple is better than complex.\nComplex is better than complicated.\nFlat is better than nested.\nSparse is better than dense.\nReadability counts.\nSpecial cases aren't special enough to break the rules.\nAlthough practicality beats purity.\nErrors should never pass silently.\nUnless explicitly silenced.\nIn the face of ambiguity, refuse the temptation to guess.\nThere should be one-- and preferably only one --obvious way to do it.\nAlthough that way may not be obvious at first unless you're Dutch.\nNow is better than never.\nAlthough never is often better than *right* now.\nIf the implementation is hard to explain, it's a bad idea.\nIf the implementation is easy to explain, it may be a good idea.\nNamespaces are one honking great idea -- let's do more of those!")
        elif data_rawinput == "ag":
            wopen("https://xkcd.com/353/")
        elif data_rawinput == "gh":
            wopen("https://xkcd.com/426/")
        elif data_cmd == "qrsh":
            data_lang = data_data[0]
            data_codeinput = 0
            data_codeblock = ""
            while not(data_codeinput == "q" or data_codeinput == "quit" or data_codeinput == "exit"):
                data_codeinput = input("> ")
                data_codeblock = f"{data_codeblock}\n{data_codeinput}"
            if data_lang == "exec" or data_lang == "py":
                try: exec(data_codeblock)
                except Exception as e: print(e)
            if data_lang == "bat" or data_lang == "ps":
                try: system(data_codeblock)
                except Exception as e: print(e)
        else:
            try: run(data_list)
            except Exception as e:
                data_err1 = False
                data_err2 = False
                try: eval(data_rawinput)
                except Exception as e: data_err1 = True
                try: exec(data_rawinput)
                except Exception as e: data_err2 = True
                if data_err1 and data_err2:
                    try: system(data_rawinput)
                    except Exception as e: print(e)
else:
    print("SunSet Editor is not compatible with this PC.\nPlease use Windows NT, so it runs Batch as cmd.exe language instead of BASH.")
