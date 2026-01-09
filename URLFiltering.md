# You really don't want these in your network
`(( url_category_list contains 'command-and-control' ) or ( url_category_list contains 'malware' ) or ( url_category_list contains 'ransomware' ) or ( url_category_list contains 'phishing' ))`

# Not the worst but still not healthy
`(( url_category_list contains 'compromised-website' ) or ( url_category_list contains 'hacking' ) or ( url_category_list contains 'scanning-activity' ))`

# It could be a lot worse than these
`((( url_category_list contains 'copyright-infringement' ) or ( url_category_list contains 'cryptocurrency' ) or ( url_category_list contains 'newly-registered-domain' ) or ( url_category_list contains 'peer-to-peer' ) or ( url_category_list contains 'proxy-avoidance-and-anonymizers' )) and (! url contains 'icloud.com/' ))`

# Some ones to watch
`( url_category_list contains 'file-converter' )`
`( url_category_list contains 'remote-access' )`
`( url_category_list contains 'unknown' )`
