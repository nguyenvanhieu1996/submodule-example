git submodule init
git submodule update
https://git-scm.com/book/en/v2/Git-Tools-Submodules


src/modules/templates là repository nên cần code nào thì checkout qua branch đó, vào submodule có thể push trực tiếp

[submodule "src/modules/templates"]
	path = src/modules/templates -> khi git submodule update sẽ pull code từ [ url ] về folder src/modules/templates
	url = https://gitlab.example.git 
