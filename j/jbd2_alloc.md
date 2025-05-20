# Function: <code>jbd2_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2a50)
Location: fs/jbd2/journal.c:2296
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff812f2a50-ffffffff812f2ac5: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81320450)
Location: fs/jbd2/journal.c:2331
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81320450-ffffffff813204a9: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81336300)
Location: fs/jbd2/journal.c:2301
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81336300-ffffffff81336359: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134b030)
Location: fs/jbd2/journal.c:2324
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8134b030-ffffffff8134b089: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136f680)
Location: fs/jbd2/journal.c:2340
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8136f680-ffffffff8136f6d9: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139dba0)
Location: fs/jbd2/journal.c:2352
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8139dba0-ffffffff8139dbff: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b6910)
Location: fs/jbd2/journal.c:2352
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813b6910-ffffffff813b696f: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e0fd0)
Location: fs/jbd2/journal.c:2343
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813e0fd0-ffffffff813e1032: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fb020)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813fb020-ffffffff813fb082: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814487e0)
Location: fs/jbd2/journal.c:2367
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff814487e0-ffffffff81448836: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81465390)
Location: fs/jbd2/journal.c:2614
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81465390-ffffffff814653f5: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146ab20)
Location: fs/jbd2/journal.c:2614
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8146ab20-ffffffff8146ab85: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c1330)
Location: fs/jbd2/journal.c:2793
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff814c1330-ffffffff814c1395: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154bc60)
Location: fs/jbd2/journal.c:2796
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8154bc60-ffffffff8154bccc: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eba10)
Location: fs/jbd2/journal.c:2799
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff815eba10-ffffffff815eba7c: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816234f0)
Location: fs/jbd2/journal.c:2799
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff816234f0-ffffffff8162355c: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165c550)
Location: fs/jbd2/journal.c:2786
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8165c550-ffffffff8165c5bc: jbd2_alloc (STB_GLOBAL)
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
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d8588)
Location: fs/jbd2/journal.c:2338
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffff8000104d8588-ffff8000104d8618: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c069a4b4)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c069a4b4-c069a524: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000613350)
Location: fs/jbd2/journal.c:2338
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c000000000613350-c0000000006133fc: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034e084)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffe00034e084-ffffffe00034e0fa: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3600)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813f3600-ffffffff813f3662: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e4080)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813e4080-ffffffff813e40e2: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f0980)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813f0980-ffffffff813f09e2: jbd2_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *jbd2_alloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814063f0)
Location: fs/jbd2/journal.c:2338
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff814063f0-ffffffff81406452: jbd2_alloc (STB_GLOBAL)
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
