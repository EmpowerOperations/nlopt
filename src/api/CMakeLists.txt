
# install man
if (NLOPT_INSTALL AND UNIX)
  install (FILES nlopt.3 nlopt_minimize.3 nlopt_minimize_constrained.3 DESTINATION ${INSTALL_MAN_DIR}/man3)
endif ()
