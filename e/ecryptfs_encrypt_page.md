# Function: <code>ecryptfs_encrypt_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81305c00)
Location: fs/ecryptfs/crypto.c:485
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81305c00-ffffffff81305d6b: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81339ef0)
Location: fs/ecryptfs/crypto.c:478
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81339ef0-ffffffff8133a054: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8134fc90)
Location: fs/ecryptfs/crypto.c:478
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff8134fc90-ffffffff8134fdf1: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81364740)
Location: fs/ecryptfs/crypto.c:478
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81364740-ffffffff813648a1: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81389460)
Location: fs/ecryptfs/crypto.c:464
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81389460-ffffffff813895c1: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:464
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff813b9abc-ffffffff813b9adc: ecryptfs_encrypt_page.cold.30 (STB_LOCAL)
ffffffff813b82c0-ffffffff813b83fc: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:464
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff813d303e-ffffffff813d305e: ecryptfs_encrypt_page.cold.28 (STB_LOCAL)
ffffffff813d1840-ffffffff813d197c: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:450
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff813fdafc-ffffffff813fdb1d: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff813fc360-ffffffff813fc4a9: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff814179e8-ffffffff81417a09: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff81416240-ffffffff81416389: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:437
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81465fc8-ffffffff81465fe9: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff814647e0-ffffffff8146492a: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:437
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81bee737-ffffffff81bee758: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff8147ffa0-ffffffff814800ea: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:433
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81be0770-ffffffff81be0791: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff814857f0-ffffffff8148593a: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:433
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81cd0f0d-ffffffff81cd0f2e: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff814dcf10-ffffffff814dd05a: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:433
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81e84144-ffffffff81e84162: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff8156af10-ffffffff8156b05e: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160eda0)
Location: fs/ecryptfs/crypto.c:433
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff8160eda0-ffffffff8160ef10: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81646c30)
Location: fs/ecryptfs/crypto.c:409
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81646c30-ffffffff81646da0: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816800f0)
Location: fs/ecryptfs/crypto.c:409
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff816800f0-ffffffff81680255: ecryptfs_encrypt_page (STB_GLOBAL)
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
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f7800)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffff8000104f7800-ffff8000104f7974: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b50ac)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
c06b50ac-c06b524c: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c000000000638f20)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
c000000000638f20-c0000000006390f0: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe00036625a)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffe00036625a-ffffffe0003663a2: ecryptfs_encrypt_page (STB_GLOBAL)
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
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff8140ffc8-ffffffff8140ffe9: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff8140e820-ffffffff8140e969: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81400a48-ffffffff81400a69: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff813ff2a0-ffffffff813ff3e9: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff8140d348-ffffffff8140d369: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff8140bba0-ffffffff8140bce9: ecryptfs_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:452
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
**Symbols:**

```
ffffffff81422fc8-ffffffff81422fe2: ecryptfs_encrypt_page.cold (STB_LOCAL)
ffffffff81421840-ffffffff81421979: ecryptfs_encrypt_page (STB_GLOBAL)
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
