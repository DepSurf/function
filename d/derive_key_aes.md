# Function: <code>derive_key_aes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int derive_key_aes(u8 *deriving_key, u8 *source_key, u8 *derived_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8128a110)
Location: fs/crypto/keyinfo.c:37
Inline: False
```
**Symbols:**

```
ffffffff8128a110-ffffffff8128a2b0: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int derive_key_aes(u8 *deriving_key, u8 *source_key, u8 *derived_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8129ee50)
Location: fs/crypto/keyinfo.c:34
Inline: False
```
**Symbols:**

```
ffffffff8129ee50-ffffffff8129eff0: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int derive_key_aes(u8 *deriving_key, const struct fscrypt_key *source_key, u8 *derived_raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812ad880)
Location: fs/crypto/keyinfo.c:39
Inline: False
```
**Symbols:**

```
ffffffff812ad880-ffffffff812ada49: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int derive_key_aes(u8 *deriving_key, const struct fscrypt_key *source_key, u8 *derived_raw_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812d0d70)
Location: fs/crypto/keyinfo.c:29
Inline: False
```
**Symbols:**

```
ffffffff812d0d70-ffffffff812d0f19: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const struct fscrypt_context *ctx, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812fb8b0)
Location: fs/crypto/keyinfo.c:29
Inline: False
```
**Symbols:**

```
ffffffff812fb8b0-ffffffff812fba6e: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const struct fscrypt_context *ctx, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81310e00)
Location: fs/crypto/keyinfo.c:35
Inline: False
```
**Symbols:**

```
ffffffff81310e00-ffffffff81311002: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const struct fscrypt_context *ctx, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81338580)
Location: fs/crypto/keyinfo.c:34
Inline: False
```
**Symbols:**

```
ffffffff81338580-ffffffff8133871d: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8134e390)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8134e390-ffffffff8134e52f: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81394130)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:setup_v1_file_key_derived
```
**Symbols:**

```
ffffffff81394130-ffffffff813942ca: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813a55f0)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:setup_v1_file_key_derived
```
**Symbols:**

```
ffffffff813a55f0-ffffffff813a578a: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813ac6d0)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813ac6d0-ffffffff813ac86a: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813fc040)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813fc040-ffffffff813fc1da: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8146f460)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8146f460-ffffffff8146f65e: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81500be0)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81500be0-ffffffff81500dde: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81538270)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81538270-ffffffff81538470: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8156d3c0)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8156d3c0-ffffffff8156d5c0: derive_key_aes (STB_LOCAL)
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
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f5a0)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffff80001040f5a0-ffff80001040f75c: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dc2d4)
Location: fs/crypto/keysetup_v1.c:47
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051d010)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
c00000000051d010-c00000000051d254: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b84a2)
Location: fs/crypto/keysetup_v1.c:47
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81346970)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81346970-ffffffff81346b0f: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81337650)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81337650-ffffffff813377ef: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81344440)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81344440-ffffffff813445df: derive_key_aes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int derive_key_aes(const u8 *master_key, const u8 *nonce, u8 *derived_key, unsigned int derived_keysize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81357720)
Location: fs/crypto/keysetup_v1.c:47
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff81357720-ffffffff813578bf: derive_key_aes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *derived_raw_key</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *derived_key</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 *source_key</code> ➡️ <code>const struct fscrypt_key *source_key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 *master_key</code>
</li>
<li>
<b>Param added. </b>
<code>const struct fscrypt_context *ctx</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *derived_key</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int derived_keysize</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *deriving_key</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fscrypt_key *source_key</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *derived_raw_key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 *nonce</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fscrypt_context *ctx</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
