# Function: <code>fscrypt_zeroout_range_inline_crypt</code>

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
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813a6b60)
Location: fs/crypto/bio.c:44
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813a6b60-ffffffff813a6dab: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813adbf0)
Location: fs/crypto/bio.c:44
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813adbf0-ffffffff813ade12: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:44
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813fd570-ffffffff813fd7b5: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
ffffffff81cc6a15-ffffffff81cc6a70: fscrypt_zeroout_range_inline_crypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:46
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81470db0-ffffffff81470f96: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
ffffffff81e78e45-ffffffff81e78e9b: fscrypt_zeroout_range_inline_crypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:50
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81502890-ffffffff81502a76: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
ffffffff8206a743-ffffffff8206a799: fscrypt_zeroout_range_inline_crypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:48
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81539e50-ffffffff8153a05d: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
ffffffff820ea551-ffffffff820ea5a7: fscrypt_zeroout_range_inline_crypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range_inline_crypt(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:48
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8156f190-ffffffff8156f39d: fscrypt_zeroout_range_inline_crypt (STB_LOCAL)
ffffffff821c70f2-ffffffff821c7148: fscrypt_zeroout_range_inline_crypt.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
