# Function: <code>ecryptfs_write_crypt_stat_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306310)
Location: fs/ecryptfs/crypto.c:940
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81306310-ffffffff81306369: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133a93c)
Location: fs/ecryptfs/crypto.c:933
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8133a600-ffffffff8133a65a: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813506d9)
Location: fs/ecryptfs/crypto.c:933
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813503a0-ffffffff813503fa: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813651d8)
Location: fs/ecryptfs/crypto.c:933
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81364eb0-ffffffff81364f01: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81389ea8)
Location: fs/ecryptfs/crypto.c:918
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81389b80-ffffffff81389bd1: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813b8d08)
Location: fs/ecryptfs/crypto.c:918
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813b89e0-ffffffff813b8a31: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813d2278)
Location: fs/ecryptfs/crypto.c:918
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813d1f50-ffffffff813d1fa1: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813fccdd)
Location: fs/ecryptfs/crypto.c:901
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813fc9f0-ffffffff813fca2e: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81416bbd)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814168d0-ffffffff8141690e: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81463e79)
Location: fs/ecryptfs/crypto.c:888
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81464e70-ffffffff81464ebc: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8147f639)
Location: fs/ecryptfs/crypto.c:888
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81480650-ffffffff8148069c: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8148629a)
Location: fs/ecryptfs/crypto.c:883
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81485ea0-ffffffff81485eec: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814dda2a)
Location: fs/ecryptfs/crypto.c:883
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814dd5e0-ffffffff814dd62c: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8156bafd)
Location: fs/ecryptfs/crypto.c:883
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8156b630-ffffffff8156b68d: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160fb2d)
Location: fs/ecryptfs/crypto.c:883
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8160f5f0-ffffffff8160f64d: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816479bd)
Location: fs/ecryptfs/crypto.c:859
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81647480-ffffffff816474dd: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81680e6d)
Location: fs/ecryptfs/crypto.c:859
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81680930-ffffffff8168098d: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
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
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f7fd0)
Location: fs/ecryptfs/crypto.c:903
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffff8000104f7fd0-ffff8000104f8044: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b5b20)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c06b5834-c06b5898: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063a0d4)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c000000000639930-c000000000639998: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000366bea)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffe0003668d0-ffffffe00036695a: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140f19d)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140eeb0-ffffffff8140eeee: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813ffc1d)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813ff930-ffffffff813ff96e: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140c51d)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140c230-ffffffff8140c26e: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_crypt_stat_flags(char *page_virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8142219d)
Location: fs/ecryptfs/crypto.c:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81421eb0-ffffffff81421eee: ecryptfs_write_crypt_stat_flags (STB_GLOBAL)
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
