# Function: <code>ecryptfs_write_header_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306470)
Location: fs/ecryptfs/crypto.c:1053
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81306470-ffffffff8130649e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133a962)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8133a830-ffffffff8133a85e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813506ff)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813505d0-ffffffff813505fe: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365214)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813650e0-ffffffff8136510e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81389ee4)
Location: fs/ecryptfs/crypto.c:1030
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81389db0-ffffffff81389dde: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813b8d4b)
Location: fs/ecryptfs/crypto.c:1030
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813b8c10-ffffffff813b8c3e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813d22bb)
Location: fs/ecryptfs/crypto.c:1030
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813d2180-ffffffff813d21ae: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813fcd18)
Location: fs/ecryptfs/crypto.c:1015
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813fcbe0-ffffffff813fcc0e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81416bf8)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81416ac0-ffffffff81416aee: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81463eb6)
Location: fs/ecryptfs/crypto.c:1002
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814650b0-ffffffff814650de: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8147f676)
Location: fs/ecryptfs/crypto.c:1002
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81480950-ffffffff8148097e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814862df)
Location: fs/ecryptfs/crypto.c:997
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814861a0-ffffffff814861ce: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814dda6f)
Location: fs/ecryptfs/crypto.c:997
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814dd930-ffffffff814dd95e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8156bb40)
Location: fs/ecryptfs/crypto.c:997
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8156b9e0-ffffffff8156ba1f: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160fb70)
Location: fs/ecryptfs/crypto.c:997
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8160fa00-ffffffff8160fa3f: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81647a00)
Location: fs/ecryptfs/crypto.c:973
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81647890-ffffffff816478cf: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81680eb0)
Location: fs/ecryptfs/crypto.c:973
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81680d40-ffffffff81680d7f: ecryptfs_write_header_metadata (STB_GLOBAL)
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
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f8198)
Location: fs/ecryptfs/crypto.c:1017
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffff8000104f8198-ffff8000104f81f8: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b5b64)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c06b59ac-c06b5a0c: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063a130)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c000000000639f90-c000000000639fc4: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000366c46)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffe000366a8e-ffffffe000366b04: ecryptfs_write_header_metadata (STB_GLOBAL)
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
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140f1d8)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140f0a0-ffffffff8140f0ce: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813ffc58)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813ffb20-ffffffff813ffb4e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140c558)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140c420-ffffffff8140c44e: ecryptfs_write_header_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ecryptfs_write_header_metadata(char *virt, struct ecryptfs_crypt_stat *crypt_stat, size_t *written);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814221d8)
Location: fs/ecryptfs/crypto.c:1017
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814220a0-ffffffff814220ce: ecryptfs_write_header_metadata (STB_GLOBAL)
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
