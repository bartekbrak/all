## All bartekbrak repositories as git submodules.

    # created with:
    curl 'https://api.github.com/users/bartekbrak/repos?per_page=50&page=1' | jq '.[]|.name,.html_url'
    # clone all with
    git clone --recurse-submodules https://github.com/bartekbrak/all

