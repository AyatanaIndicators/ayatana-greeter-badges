# badge files

file(GLOB_RECURSE BADGE_FILES FOLLOW_SYMLINKS *.svg *.png)

install(FILES ${BADGE_FILES}
        DESTINATION "${CMAKE_INSTALL_FULL_DATADIR}/ayatana-greeter/badges")
