# my_script
一键下载GitHub上指定的工具，可设置每个工具储存的目录。
需要更改的位置：
====================================================
# 设置GitHub Personal Access Token
GITHUB_TOKEN = 'ghp_xxxx'

# 设置代理
PROXY = {
    'http': 'http://127.0.0.1:7890',
    'https': 'http://127.0.0.1:7890'
}


# 指定要下载的GitHub链接和目标存储位置
    releases = [
        {
            'repo_name': 'wgpsec/ENScan_GO', 这里填写下载的项目位置
            'pattern': 'win',  这里选择下载的版本中选择要下载的版本。看每个项目是怎么命名的就填写什么。
            'target_dir': 'E:/tools/404StarLink/'  这里填写下载的存储位置
        },
===================================================
