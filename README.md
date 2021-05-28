# Scripts

Execute to get list of installed fonts execute:

  `fc-list -f '%{family}\n' | awk '!x[$0]++'`
