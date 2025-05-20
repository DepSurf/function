# Function: <code>set_bh_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81243020)
Location: fs/buffer.c:1475
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81243020-ffffffff8124302b: set_bh_page.part.17 (STB_LOCAL)
ffffffff81243030-ffffffff81243075: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8126b8b9)
Location: fs/buffer.c:1465
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8126b150-ffffffff8126b15b: set_bh_page.part.17 (STB_LOCAL)
ffffffff8126b160-ffffffff8126b19f: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8127ea28)
Location: fs/buffer.c:1465
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8127e290-ffffffff8127e29b: set_bh_page.part.24 (STB_LOCAL)
ffffffff8127e2a0-ffffffff8127e2d9: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8128c3a5)
Location: fs/buffer.c:1460
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8128be40-ffffffff8128be4b: set_bh_page.part.23 (STB_LOCAL)
ffffffff8128be50-ffffffff8128be89: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812aee7c)
Location: fs/buffer.c:1420
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff812ae930-ffffffff812ae93b: set_bh_page.part.26 (STB_LOCAL)
ffffffff812ae940-ffffffff812ae979: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d64b0)
Location: fs/buffer.c:1391
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff812d64b0-ffffffff812d64e6: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb880)
Location: fs/buffer.c:1399
Inline: True
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff812eb880-ffffffff812eb8b6: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8130d5c8)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8130cf50-ffffffff8130cf5b: set_bh_page.part.0 (STB_LOCAL)
ffffffff8130cf60-ffffffff8130cf99: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81320598)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8131fe30-ffffffff8131fe3b: set_bh_page.part.0 (STB_LOCAL)
ffffffff8131fe40-ffffffff8131fe79: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813599f8)
Location: fs/buffer.c:1444
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813593b0-ffffffff813593ed: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81367ad6)
Location: fs/buffer.c:1443
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81367170-ffffffff813671ad: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136e6db)
Location: fs/buffer.c:1463
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8136db70-ffffffff8136dba7: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bd96d)
Location: fs/buffer.c:1442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813bc690-ffffffff813bc6c7: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8144456d)
Location: fs/buffer.c:1441
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81442910-ffffffff81442951: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d37dd)
Location: fs/buffer.c:1430
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff814d1900-ffffffff814d1941: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81508010)
Location: fs/buffer.c:1542
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81508010-ffffffff81508051: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffff8000103d9218)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffff8000103d7768-ffff8000103d777c: set_bh_page.part.0 (STB_LOCAL)
ffff8000103d7780-ffff8000103d77e4: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b1b2c)
Location: fs/buffer.c:1400
Inline: True
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c05b1b2c-c05b1b88: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dbec0)
Location: fs/buffer.c:1400
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c0000000004dbec0-c0000000004dbf10: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffe000291d2a)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffe000291306-ffffffe00029131a: set_bh_page.part.0 (STB_LOCAL)
ffffffe00029131a-ffffffe000291376: set_bh_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81318b78)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81318410-ffffffff8131841b: set_bh_page.part.0 (STB_LOCAL)
ffffffff81318420-ffffffff81318459: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81309768)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81309000-ffffffff8130900b: set_bh_page.part.0 (STB_LOCAL)
ffffffff81309010-ffffffff81309049: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81316648)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81315ee0-ffffffff81315eeb: set_bh_page.part.0 (STB_LOCAL)
ffffffff81315ef0-ffffffff81315f29: set_bh_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_bh_page(struct buffer_head *bh, struct page *page, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81328438)
Location: fs/buffer.c:1400
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81327bf0-ffffffff81327bfb: set_bh_page.part.0 (STB_LOCAL)
ffffffff81327c00-ffffffff81327c39: set_bh_page (STB_GLOBAL)
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
