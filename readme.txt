#learn use git
//2021/10/28
	1.load in linux/windows git
	2.config your inf
		gitconfig --user.name ""
		gitconfig --user.email ""
	3.make emptry dir as rep & init git rep
		mkdir xxx
		cd xxx
		git init
	4.add readme.txt
		vi readme.txt
		git add readme.txt
		git commit -m "discript mansgage"
//********************************test git log************/
	5.different verion cut
		vi readme.txt(add test line)
		git log(cheak verion histery)
		git reset --hard (id)
		//id is verion num,right now verion is called HEAD,up 1 degree is HEAD^,2 is HEAD^^....//
		git reflog(check laster verion num)
