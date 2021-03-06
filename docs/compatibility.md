---
id: compatibility
title: Compatibility
sidebar_label: Compatibility
---

<!-- Generated by build-scripts/symbols.js with
     sodium-native@2.2.1
     sodium-javascript@0.5.5 -->


| C Library Symbol                                                                                                       |  `sodium-native`       | `sodium-javascript`      |
|:-----------------------------------------------------------------------------------------------------------------------|:----------------------:|:------------------------:|
| [`crypto_aead_xchacha20poly1305_ietf_ABYTES`](aead#constants)                                                          | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_decrypt`](aead#crypto_aead_xchacha20poly1305_ietf_decrypt)                        | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_decrypt_detached`](aead#crypto_aead_xchacha20poly1305_ietf_decrypt_detached)      | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_encrypt`](aead#crypto_aead_xchacha20poly1305_ietf_encrypt)                        | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_encrypt_detached`](aead#crypto_aead_xchacha20poly1305_ietf_encrypt_detached)      | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_KEYBYTES`](aead#constants)                                                        | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_keygen`](aead#crypto_aead_xchacha20poly1305_ietf_keygen)                          | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_MESSAGEBYTES_MAX`](aead#constants)                                                | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_NPUBBYTES`](aead#constants)                                                       | ![sodium-native][node] |                          |
| [`crypto_aead_xchacha20poly1305_ietf_NSECBYTES`](aead#constants)                                                       | ![sodium-native][node] |                          |
| [`crypto_auth`](authentication#crypto_auth)                                                                            | ![sodium-native][node] |                          |
| [`crypto_auth_BYTES`](authentication#constants)                                                                        | ![sodium-native][node] |                          |
| [`crypto_auth_KEYBYTES`](authentication#constants)                                                                     | ![sodium-native][node] |                          |
| [`crypto_auth_PRIMITIVE`](authentication#constants)                                                                    | ![sodium-native][node] |                          |
| [`crypto_auth_verify`](authentication#crypto_auth_verify)                                                              | ![sodium-native][node] |                          |
| [`crypto_box_detached`](keyboxencryption#crypto_box_detached)                                                          | ![sodium-native][node] |                          |
| [`crypto_box_easy`](keyboxencryption#crypto_box_easy)                                                                  | ![sodium-native][node] |                          |
| [`crypto_box_keypair`](keyboxencryption#crypto_box_keypair)                                                            | ![sodium-native][node] |                          |
| [`crypto_box_MACBYTES`](keyboxencryption#constants)                                                                    | ![sodium-native][node] |                          |
| [`crypto_box_NONCEBYTES`](keyboxencryption#constants)                                                                  | ![sodium-native][node] |                          |
| [`crypto_box_open_detached`](keyboxencryption#crypto_box_open_detached)                                                | ![sodium-native][node] |                          |
| [`crypto_box_open_easy`](keyboxencryption#crypto_box_open_easy)                                                        | ![sodium-native][node] |                          |
| [`crypto_box_PRIMITIVE`](keyboxencryption#constants)                                                                   | ![sodium-native][node] |                          |
| [`crypto_box_PUBLICKEYBYTES`](keyboxencryption#constants)                                                              | ![sodium-native][node] |                          |
| [`crypto_box_seal`](sealedboxencryption#crypto_box_seal)                                                               | ![sodium-native][node] |                          |
| [`crypto_box_seal_open`](sealedboxencryption#crypto_box_seal_open)                                                     | ![sodium-native][node] |                          |
| [`crypto_box_SEALBYTES`](sealedboxencryption#constants)                                                                | ![sodium-native][node] |                          |
| [`crypto_box_SECRETKEYBYTES`](keyboxencryption#constants)                                                              | ![sodium-native][node] |                          |
| [`crypto_box_seed_keypair`](keyboxencryption#crypto_box_seed_keypair)                                                  | ![sodium-native][node] |                          |
| [`crypto_box_SEEDBYTES`](keyboxencryption#constants)                                                                   | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_add`](finitefieldarithmetic#crypto_core_ed25519_add)                                             | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_BYTES`](finitefieldarithmetic#constants)                                                         | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_from_uniform`](finitefieldarithmetic#crypto_core_ed25519_from_uniform)                           | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_is_valid_point`](finitefieldarithmetic#crypto_core_ed25519_is_valid_point)                       | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_sub`](finitefieldarithmetic#crypto_core_ed25519_sub)                                             | ![sodium-native][node] |                          |
| [`crypto_core_ed25519_UNIFORMBYTES`](finitefieldarithmetic#constants)                                                  | ![sodium-native][node] |                          |
| [`crypto_generichash`](generichashing#crypto_generichash)                                                              | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_BYTES`](generichashing#crypto_constants)                                                          | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_BYTES_MAX`](generichashing#constants)                                                             | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_BYTES_MIN`](generichashing#constants)                                                             | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_KEYBYTES`](generichashing#constants)                                                              | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_KEYBYTES_MAX`](generichashing#constants)                                                          | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_KEYBYTES_MIN`](generichashing#constants)                                                          | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_generichash_PRIMITIVE`](generichashing#constants)                                                             | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_hash`](sha#crypto_hash)                                                                                       | ![sodium-native][node] |                          |
| [`crypto_hash_BYTES`](sha#constants)                                                                                   | ![sodium-native][node] |                          |
| [`crypto_hash_PRIMITIVE`](sha#constants)                                                                               | ![sodium-native][node] |                          |
| [`crypto_hash_sha256`](sha#crypto_hash_sha256)                                                                         | ![sodium-native][node] |                          |
| [`crypto_hash_sha256_BYTES`](sha#constants)                                                                            | ![sodium-native][node] |                          |
| [`crypto_hash_sha512`](sha#crypto_hash_sha512)                                                                         | ![sodium-native][node] |                          |
| [`crypto_hash_sha512_BYTES`](sha#constants)                                                                            | ![sodium-native][node] |                          |
| [`crypto_kdf_BYTES_MAX`](keyderivation#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_BYTES_MIN`](keyderivation#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_CONTEXTBYTES`](keyderivation#constants)                                                                   | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_derive_from_key`](keyderivation#crypto_kdf_derive_from_key)                                               | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_KEYBYTES`](keyderivation#constants)                                                                       | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_keygen`](keyderivation#crypto_kdf_keygen)                                                                 | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kdf_PRIMITIVE`](keyderivation#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_kx_client_session_keys`](keyexchange#crypto_kx_client_session_keys)                                           | ![sodium-native][node] |                          |
| [`crypto_kx_keypair`](keyexchange#crypto_kx_keypair)                                                                   | ![sodium-native][node] |                          |
| [`crypto_kx_PRIMITIVE`](keyexchange#constants)                                                                         | ![sodium-native][node] |                          |
| [`crypto_kx_PUBLICKEYBYTES`](keyexchange#constants)                                                                    | ![sodium-native][node] |                          |
| [`crypto_kx_SECRETKEYBYTES`](keyexchange#constants)                                                                    | ![sodium-native][node] |                          |
| [`crypto_kx_seed_keypair`](keyexchange#crypto_kx_seed_keypair)                                                         | ![sodium-native][node] |                          |
| [`crypto_kx_SEEDBYTES`](keyexchange#constants)                                                                         | ![sodium-native][node] |                          |
| [`crypto_kx_server_session_keys`](keyexchange#crypto_kx_server_session_keys)                                           | ![sodium-native][node] |                          |
| [`crypto_kx_SESSIONKEYBYTES`](keyexchange#constants)                                                                   | ![sodium-native][node] |                          |
| [`crypto_onetimeauth`](onetimeauthentication#crypto_onetimeauth)                                                       | ![sodium-native][node] |                          |
| [`crypto_onetimeauth_BYTES`](onetimeauthentication#constants)                                                          | ![sodium-native][node] |                          |
| [`crypto_onetimeauth_KEYBYTES`](onetimeauthentication#constants)                                                       | ![sodium-native][node] |                          |
| [`crypto_onetimeauth_PRIMITIVE`](onetimeauthentication#constants)                                                      | ![sodium-native][node] |                          |
| [`crypto_onetimeauth_verify`](onetimeauthentication#crypto_onetimeauth_verify)                                         | ![sodium-native][node] |                          |
| [`crypto_pwhash`](passwordhashing#crypto_pwhash)                                                                       | ![sodium-native][node] |                          |
| [`crypto_pwhash_ALG_ARGON2I13`](passwordhashing#crypto_pwhash)                                                         | ![sodium-native][node] |                          |
| [`crypto_pwhash_ALG_ARGON2ID13`](passwordhashing#crypto_pwhash)                                                        | ![sodium-native][node] |                          |
| [`crypto_pwhash_ALG_DEFAULT`](passwordhashing#crypto_pwhash)                                                           | ![sodium-native][node] |                          |
| [`crypto_pwhash_BYTES_MAX`](passwordhashing#constants)                                                                 | ![sodium-native][node] |                          |
| [`crypto_pwhash_BYTES_MIN`](passwordhashing#constants)                                                                 | ![sodium-native][node] |                          |
| [`crypto_pwhash_PRIMITIVE`](passwordhashing#constants)                                                                 | ![sodium-native][node] |                          |
| [`crypto_pwhash_SALTBYTES`](passwordhashing#constants)                                                                 | ![sodium-native][node] |                          |
| [`crypto_pwhash_str`](passwordhashing#crypto_pwhash_str)                                                               | ![sodium-native][node] |                          |
| [`crypto_pwhash_str_needs_rehash`](passwordhashing#crypto_pwhash_str_needs_rehash)                                     | ![sodium-native][node] |                          |
| [`crypto_pwhash_str_verify`](passwordhashing#crypto_pwhash_str_verify)                                                 | ![sodium-native][node] |                          |
| [`crypto_pwhash_STRBYTES`](passwordhashing#constants)                                                                  | ![sodium-native][node] |                          |
| [`crypto_pwhash_STRPREFIX`](passwordhasing#constants)                                                                  | ![sodium-native][node] |                          |
| [`crypto_scalarmult`](finitefieldarithmetic)                                                                           | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_scalarmult_base`](finitefieldarithmetic)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_scalarmult_BYTES`](finitefieldarithmetic#constants)                                                           | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_scalarmult_ed25519`](finitefieldarithmetic#crypto_scalarmult_ed25519)                                         | ![sodium-native][node] |                          |
| [`crypto_scalarmult_ed25519_base`](finitefieldarithmetic#crypto_scalarmult_ed25519_base)                               | ![sodium-native][node] |                          |
| [`crypto_scalarmult_ed25519_BYTES`](finitefieldarithmetic#constants)                                                   | ![sodium-native][node] |                          |
| [`crypto_scalarmult_ed25519_SCALARBYTES`](finitefieldarithmetic#constants)                                             | ![sodium-native][node] |                          |
| [`crypto_scalarmult_PRIMITIVE`](finitefieldarithmetic#constants)                                                       | ![sodium-native][node] |                          |
| [`crypto_scalarmult_SCALARBYTES`](finitefieldarithmetic#constants)                                                     | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_detached`](secretkeyboxencryption#crypto_secretbox_detached)                                        | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_easy`](secretkeyboxencryption#crypto_secretbox_easy)                                                | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_KEYBYTES`](secretkeyboxencryption#constants)                                                        | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_MACBYTES`](secretkeyboxencryption#constants)                                                        | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_NONCEBYTES`](secretkeyboxencryption#constants)                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_open_detached`](secretkeyboxencryption#crypto_secretbox_open_detached)                              | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_open_easy`](secretkeyboxencryption#crypto_secretbox_open_easy)                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_secretbox_PRIMITIVE`](secretkeyboxencryption#constants)                                                       | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_ABYTES`](streamencryption#constants)                                           | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_HEADERBYTES`](streamencryption#constants)                                      | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_init_pull`](streamencryption#crypto_secretstream_xchacha20poly1305_init_pull)  | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_init_push`](streamencryption#crypto_secretstream_xchacha20poly1305_init_push)  | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_KEYBYTES`](streamencryption#constants)                                         | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_keygen`](streamencryption#crypto_secretstream_xchacha20poly1305_keygen)        | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_MESSAGEBYTES_MAX`](streamencryption#constants)                                 | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_pull`](streamencryption#crypto_secretstream_xchacha20poly1305_pull)            | ![sodium-native][node] |                          | 
| [`crypto_secretstream_xchacha20poly1305_push`](streamencryption#crypto_secretstream_xchacha20poly1305_push)            | ![sodium-native][node] |                          |
| [`crypto_secretstream_xchacha20poly1305_rekey`](streamencryption#crypto_secretstream_xchacha20poly1305_rekey)          | ![sodium-native][node] |                          |
| [`crypto_shorthash`](shorthashes#crypto_shorthash)                                                                     | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_shorthash_BYTES`](shorthashes#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_shorthash_KEYBYTES`](shorthashes#constants)                                                                   | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_shorthash_PRIMITIVE`](shorthashes#constants)                                                                  | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign`](signing#crypto_sign)                                                                                   | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_BYTES`](signing#constants)                                                                               | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_detached`](signing#crypt_sign_detached)                                                                  | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_ed25519_pk_to_curve25519`](signing#crypto_sign_ed25519_pk_to_curve25519)                                 | ![sodium-native][node] |                          |
| [`crypto_sign_ed25519_sk_to_curve25519`](signing#crypto_sign_ed25519_sk_to_curve25519)                                 | ![sodium-native][node] |                          |
| [`crypto_sign_keypair`](signing#crypto_sign_keypair)                                                                   | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_open`](signing#crypto_sign_open)                                                                         | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_PUBLICKEYBYTES`](signing#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_SECRETKEYBYTES`](signing#constants)                                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_seed_keypair`](signing#crypto_sign_seed_keypair)                                                         | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_SEEDBYTES`](signing#constants)                                                                           | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_sign_verify_detached`](signing#crypto_sign_verify_detached)                                                   | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_stream`](nonauthstreamingencryption#crypto_stream)                                                            | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_stream_chacha20_KEYBYTES`](nonauthstreamingencryption)                                                        | ![sodium-native][node] |                          |
| [`crypto_stream_chacha20_NONCEBYTES`](nonauthstreamingencryption)                                                      | ![sodium-native][node] |                          |
| [`crypto_stream_chacha20_xor`](nonauthstreamingencryption#crypto_stream_chacha20_xor)                                  | ![sodium-native][node] |                          |
| [`crypto_stream_KEYBYTES`](nonauthstreamingencryption#constants)                                                       | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_stream_NONCEBYTES`](nonauthstreamingencryption#constants)                                                     | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_stream_PRIMITIVE`](nonauthstreamingencryption#constants)                                                      | ![sodium-native][node] | ![sodium-javascript][js] |
| [`crypto_stream_xor`](nonauthstreamingencryption#crypto_stream_xor)                                                    | ![sodium-native][node] | ![sodium-javascript][js] |
| [`randombytes_buf`](generatingrandomdata#randombytes_buf)                                                              | ![sodium-native][node] | ![sodium-javascript][js] |
| [`randombytes_buf_deterministic`](generatingrandomdata#randombytes_buf_deterministic)                                  | ![sodium-native][node] |                          |
| [`randombytes_random`](generatingrandomdata#randombytes_random)                                                        | ![sodium-native][node] |                          |
| [`randombytes_SEEDBYTES`](generatingrandomdata#constants)                                                              | ![sodium-native][node] |                          |
| [`randombytes_uniform`](generatingrandomdata#randombytes_uniform)                                                      | ![sodium-native][node] |                          |
| [`sodium_add`](helpers#sodium_add)                                                                                     | ![sodium-native][node] |                          |
| [`sodium_compare`](helpers#sodium_compare)                                                                             | ![sodium-native][node] |                          |
| [`sodium_increment`](helpers#sodium_increment)                                                                         | ![sodium-native][node] |                          |
| [`sodium_is_zero`](helpers#sodium_is_zero)                                                                             | ![sodium-native][node] |                          |
| [`sodium_malloc`](memoryprotection#sodium_malloc)                                                                      | ![sodium-native][node] |                          |
| [`sodium_memcmp`](helpers#sodium_memcmp)                                                                               | ![sodium-native][node] |                          |
| [`sodium_memzero`](memoryprotection#sodium_memzero)                                                                    | ![sodium-native][node] |                          |
| [`sodium_mlock`](memoryprotection#sodium_mlock)                                                                        | ![sodium-native][node] |                          |
| [`sodium_mprotect_noaccess`](memoryprotection#sodium_mprotect_noaccess)                                                | ![sodium-native][node] |                          |
| [`sodium_mprotect_readonly`](memoryprotection#sodium_mprotect_readonly)                                                | ![sodium-native][node] |                          |
| [`sodium_mprotect_readwrite`](memoryprotection#sodium_mprotect_readwrite)                                              | ![sodium-native][node] |                          |
| [`sodium_munlock`](memoryprotection#sodium_munlock)                                                                    | ![sodium-native][node] |                          |
| [`sodium_pad`](padding#sodium_pad)                                                                                     | ![sodium-native][node] |                          |
| [`sodium_unpad`](padding#sodium_unpad)                                                                                 | ![sodium-native][node] |                          |


[js]: /docs/img/icon_js.svg
[node]: /docs/img/nodejs-icon.svg
