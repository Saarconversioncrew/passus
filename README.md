**get module, including fields, created in Design manager:**

cd modules
hs fetch --overwrite /passus-2022/modules/module-name.module/ module-name.module/

**automatically update files to HubSpot:**

cd .
hs watch --remove passus-2022 \passus-2022
