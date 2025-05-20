# Function: <code>ecryptfs_get_tfm_and_mutex_for_cipher_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_blkcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306f70)
Location: fs/ecryptfs/crypto.c:1750
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
**Symbols:**

```
ffffffff81306f70-ffffffff8130702c: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133b190)
Location: fs/ecryptfs/crypto.c:1741
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8133b190-ffffffff8133b24c: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350f20)
Location: fs/ecryptfs/crypto.c:1741
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81350f20-ffffffff81350fdc: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365a50)
Location: fs/ecryptfs/crypto.c:1741
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81365a50-ffffffff81365b0c: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a710)
Location: fs/ecryptfs/crypto.c:1718
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8138a710-ffffffff8138a7cc: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1718
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813b9ccb-ffffffff813b9cde: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold.38 (STB_LOCAL)
ffffffff813b93f0-ffffffff813b94a1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1718
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813d327a-ffffffff813d328d: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold.36 (STB_LOCAL)
ffffffff813d2960-ffffffff813d2a11: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1712
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff813fdd77-ffffffff813fdd8a: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff813fd400-ffffffff813fd4b1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81417c63-ffffffff81417c76: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff814172e0-ffffffff81417391: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1699
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff814661d7-ffffffff814661ea: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff81465960-ffffffff81465a11: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1699
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81bee98e-ffffffff81bee9a1: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff81481200-ffffffff814812b1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1693
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81be0a64-ffffffff81be0a77: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff81486ba0-ffffffff81486c51: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1693
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81cd1201-ffffffff81cd1214: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff814de330-ffffffff814de3e1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1693
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81e843cb-ffffffff81e843de: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff8156c380-ffffffff8156c443: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816105c0)
Location: fs/ecryptfs/crypto.c:1693
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff816105c0-ffffffff8161068e: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81648440)
Location: fs/ecryptfs/crypto.c:1669
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81648440-ffffffff8164850e: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816818f0)
Location: fs/ecryptfs/crypto.c:1669
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff816818f0-ffffffff816819be: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f8df0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffff8000104f8df0-ffff8000104f8ec8: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b6694)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
c06b6694-c06b6764: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063aea0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
c00000000063aea0-c00000000063afb8: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000367684)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffe000367684-ffffffe000367722: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81410243-ffffffff81410256: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff8140f8c0-ffffffff8140f971: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff81400cc3-ffffffff81400cd6: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff81400340-ffffffff814003f1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8140d5c3-ffffffff8140d5d6: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff8140cc40-ffffffff8140ccf1: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher **tfm, struct mutex **tfm_mutex, char *cipher_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1714
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
**Symbols:**

```
ffffffff8142323c-ffffffff8142324f: ecryptfs_get_tfm_and_mutex_for_cipher_name.cold (STB_LOCAL)
ffffffff814228c0-ffffffff81422971: ecryptfs_get_tfm_and_mutex_for_cipher_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct crypto_blkcipher **tfm</code> ➡️ <code>struct crypto_skcipher **tfm</code>
</li>
</ul>
</details>
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
