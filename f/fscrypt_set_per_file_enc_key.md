# Function: <code>fscrypt_set_per_file_enc_key</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81393823)
Location: fs/crypto/keysetup.c:113
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:setup_v1_file_key_derived
```
**Symbols:**

```
ffffffff81393e70-ffffffff81393ea1: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a4d8e)
Location: fs/crypto/keysetup.c:152
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:setup_v1_file_key_derived
```
**Symbols:**

```
ffffffff813a4ae0-ffffffff813a4b27: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813abe3f)
Location: fs/crypto/keysetup.c:152
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813abc70-ffffffff813abc87: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813fb72b)
Location: fs/crypto/keysetup.c:157
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813fb540-ffffffff813fb557: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146eb0a)
Location: fs/crypto/keysetup.c:158
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8146e8d0-ffffffff8146e8f1: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8150024b)
Location: fs/crypto/keysetup.c:181
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff814fffe0-ffffffff81500001: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8153781b)
Location: fs/crypto/keysetup.c:181
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff815375b0-ffffffff815375d1: fscrypt_set_per_file_enc_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_set_per_file_enc_key(struct fscrypt_inode_info *ci, const u8 *raw_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156c8eb)
Location: fs/crypto/keysetup.c:181
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8156c680-ffffffff8156c6a1: fscrypt_set_per_file_enc_key (STB_GLOBAL)
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
