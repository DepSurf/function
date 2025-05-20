# Function: <code>crypt_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81305700)
Location: fs/ecryptfs/crypto.c:426
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
```
**Symbols:**

```
ffffffff81305700-ffffffff81305895: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813399a0)
Location: fs/ecryptfs/crypto.c:419
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813399a0-ffffffff81339b37: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8134f740)
Location: fs/ecryptfs/crypto.c:419
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8134f740-ffffffff8134f8d7: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813641f0)
Location: fs/ecryptfs/crypto.c:419
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813641f0-ffffffff8136438c: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81388f10)
Location: fs/ecryptfs/crypto.c:405
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff81388f10-ffffffff813890ac: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:405
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813b7d80-ffffffff813b7ef3: crypt_extent (STB_LOCAL)
ffffffff813b9a90-ffffffff813b9abc: crypt_extent.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:405
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813d1300-ffffffff813d1473: crypt_extent (STB_LOCAL)
ffffffff813d3012-ffffffff813d303e: crypt_extent.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:391
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813fbe30-ffffffff813fbfa3: crypt_extent (STB_LOCAL)
ffffffff813fdad0-ffffffff813fdafc: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff81415d10-ffffffff81415e83: crypt_extent (STB_LOCAL)
ffffffff814179bc-ffffffff814179e8: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:378
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff814642b0-ffffffff81464422: crypt_extent (STB_LOCAL)
ffffffff81465f9c-ffffffff81465fc8: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:378
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8147fa70-ffffffff8147fbe2: crypt_extent (STB_LOCAL)
ffffffff81bee70b-ffffffff81bee737: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:374
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff814852c0-ffffffff81485432: crypt_extent (STB_LOCAL)
ffffffff81be0744-ffffffff81be0770: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:374
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff814dc9e0-ffffffff814dcb52: crypt_extent (STB_LOCAL)
ffffffff81cd0ee1-ffffffff81cd0f0d: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:374
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8156a930-ffffffff8156ab0b: crypt_extent (STB_LOCAL)
ffffffff81e8411c-ffffffff81e84144: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160e750)
Location: fs/ecryptfs/crypto.c:374
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8160e750-ffffffff8160e94f: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816465e0)
Location: fs/ecryptfs/crypto.c:350
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff816465e0-ffffffff816467df: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8167faa0)
Location: fs/ecryptfs/crypto.c:350
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8167faa0-ffffffff8167fc9f: crypt_extent (STB_LOCAL)
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
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f72d8)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffff8000104f72d8-ffff8000104f745c: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b4a74)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
c06b4a74-c06b4d88: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c000000000638810)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
c000000000638810-c000000000638a08: crypt_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000365dc6)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffe000365dc6-ffffffe000365f00: crypt_extent (STB_LOCAL)
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
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8140e2f0-ffffffff8140e463: crypt_extent (STB_LOCAL)
ffffffff8140ff9c-ffffffff8140ffc8: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff813fed70-ffffffff813feee3: crypt_extent (STB_LOCAL)
ffffffff81400a1c-ffffffff81400a48: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff8140b670-ffffffff8140b7e3: crypt_extent (STB_LOCAL)
ffffffff8140d31c-ffffffff8140d348: crypt_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crypt_extent(struct ecryptfs_crypt_stat *crypt_stat, struct page *dst_page, struct page *src_page, long unsigned int extent_offset, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:393
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
**Symbols:**

```
ffffffff81421310-ffffffff81421483: crypt_extent (STB_LOCAL)
ffffffff81422f9c-ffffffff81422fc8: crypt_extent.cold (STB_LOCAL)
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
