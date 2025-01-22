# badge files

file(GLOB BADGE_FILES *.svg *.png)

install(FILES ${BADGE_FILES}
        DESTINATION "${CMAKE_INSTALL_FULL_DATADIR}/ayatana-greeter/badges")
