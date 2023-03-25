1 $ git merge origin/druid
    fatal: refusing to merge unrelated histories
    
    在执行merge的时候报unrelated histories，其实pull，push也一样
    解决方法：在执行命令的后面加 --allow-unrelated-histories