include_directories(..)

add_executable(crypto_test crypto_test.cpp)
target_link_libraries(crypto_test ${OPENSSL_CRYPTO_LIBRARY})
add_test(crypto_test crypto_test)
