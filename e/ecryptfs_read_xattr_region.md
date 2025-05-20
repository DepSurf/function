# Function: <code>ecryptfs_read_xattr_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306990)
Location: fs/ecryptfs/crypto.c:1372
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81306990-ffffffff813069ec: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133ab60)
Location: fs/ecryptfs/crypto.c:1366
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff8133ab60-ffffffff8133abc7: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813508f0)
Location: fs/ecryptfs/crypto.c:1366
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff813508f0-ffffffff81350957: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365400)
Location: fs/ecryptfs/crypto.c:1366
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81365400-ffffffff81365467: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a0d0)
Location: fs/ecryptfs/crypto.c:1350
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff8138a0d0-ffffffff8138a137: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1350
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff813b9baf-ffffffff813b9bca: ecryptfs_read_xattr_region.cold.35 (STB_LOCAL)
ffffffff813b8ec0-ffffffff813b8f15: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1350
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff813d315e-ffffffff813d3179: ecryptfs_read_xattr_region.cold.33 (STB_LOCAL)
ffffffff813d2430-ffffffff813d2485: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1342
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff813fdc4b-ffffffff813fdc6b: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff813fced0-ffffffff813fcf21: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81417b37-ffffffff81417b57: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff81416db0-ffffffff81416e01: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81465513)
Location: fs/ecryptfs/crypto.c:1329
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81466102-ffffffff81466122: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff81465310-ffffffff81465361: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81480db3)
Location: fs/ecryptfs/crypto.c:1329
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81bee8b9-ffffffff81bee8d9: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff81480bb0-ffffffff81480c01: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814866a3)
Location: fs/ecryptfs/crypto.c:1324
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81be0904-ffffffff81be0924: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff814864a0-ffffffff814864f1: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814dde33)
Location: fs/ecryptfs/crypto.c:1324
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81cd10a1-ffffffff81cd10c1: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff814ddc30-ffffffff814ddc81: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8156bf45)
Location: fs/ecryptfs/crypto.c:1324
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81e842cf-ffffffff81e842ea: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff8156bd20-ffffffff8156bd8f: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81610075)
Location: fs/ecryptfs/crypto.c:1324
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8160fe10-ffffffff8160fe93: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81647f05)
Location: fs/ecryptfs/crypto.c:1300
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81647ca0-ffffffff81647d26: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816813b5)
Location: fs/ecryptfs/crypto.c:1300
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81681150-ffffffff816811d6: ecryptfs_read_xattr_region (STB_GLOBAL)
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
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f87a0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffff8000104f87a0-ffff8000104f882c: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b6068)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
c06b6068-c06b60f0: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063a410)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
c00000000063a410-c00000000063a4b8: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe0003670ec)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffe0003670ec-ffffffe000367162: ecryptfs_read_xattr_region (STB_GLOBAL)
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
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81410117-ffffffff81410137: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff8140f390-ffffffff8140f3e1: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81400b97-ffffffff81400bb7: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff813ffe10-ffffffff813ffe61: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff8140d497-ffffffff8140d4b7: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff8140c710-ffffffff8140c761: ecryptfs_read_xattr_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_xattr_region(char *page_virt, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1344
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
```
**Symbols:**

```
ffffffff81423110-ffffffff81423130: ecryptfs_read_xattr_region.cold (STB_LOCAL)
ffffffff81422390-ffffffff814223e1: ecryptfs_read_xattr_region (STB_GLOBAL)
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
