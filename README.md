# go-docker
go app in docker

Setting up Go get command for private repository Gitlab

1. Add following cmd to .Gitconfig file in userprofile folder
[url "ssh://git@gitlab.com/"]
	insteadOf = https://gitlab.com/
2. Add _netrc file to user profile folder
3. Add following line to _netrc file
machine gitlab.com login [username] password [access-key]   

