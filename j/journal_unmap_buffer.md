# Function: <code>journal_unmap_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e91e9)
Location: fs/jbd2/transaction.c:2096
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81316dcb)
Location: fs/jbd2/transaction.c:2081
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132cdbb)
Location: fs/jbd2/transaction.c:2086
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81341ff7)
Location: fs/jbd2/transaction.c:2104
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81366627)
Location: fs/jbd2/transaction.c:2107
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81394cd7)
Location: fs/jbd2/transaction.c:2110
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ada47)
Location: fs/jbd2/transaction.c:2150
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d7d8c)
Location: fs/jbd2/transaction.c:2184
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f1e5c)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143f1a0)
Location: fs/jbd2/transaction.c:2254
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
ffffffff8143f1a0-ffffffff8143f388: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145b400)
Location: fs/jbd2/transaction.c:2252
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
ffffffff8145b400-ffffffff8145b5e8: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81460d40)
Location: fs/jbd2/transaction.c:2257
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
ffffffff81460d40-ffffffff81460f28: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b6220)
Location: fs/jbd2/transaction.c:2257
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
ffffffff814b6220-ffffffff814b640e: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153fb10)
Location: fs/jbd2/transaction.c:2276
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
**Symbols:**

```
ffffffff8153fb10-ffffffff8153fd11: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815de680)
Location: fs/jbd2/transaction.c:2284
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
**Symbols:**

```
ffffffff815de680-ffffffff815de881: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816160e0)
Location: fs/jbd2/transaction.c:2260
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
**Symbols:**

```
ffffffff816160e0-ffffffff816162ef: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164ef00)
Location: fs/jbd2/transaction.c:2270
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
**Symbols:**

```
ffffffff8164ef00-ffffffff8164f109: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104cc324)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068fb74)
Location: fs/jbd2/transaction.c:2191
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
c068fb74-c068fe90: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int journal_unmap_buffer(journal_t *journal, struct buffer_head *bh, int partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0000000006057a0)
Location: fs/jbd2/transaction.c:2191
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
**Symbols:**

```
c0000000006057a0-c000000000605ba0: journal_unmap_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000344e4c)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ea43c)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813daebc)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e77bc)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fcf6f)
Location: fs/jbd2/transaction.c:2191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
