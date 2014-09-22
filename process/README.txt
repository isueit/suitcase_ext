##########################################################################################
      _                _                                  _                     _
   __| | _____   _____| | ___  _ __  _ __ ___   ___ _ __ | |_    __ _  ___  ___| | _____
  / _` |/ _ \ \ / / _ \ |/ _ \| '_ \| '_ ` _ \ / _ \ '_ \| __|  / _` |/ _ \/ _ \ |/ / __|
 | (_| |  __/\ V /  __/ | (_) | |_) | | | | | |  __/ | | | |_  | (_| |  __/  __/   <\__ \
  \__,_|\___| \_/ \___|_|\___/| .__/|_| |_| |_|\___|_| |_|\__|  \__, |\___|\___|_|\_\___/
                              |_|                               |___/
##########################################################################################

##########################################################################################
##### Omega Theme
##########################################################################################
Informational:  http://himer.us/omega960
Documentation:  http://himer.us/omega-docs
Project Page:   http://drupal.org/project/omega
Issue Queue:    http://drupal.org/project/issues/omega
Usage Stats:    http://drupal.org/project/usage/omega
Twitter:        http://twitter.com/Omeglicon
##########################################################################################
##### Process Hooks
##########################################################################################

<<<<<<< HEAD
Any custom process functionality can (rather than directly in template.php) be placed
=======
Any custom process functionality can (rather than directly in template.php) be placed 
>>>>>>> 87be89e3ddd547aca1197ea9544e986c3f82a2e7
in this process folder in a file named as such:

TEMPLATE_process_html() = process-html.inc
TEMPLATE_process_page() = process-page.inc
TEMPLATE_process_node() = process-node.inc
TEMPLATE_process_comment() = process-comment.inc
TEMPLATE_process_region() = process-region.inc
etc.

<<<<<<< HEAD
Inside of your process-HOOK.inc files, you can either directly dump the PHP code as it
would normally appear INSIDE of a process function, or you can optionally (recommended)
=======
Inside of your process-HOOK.inc files, you can either directly dump the PHP code as it 
would normally appear INSIDE of a process function, or you can optionally (recommended) 
>>>>>>> 87be89e3ddd547aca1197ea9544e986c3f82a2e7
wrap the code in a custom hook for Alpha/Omega as such:

function THEMENAME_alpha_process_HOOK(&$vars) {
  // custom functionality here
<<<<<<< HEAD
}
=======
}
>>>>>>> 87be89e3ddd547aca1197ea9544e986c3f82a2e7
