# Function: <code>ext4_mpage_readpages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff812e2e00)
Location: fs/ext4/readpage.c:133
Inline: False
```
**Symbols:**

```
ffffffff812e2e00-ffffffff812e3716: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81312ce0)
Location: fs/ext4/readpage.c:98
Inline: False
```
**Symbols:**

```
ffffffff81312ce0-ffffffff813136e7: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81328c90)
Location: fs/ext4/readpage.c:98
Inline: False
```
**Symbols:**

```
ffffffff81328c90-ffffffff81329682: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff8131e750)
Location: fs/ext4/readpage.c:98
Inline: False
```
**Symbols:**

```
ffffffff8131e750-ffffffff8131f0ca: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81342d90)
Location: fs/ext4/readpage.c:99
Inline: False
```
**Symbols:**

```
ffffffff81342d90-ffffffff81343767: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81370c20)
Location: fs/ext4/readpage.c:99
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff81370c20-ffffffff8137156f: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813890b0)
Location: fs/ext4/readpage.c:99
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813890b0-ffffffff81389a32: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813b3260)
Location: fs/ext4/readpage.c:99
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813b3260-ffffffff813b3c0f: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813cc430)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813cc430-ffffffff813cceee: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff814185b0)
Location: fs/ext4/readpage.c:224
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
```
**Symbols:**

```
ffffffff814185b0-ffffffff81418fff: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff8142c110)
Location: fs/ext4/readpage.c:224
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
```
**Symbols:**

```
ffffffff8142c110-ffffffff8142cb7a: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81432dd0)
Location: fs/ext4/readpage.c:224
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
```
**Symbols:**

```
ffffffff81432dd0-ffffffff81433858: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:224
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
```
**Symbols:**

```
ffffffff81ccceb1-ffffffff81cccfad: ext4_mpage_readpages.cold (STB_LOCAL)
ffffffff814866e0-ffffffff814871f6: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:223
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
```
**Symbols:**

```
ffffffff81e7fd8e-ffffffff81e7feae: ext4_mpage_readpages.cold (STB_LOCAL)
ffffffff81509f50-ffffffff8150ab67: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:221
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
```
**Symbols:**

```
ffffffff82070218-ffffffff8207033b: ext4_mpage_readpages.cold (STB_LOCAL)
ffffffff815a4af0-ffffffff815a56ef: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:218
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
```
**Symbols:**

```
ffffffff820efe98-ffffffff820f0011: ext4_mpage_readpages.cold (STB_LOCAL)
ffffffff815db4c0-ffffffff815dbf63: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_mpage_readpages(struct inode *inode, struct readahead_control *rac, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:211
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
```
**Symbols:**

```
ffffffff821cd058-ffffffff821cd1ce: ext4_mpage_readpages.cold (STB_LOCAL)
ffffffff81613d90-ffffffff8161482d: ext4_mpage_readpages (STB_GLOBAL)
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
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffff8000104a4910)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffff8000104a4910-ffff8000104a51d8: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c0666478)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
c0666478-c0666f70: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c0000000005d1970)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
c0000000005d1970-c0000000005d2410: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffe000325a8c)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffe000325a8c-ffffffe0003261e0: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c4a10)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813c4a10-ffffffff813c54ce: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813b5490)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813b5490-ffffffff813b5f4e: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c1ea0)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813c1ea0-ffffffff813c295e: ext4_mpage_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_mpage_readpages(struct address_space *mapping, struct list_head *pages, struct page *page, unsigned int nr_pages, bool is_readahead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813d7020)
Location: fs/ext4/readpage.c:225
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_readpages
```
**Symbols:**

```
ffffffff813d7020-ffffffff813d7b0f: ext4_mpage_readpages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_readahead</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param added. </b>
<code>struct readahead_control *rac</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *pages</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_readahead</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
