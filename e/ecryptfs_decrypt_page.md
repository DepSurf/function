# Function: <code>ecryptfs_decrypt_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81305d70)
Location: fs/ecryptfs/crypto.c:554
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
**Symbols:**

```
ffffffff81305d70-ffffffff81305e9e: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133a060)
Location: fs/ecryptfs/crypto.c:547
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8133a060-ffffffff8133a189: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8134fe00)
Location: fs/ecryptfs/crypto.c:547
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8134fe00-ffffffff8134ff26: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813648b0)
Location: fs/ecryptfs/crypto.c:547
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813648b0-ffffffff813649d1: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813895d0)
Location: fs/ecryptfs/crypto.c:533
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813895d0-ffffffff813896f1: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:533
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813b9adc-ffffffff813b9afc: ecryptfs_decrypt_page.cold.31 (STB_LOCAL)
ffffffff813b8400-ffffffff813b84f9: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:533
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813d305e-ffffffff813d307e: ecryptfs_decrypt_page.cold.29 (STB_LOCAL)
ffffffff813d1980-ffffffff813d1a79: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:519
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813fdb1d-ffffffff813fdb37: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff813fc4b0-ffffffff813fc5a6: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81417a09-ffffffff81417a23: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff81416390-ffffffff81416486: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:506
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81465fe9-ffffffff81466003: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff81464930-ffffffff81464a27: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:506
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81bee758-ffffffff81bee772: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff814800f0-ffffffff814801e7: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:502
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81be0791-ffffffff81be07ab: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff81485940-ffffffff81485a37: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:502
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81cd0f2e-ffffffff81cd0f48: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff814dd060-ffffffff814dd157: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:502
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff81e84162-ffffffff81e8417c: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff8156b060-ffffffff8156b173: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160ef20)
Location: fs/ecryptfs/crypto.c:502
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff8160ef20-ffffffff8160f046: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81646db0)
Location: fs/ecryptfs/crypto.c:478
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff81646db0-ffffffff81646ed6: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81680270)
Location: fs/ecryptfs/crypto.c:478
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff81680270-ffffffff8168038e: ecryptfs_decrypt_page (STB_GLOBAL)
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
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f7978)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffff8000104f7978-ffff8000104f7ab0: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b524c)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
c06b524c-c06b536c: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c0000000006390f0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
c0000000006390f0-c000000000639298: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe0003663a2)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffe0003663a2-ffffffe0003664a0: ecryptfs_decrypt_page (STB_GLOBAL)
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
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8140ffe9-ffffffff81410003: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff8140e970-ffffffff8140ea66: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81400a69-ffffffff81400a83: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff813ff3f0-ffffffff813ff4e6: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8140d369-ffffffff8140d383: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff8140bcf0-ffffffff8140bde6: ecryptfs_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:521
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81422fe2-ffffffff81422ffc: ecryptfs_decrypt_page.cold (STB_LOCAL)
ffffffff81421980-ffffffff81421a6f: ecryptfs_decrypt_page (STB_GLOBAL)
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
