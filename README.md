# Traceback-most-recent-call-last-Error-microsoft-point-autofarmer
Hello, I'm not really familiar with coding and such, but i've been trying to set up a microsoft point autofarmer, and it keeps stopping at the part where it tells me how many points I hve. I don't really know what to about this, and I'm very frustrated. If anyone can see this please me.

Run command: python ms_rewards_farmer.py

This is the code tho:

███╗   ███╗███████╗    ███████╗ █████╗ ██████╗ ███╗   ███╗███████╗██████╗
████╗ ████║██╔════╝    ██╔════╝██╔══██╗██╔══██╗████╗ ████║██╔════╝██╔══██╗
██╔████╔██║███████╗    █████╗  ███████║██████╔╝██╔████╔██║█████╗  ██████╔╝
██║╚██╔╝██║╚════██║    ██╔══╝  ██╔══██║██╔══██╗██║╚██╔╝██║██╔══╝  ██╔══██╗
██║ ╚═╝ ██║███████║    ██║     ██║  ██║██║  ██║██║ ╚═╝ ██║███████╗██║  ██║
╚═╝     ╚═╝╚══════╝    ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝
        by Lucas#5123              version 3.0

********************(I have my actual email here already)********************

DevTools listening on ws://127.0.0.1:51147/devtools/browser/4755fd3e-f900-4df6-a624-c81252ee14ab
[LOGIN] Logging-in...
[LOGIN] Writing email...
[LOGIN] Writing password...
[LOGIN] Passing security checks...
[LOGIN] Logged-in !
[LOGIN] Ensuring login on Bing...
[LOGIN] Logged-in successfully !
[POINTS] You have 4273 points on your account !
Traceback (most recent call last):
  File "C:\Users\udayv\Downloads\Microsoft-points-autofarmer-main (2)\Microsoft-points-autofarmer-main\ms_rewards_farmer.py", line 779, in <module>
    waitUntilVisible(browser, By.XPATH, '//*[@id="navs"]/div/div/div/div/div[4]/a', 20)
  File "C:\Users\udayv\Downloads\Microsoft-points-autofarmer-main (2)\Microsoft-points-autofarmer-main\ms_rewards_farmer.py", line 160, in waitUntilVisible
    WebDriverWait(browser, time_to_wait).until(ec.visibility_of_element_located((by_, selector)))
  File "C:\Users\udayv\AppData\Local\Programs\Python\Python312\Lib\site-packages\selenium\webdriver\support\wait.py", line 105, in until
    raise TimeoutException(message, screen, stacktrace)
selenium.common.exceptions.TimeoutException: Message:
Stacktrace:
        GetHandleVerifier [0x00007FF6C9F72142+3514994]
        (No symbol) [0x00007FF6C9B90CE2]
        (No symbol) [0x00007FF6C9A376AA]
        (No symbol) [0x00007FF6C9A81860]
        (No symbol) [0x00007FF6C9A8197C]
        (No symbol) [0x00007FF6C9AC4EE7]
        (No symbol) [0x00007FF6C9AA602F]
        (No symbol) [0x00007FF6C9AC28F6]
        (No symbol) [0x00007FF6C9AA5D93]
        (No symbol) [0x00007FF6C9A74BDC]
        (No symbol) [0x00007FF6C9A75C64]
        GetHandleVerifier [0x00007FF6C9F9E16B+3695259]
        GetHandleVerifier [0x00007FF6C9FF6737+4057191]
        GetHandleVerifier [0x00007FF6C9FEE4E3+4023827]
        GetHandleVerifier [0x00007FF6C9CC04F9+689705]
        (No symbol) [0x00007FF6C9B9C048]
        (No symbol) [0x00007FF6C9B98044]
        (No symbol) [0x00007FF6C9B981C9]
        (No symbol) [0x00007FF6C9B888C4]
        BaseThreadInitThunk [0x00007FFC862C257D+29]
        RtlUserThreadStart [0x00007FFC87D6AA58+40]
