
add_executable(clickhouse-odbc-ut
    main.cpp
    escape_sequences_ut.cpp
)

target_link_libraries(clickhouse-odbc-ut
    clickhouse-odbc-escaping
    gtest-lib
    pthread
)
