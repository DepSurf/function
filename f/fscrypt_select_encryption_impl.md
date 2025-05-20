# Function: <code>fscrypt_select_encryption_impl</code>

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
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a7540)
Location: fs/crypto/inline_crypt.c:67
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813a7540-ffffffff813a76e3: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae590)
Location: fs/crypto/inline_crypt.c:67
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813ae590-ffffffff813ae722: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813fe130)
Location: fs/crypto/inline_crypt.c:67
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813fe130-ffffffff813fe2cc: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:97
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81e790d7-ffffffff81e790ff: fscrypt_select_encryption_impl.cold (STB_LOCAL)
ffffffff81471c00-ffffffff81471dfb: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81503810)
Location: fs/crypto/inline_crypt.c:93
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81503810-ffffffff815039a6: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153b0c0)
Location: fs/crypto/inline_crypt.c:93
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8153b0c0-ffffffff8153b253: fscrypt_select_encryption_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_select_encryption_impl(struct fscrypt_inode_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:92
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff821c746e-ffffffff821c748e: fscrypt_select_encryption_impl.cold (STB_LOCAL)
ffffffff81570340-ffffffff815704e8: fscrypt_select_encryption_impl (STB_GLOBAL)
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
