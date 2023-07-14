If use window:
steps: - go to where you want create django app on that folder.

then run this command on command prompt : python -m virtualenv .

(eg. C:\Users\gshiv\Desktop\django>python -m virtualenv .)

where django is the my folder i want run virtualenv and .(dot) indicates virtualenv install all it's folder in django folder otherwise you can use other folder name instead .(dot) this time virtulenv creates a folder in main folder(django) .

after running this command: run .\scripts\activate now you can see this type of line on cmd-prompt (django) C:\Users\gshiv\Desktop\django>
i.e main folder name before the source path. now you can install any modules for your project that belongs to that main folder only.
pip install django works fine.
