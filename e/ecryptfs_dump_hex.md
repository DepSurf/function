# Function: <code>ecryptfs_dump_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8130b090)
Location: fs/ecryptfs/debug.c:98
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8130b090-ffffffff8130b122: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8133f2f0)
Location: fs/ecryptfs/debug.c:98
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8133f2f0-ffffffff8133f382: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81355070)
Location: fs/ecryptfs/debug.c:98
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81355070-ffffffff81355102: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81369e60)
Location: fs/ecryptfs/debug.c:98
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81369c30-ffffffff81369cdd: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81369f30-ffffffff81369f4c: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8138ea23)
Location: fs/ecryptfs/debug.c:98
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8138e7f0-ffffffff8138e89d: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff8138eaf0-ffffffff8138eb0c: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (0)
Location: fs/ecryptfs/debug.c:98
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813bdb35-ffffffff813bdbb0: ecryptfs_dump_hex.cold.0 (STB_LOCAL)
ffffffff813bd8b0-ffffffff813bd8e9: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (0)
Location: fs/ecryptfs/debug.c:98
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff813d7175-ffffffff813d71f0: ecryptfs_dump_hex.cold.0 (STB_LOCAL)
ffffffff813d6ef0-ffffffff813d6f29: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81401a6a)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff814018b0-ffffffff814018e9: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81401b40-ffffffff81401b5b: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8141b95a)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff8141b7a0-ffffffff8141b7d9: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff8141ba30-ffffffff8141ba4b: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8146a413)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8146a530-ffffffff8146a574: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81484e83)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81484fa0-ffffffff81484fe4: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8148a933)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8148aa50-ffffffff8148aa94: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff814e2133)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814e2250-ffffffff814e2294: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81570389)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff815704a0-ffffffff8157050c: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81615289)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff816153b0-ffffffff8161541c: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff8164d319)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8164d440-ffffffff8164d4ac: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81686849)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81686970-ffffffff816869dc: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffff8000104fce24)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffff8000104fcbe8-ffff8000104fcc3c: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffff8000104fce80-ffff8000104fcec4: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (c06ba43c)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
c06ba238-c06ba28c: ecryptfs_dump_hex.part.0 (STB_LOCAL)
c06ba510-c06ba540: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (c00000000063ffac)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
c00000000063fcc0-c00000000063fd1c: ecryptfs_dump_hex.part.0 (STB_LOCAL)
c000000000640030-c000000000640058: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffe00036b49c)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffe00036b292-ffffffe00036b2dc: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffe00036b5fc-ffffffe00036b63a: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81413f3a)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81413d80-ffffffff81413db9: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81414010-ffffffff8141402b: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff814049ba)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81404800-ffffffff81404839: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81404a90-ffffffff81404aab: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff814112ba)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81411100-ffffffff81411139: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81411390-ffffffff814113ab: ecryptfs_dump_hex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ecryptfs_dump_hex(char *data, int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/debug.c (ffffffff81426f2a)
Location: fs/ecryptfs/debug.c:84
Inline: True
Inline callers:
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
  - fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok
```
**Symbols:**

```
ffffffff81426d70-ffffffff81426da9: ecryptfs_dump_hex.part.0 (STB_LOCAL)
ffffffff81427000-ffffffff8142701b: ecryptfs_dump_hex (STB_GLOBAL)
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
