build_external(tgt_double-conversion)

install_external(double-conversion)

add_custom_target(
    clean-double-conversion
    COMMAND "rm" "-fr" "_build" "_install" "_build.log"
)

