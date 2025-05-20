# Function: <code>fscrypt_hash_inode_number</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a4b70)
Location: fs/crypto/keysetup.c:228
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff813a4b70-ffffffff813a4bba: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813abcd0)
Location: fs/crypto/keysetup.c:253
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff813abcd0-ffffffff813abd1a: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:258
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff81cc661d-ffffffff81cc663b: fscrypt_hash_inode_number.cold (STB_LOCAL)
ffffffff813fb5a0-ffffffff813fb5fc: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:259
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff81e78a94-ffffffff81e78ab2: fscrypt_hash_inode_number.cold (STB_LOCAL)
ffffffff8146e950-ffffffff8146e9b6: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:282
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff8206a6a2-ffffffff8206a6c0: fscrypt_hash_inode_number.cold (STB_LOCAL)
ffffffff81500080-ffffffff815000e6: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:282
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff820ea4b0-ffffffff820ea4ce: fscrypt_hash_inode_number.cold (STB_LOCAL)
ffffffff81537650-ffffffff815376b6: fscrypt_hash_inode_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fscrypt_hash_inode_number(struct fscrypt_inode_info *ci, const struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:283
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/policy.c:fscrypt_set_context
```
**Symbols:**

```
ffffffff821c7011-ffffffff821c702f: fscrypt_hash_inode_number.cold (STB_LOCAL)
ffffffff8156c720-ffffffff8156c786: fscrypt_hash_inode_number (STB_GLOBAL)
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
