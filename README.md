# TY Blog Site

This is a repo that aims to teach Transition Year students some of the basics of Git via a jekyll-hosted markdown site. It was created as part of the TY Programme in Red Hat Waterford.

freshclam
clamscan
db_version=$(sigtool --info /var/lib/clamav/daily.cvd | grep 'Version')
echo -e "Executed-on: Scan was executed on clamscan version - $(clamscan --version)\nDatabase - $db_version"