#*******************************************************************************
# Copyright (C) Sierra Wireless Inc.
#*******************************************************************************

mkapp(voicePromptMcc2.adef
    -i ${LEGATO_ROOT}/interfaces/modemServices
)

# This is a C test
add_dependencies(tests_c voicePromptMcc2)
