## Приручая орудия уничтожения Mac OS

#### Патрик Вардл. Конференция DEF CON 27

Доклад был подготовлен Патриком Уордлом, исследователем из Jampf, сооснователем Objective-See. (Нужно ли это вообще..)

Данный доклад был посвящен использованию чужого вредоносного ПО для маков в собственных целях. На примерах различных типов вредоносного ПО были рассмотрены способы кастомизации уже имеющихся программ, что представляет собой модификацию бинаря для работы с нашим собственным C&C сервером и т.д. Но возможность модификации подразумевает то, что программа уже была обнаружена, и для того чтобы старания в кастомизации софта не оказались напрасны в докладе было уделено внимание и способам “скрыться” от распространенных методов обнаружения. 


---

## Harnessing Weapons of Mac Destruction

#### Patrick Wardle - DEF CON 27 Conference

Whenever a new Mac malware specimen is uncovered, it provides a unique insight into the offensive Mac capabilities of hackers or nation-state adversaries. Better yet, such discoveries provide fully-functional capabilities that may be weaponized for our own surreptitious purposes! I mean, life is short, why write your own?

We'll begin this talk by discussing the methodology of subverting existing malware for "personal use", highlighting both the challenges and benefits of such an approach.

Next, we'll walk-thru the weaponization of various Mac malware specimens, including an interactive backdoor, a file-exfiltration implant, ransomware, and yes, even adware. Customizations include various runtime binary modifications that will coerce such malware to accept tasking from our own C&C servers, and/or automatically perform actions on our behalf. 

Of course, in their pristine state, such samples are currently detected by AV products. As such we'll also walk-thru subtle modifications that will ensure our modified tools remains undetected by traditional detection approaches.

In conclusion, we'll highlight novel heuristic methods that can generically detect such threats to ensure Mac users remain protected even from such weaponized threats.

Patrick Wardle
Patrick Wardle is the Chief Research Officer at Digita Security and founder of Objective-See. Having worked at NASA and the NSA, as well as presented at countless security conferences, he is intimately familiar with aliens, spies, and talking nerdy. Patrick is passionate about all things related to macOS security and thus spends his days finding Apple 0days, analyzing macOS malware and writing free open-source security tools to protect Mac users.

http://twitch.com/patrickwardle

