# Function: <code>migrate_page_move_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f1620)
Location: mm/migrate.c:312
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff811f1620-ffffffff811f1983: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81210bd0)
Location: mm/migrate.c:405
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81210bd0-ffffffff81211014: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81222d20)
Location: mm/migrate.c:405
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81222d20-ffffffff812231d3: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122e730)
Location: mm/migrate.c:391
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8122e730-ffffffff8122ec24: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124a850)
Location: mm/migrate.c:435
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8124a850-ffffffff8124ad70: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, struct buffer_head *head, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126e660)
Location: mm/migrate.c:436
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8126e660-ffffffff8126ec3b: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81282320)
Location: mm/migrate.c:399
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81282320-ffffffff812828ac: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129e300)
Location: mm/migrate.c:396
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8129e300-ffffffff8129e892: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812adbb0)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812adbb0-ffffffff812ae132: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e46f0)
Location: mm/migrate.c:402
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812e46f0-ffffffff812e4cc8: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ef0e0)
Location: mm/migrate.c:398
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812ef0e0-ffffffff812ef6a9: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f5d50)
Location: mm/migrate.c:372
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812f5d50-ffffffff812f639e: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81340310)
Location: mm/migrate.c:380
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81340310-ffffffff813409d5: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81301220)
Location: mm/folio-compat.c:55
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81301220-ffffffff813012be: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034fab8)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffff80001034fab8-ffff8000103500c8: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0550e30)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
c0550e30-c05512bc: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000432fd0)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
c000000000432fd0-c000000000433804: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023e976)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffe00023e976-ffffffe00023edd8: migrate_page_move_mapping (STB_GLOBAL)
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
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6190)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812a6190-ffffffff812a6712: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81297c40)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81297c40-ffffffff812981b6: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3fa0)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812a3fa0-ffffffff812a4522: migrate_page_move_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_page_move_mapping(struct address_space *mapping, struct page *newpage, struct page *page, int extra_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b3710)
Location: mm/migrate.c:397
Inline: False
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812b3710-ffffffff812b3c87: migrate_page_move_mapping (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct buffer_head *head</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, newpage, page, head, mode, extra_count</code> ➡️ <code>mapping, newpage, page, mode, extra_count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum migrate_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, newpage, page, mode, extra_count</code> ➡️ <code>mapping, newpage, page, extra_count</code>
</li>
</ul>
</details>
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
