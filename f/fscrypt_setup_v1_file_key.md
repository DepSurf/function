# Function: <code>fscrypt_setup_v1_file_key</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8134e86a-ffffffff8134e8b1: fscrypt_setup_v1_file_key.cold (STB_LOCAL)
ffffffff8134e5a0-ffffffff8134e732: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813946d6)
Location: fs/crypto/keysetup_v1.c:292
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81394620-ffffffff81394661: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813a5baa)
Location: fs/crypto/keysetup_v1.c:290
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813a5af0-ffffffff813a5b3a: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813acb50)
Location: fs/crypto/keysetup_v1.c:290
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813acb50-ffffffff813acbfd: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813fc4c0)
Location: fs/crypto/keysetup_v1.c:290
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813fc4c0-ffffffff813fc56d: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8146f970)
Location: fs/crypto/keysetup_v1.c:290
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8146f970-ffffffff8146fa2f: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81501160)
Location: fs/crypto/keysetup_v1.c:292
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81501160-ffffffff8150121f: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff815387f0)
Location: fs/crypto/keysetup_v1.c:292
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff815387f0-ffffffff815388af: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_inode_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8156d970)
Location: fs/crypto/keysetup_v1.c:293
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8156d970-ffffffff8156da2f: fscrypt_setup_v1_file_key (STB_GLOBAL)
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
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f950)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffff80001040f950-ffff80001040fb30: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dc200)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
c05dc200-c05dc598: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051d350)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
c00000000051d350-c00000000051d614: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b841a)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffe0002b841a-ffffffe0002b873a: fscrypt_setup_v1_file_key (STB_GLOBAL)
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
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81346e4a-ffffffff81346e91: fscrypt_setup_v1_file_key.cold (STB_LOCAL)
ffffffff81346b80-ffffffff81346d12: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81337b2a-ffffffff81337b71: fscrypt_setup_v1_file_key.cold (STB_LOCAL)
ffffffff81337860-ffffffff813379f2: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff8134491a-ffffffff81344961: fscrypt_setup_v1_file_key.cold (STB_LOCAL)
ffffffff81344650-ffffffff813447e2: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v1_file_key(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup_v1.c (0)
Location: fs/crypto/keysetup_v1.c:311
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff81357bfa-ffffffff81357c41: fscrypt_setup_v1_file_key.cold (STB_LOCAL)
ffffffff81357930-ffffffff81357ac2: fscrypt_setup_v1_file_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
