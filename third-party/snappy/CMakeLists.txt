build_external(tgt_snappy)

install_external(snappy)

add_custom_target(
    clean-snappy
    COMMAND "rm" "-fr" "_build" "_install" "_build.log"
)

