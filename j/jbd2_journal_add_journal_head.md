# Function: <code>jbd2_journal_add_journal_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2f60)
Location: fs/jbd2/journal.c:2444
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
**Symbols:**

```
ffffffff812f2f60-ffffffff812f3062: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81320930)
Location: fs/jbd2/journal.c:2461
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81320930-ffffffff81320a32: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813367e0)
Location: fs/jbd2/journal.c:2431
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813367e0-ffffffff813368e2: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134b490)
Location: fs/jbd2/journal.c:2454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8134b490-ffffffff8134b59d: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136fac0)
Location: fs/jbd2/journal.c:2470
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8136fac0-ffffffff8136fbcd: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2480
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8139e55b-ffffffff8139e573: jbd2_journal_add_journal_head.cold.56 (STB_LOCAL)
ffffffff8139dfd0-ffffffff8139e0d8: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2480
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813b72cb-ffffffff813b72e3: jbd2_journal_add_journal_head.cold.57 (STB_LOCAL)
ffffffff813b6d40-ffffffff813b6e48: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2468
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e1a3f-ffffffff813e1a57: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff813e1440-ffffffff813e154a: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813fba7c-ffffffff813fba94: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff813fb490-ffffffff813fb59a: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2494
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81449218-ffffffff81449230: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff81448c50-ffffffff81448d66: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2741
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81bed354-ffffffff81bed36c: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff814657f0-ffffffff81465906: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2741
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81bdf438-ffffffff81bdf450: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff8146afa0-ffffffff8146b0b6: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2920
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81ccedf5-ffffffff81ccee0d: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff814c18c0-ffffffff814c19d6: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2923
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81e81e42-ffffffff81e81e5a: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff8154c2a0-ffffffff8154c40c: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ec0c0)
Location: fs/jbd2/journal.c:2926
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff815ec0c0-ffffffff815ec23d: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81623ba0)
Location: fs/jbd2/journal.c:2926
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81623ba0-ffffffff81623d1d: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165cc40)
Location: fs/jbd2/journal.c:2913
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8165cc40-ffffffff8165cdbd: jbd2_journal_add_journal_head (STB_GLOBAL)
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
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d8ad0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffff8000104d8ad0-ffff8000104d8cc4: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c069a968)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c069a968-c069ab98: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000613a20)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c000000000613a20-c000000000613c7c: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034e532)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffe00034e532-ffffffe00034e69a: jbd2_journal_add_journal_head (STB_GLOBAL)
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
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813f405c-ffffffff813f4074: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff813f3a70-ffffffff813f3b7a: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e4adc-ffffffff813e4af4: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff813e44f0-ffffffff813e45fa: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813f13dc-ffffffff813f13f4: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff813f0df0-ffffffff813f0efa: jbd2_journal_add_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct journal_head *jbd2_journal_add_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2463
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81406fe7-ffffffff81406fff: jbd2_journal_add_journal_head.cold (STB_LOCAL)
ffffffff81406930-ffffffff81406a87: jbd2_journal_add_journal_head (STB_GLOBAL)
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
