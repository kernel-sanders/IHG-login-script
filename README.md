IHG-login-script
================

Automate the annoying 24 hour login required at IHG

Change the 'MAC' and 'REQUESTED_IP' variables at the top
of the script and run at a frequency < 24 hours (cron
works great for this). The 'usermac' in the second POST
as well as the 'sysid' used in all POSTs will probably
need to be changed depending on your location (I am unable 
to test this, watch a manual log in with firebug or similar
and tweak accordingly).