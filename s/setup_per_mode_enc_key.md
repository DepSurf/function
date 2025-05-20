# Function: <code>setup_per_mode_enc_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct crypto_skcipher **tfms, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:126
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key
```
**Symbols:**

```
ffffffff813934d0-ffffffff81393658: setup_per_mode_enc_key (STB_LOCAL)
ffffffff81393f5b-ffffffff81393f67: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:158
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key
```
**Symbols:**

```
ffffffff813a4830-ffffffff813a4a5a: setup_per_mode_enc_key (STB_LOCAL)
ffffffff81beaf46-ffffffff81beaf52: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:158
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff813aba60-ffffffff813abc35: setup_per_mode_enc_key (STB_LOCAL)
ffffffff81bdcf9f-ffffffff81bdcfab: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:163
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff813fb310-ffffffff813fb509: setup_per_mode_enc_key (STB_LOCAL)
ffffffff81cc659f-ffffffff81cc661d: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:164
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff8146e660-ffffffff8146e896: setup_per_mode_enc_key (STB_LOCAL)
ffffffff81e78a0e-ffffffff81e78a94: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:187
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff814ffd30-ffffffff814fff63: setup_per_mode_enc_key (STB_LOCAL)
ffffffff8206a620-ffffffff8206a6a2: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:187
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff81537300-ffffffff81537533: setup_per_mode_enc_key (STB_LOCAL)
ffffffff820ea42e-ffffffff820ea4b0: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int setup_per_mode_enc_key(struct fscrypt_inode_info *ci, struct fscrypt_master_key *mk, struct fscrypt_prepared_key *keys, u8 hkdf_context, bool include_fs_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:188
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
**Symbols:**

```
ffffffff8156c3d0-ffffffff8156c603: setup_per_mode_enc_key (STB_LOCAL)
ffffffff821c6f8f-ffffffff821c7011: setup_per_mode_enc_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_prepared_key *keys</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_skcipher **tfms</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_info *ci</code> ➡️ <code>struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
</li>
</ul>
