# Function: <code>filemap_fdatawrite_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118ea10)
Location: mm/filemap.c:314
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff8118ea10-ffffffff8118ea25: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a25c0)
Location: mm/filemap.c:393
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811a25c0-ffffffff811a25d5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2400)
Location: mm/filemap.c:358
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811b2400-ffffffff811b2415: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9070)
Location: mm/filemap.c:362
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811b9070-ffffffff811b9085: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd980)
Location: mm/filemap.c:462
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811cd980-ffffffff811cd995: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef4b0)
Location: mm/filemap.c:462
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff811ef4b0-ffffffff811ef4c5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200cb0)
Location: mm/filemap.c:428
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81200cb0-ffffffff81200cc5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812188d0)
Location: mm/filemap.c:432
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff812188d0-ffffffff812188e5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226160)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81226160-ffffffff81226175: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251200)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81251200-ffffffff81251215: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c890)
Location: mm/filemap.c:439
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8125c890-ffffffff8125c8a5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261670)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81261670-ffffffff81261685: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299700)
Location: mm/filemap.c:448
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81299700-ffffffff8129976a: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5670)
Location: mm/filemap.c:436
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff812f5670-ffffffff812f5691: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f4f0)
Location: mm/filemap.c:436
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8135f4f0-ffffffff8135f511: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390650)
Location: mm/filemap.c:441
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81390650-ffffffff81390671: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba090)
Location: mm/filemap.c:436
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff813ba090-ffffffff813ba0b1: filemap_fdatawrite_range (STB_GLOBAL)
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
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b33e0)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffff8000102b33e0-ffff8000102b3428: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e05e4)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
c04e05e4-c04e0618: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369f60)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
c000000000369f60-c000000000369f78: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8b04)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffe0001d8b04-ffffffe0001d8b40: filemap_fdatawrite_range (STB_GLOBAL)
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
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e7b0)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8121e7b0-ffffffff8121e7c5: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211970)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff81211970-ffffffff81211985: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c550)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8121c550-ffffffff8121c565: filemap_fdatawrite_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filemap_fdatawrite_range(struct address_space *mapping, loff_t start, loff_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b5e0)
Location: mm/filemap.c:438
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/fat/file.c:fat_cont_expand
```
**Symbols:**

```
ffffffff8122b5e0-ffffffff8122b5f5: filemap_fdatawrite_range (STB_GLOBAL)
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
