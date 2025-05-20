# Function: <code>__ecryptfs_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813030f0)
Location: fs/ecryptfs/main.c:86
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/crypto.c:ecryptfs_calculate_md5
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813030f0-ffffffff81303171: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81337070)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81337070-ffffffff813370f1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8134ce40)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8134ce40-ffffffff8134cec1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813619b0)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813619b0-ffffffff81361a30: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81386680)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81386680-ffffffff81386700: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813b5490)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813b5490-ffffffff813b5511: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813ce9b0)
Location: fs/ecryptfs/main.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813ce9b0-ffffffff813cea31: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813f94f0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813f94f0-ffffffff813f9571: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff814133c0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff814133c0-ffffffff81413441: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81461570)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init_kmem_caches
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81461570-ffffffff814615f1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8147d040)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init_kmem_caches
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:write_tag_66_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:write_tag_64_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8147d040-ffffffff8147d0c1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81482bd0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81482bd0-ffffffff81482c51: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff814da350)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:parse_tag_65_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff814da350-ffffffff814da3d1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81567ca0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_67_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
```
**Symbols:**

```
ffffffff81567ca0-ffffffff81567d3d: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8160b440)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_67_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
```
**Symbols:**

```
ffffffff8160b440-ffffffff8160b4dd: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81643300)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_67_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
```
**Symbols:**

```
ffffffff81643300-ffffffff8164339d: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8167c890)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:parse_tag_67_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_length
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
```
**Symbols:**

```
ffffffff8167c890-ffffffff8167c92d: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffff8000104f4750)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffff8000104f4750-ffff8000104f4800: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c06b20f4)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
c06b20f4-c06b2180: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c000000000634f20)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
c000000000634f20-c000000000634fa4: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffe000363a22)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffe000363a22-ffffffe000363a8c: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8140b9a0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8140b9a0-ffffffff8140ba21: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813fc420)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813fc420-ffffffff813fc4a1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81408d20)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81408d20-ffffffff81408da1: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ecryptfs_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8141e9e0)
Location: fs/ecryptfs/main.c:71
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_filldir
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/crypto.c:ecryptfs_decode_and_decrypt_filename
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_cipher_code_to_string
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8141e9e0-ffffffff8141ea61: __ecryptfs_printk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
