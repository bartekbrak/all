## All bartekbrak repositories as git submodules.

    # created with:
    curl 'https://api.github.com/users/bartekbrak/repos?per_page=50&page=1' | jq '.[]|.name,.html_url'
    # clone all with
    git clone --recurse-submodules https://github.com/bartekbrak/all
    # change to SSH for all for myself:
    sed -i 's,https://github.com/,git@github.com:,g' .git/modules/*/config
    # https://stackoverflow.com/a/51920532/1472229

