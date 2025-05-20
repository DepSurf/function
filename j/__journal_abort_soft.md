# Function: <code>__journal_abort_soft</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1890)
Location: fs/jbd2/journal.c:2065
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff812f1890-ffffffff812f18e3: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f0a0)
Location: fs/jbd2/journal.c:2100
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff8131f0a0-ffffffff8131f0f3: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335120)
Location: fs/jbd2/journal.c:2070
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff81335120-ffffffff81335173: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81349ec0)
Location: fs/jbd2/journal.c:2093
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff81349ec0-ffffffff81349f13: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e510)
Location: fs/jbd2/journal.c:2109
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff8136e510-ffffffff8136e563: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2112
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff8139cb30-ffffffff8139cbc6: __journal_abort_soft (STB_LOCAL)
ffffffff8139e3e3-ffffffff8139e3f0: __journal_abort_soft.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2112
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813b58a0-ffffffff813b5936: __journal_abort_soft (STB_LOCAL)
ffffffff813b7153-ffffffff813b7160: __journal_abort_soft.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2103
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813dff80-ffffffff813e0021: __journal_abort_soft (STB_LOCAL)
ffffffff813e18cb-ffffffff813e18d8: __journal_abort_soft.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813f9fd0-ffffffff813fa062: __journal_abort_soft (STB_LOCAL)
ffffffff813fb91b-ffffffff813fb928: __journal_abort_soft.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d6d68)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffff8000104d6d68-ffff8000104d6ec0: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0698f38)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
c0698f38-c0699014: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0000000006118e0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
c0000000006118e0-c0000000006119f8: __journal_abort_soft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034cdce)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffe00034cdce-ffffffe00034ce80: __journal_abort_soft (STB_LOCAL)
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
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813f25b0-ffffffff813f2642: __journal_abort_soft (STB_LOCAL)
ffffffff813f3efb-ffffffff813f3f08: __journal_abort_soft.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813e3030-ffffffff813e30c2: __journal_abort_soft (STB_LOCAL)
ffffffff813e497b-ffffffff813e4988: __journal_abort_soft.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff813ef930-ffffffff813ef9c2: __journal_abort_soft (STB_LOCAL)
ffffffff813f127b-ffffffff813f1288: __journal_abort_soft.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __journal_abort_soft(journal_t *journal, int errno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:2106
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
**Symbols:**

```
ffffffff81405310-ffffffff814053d3: __journal_abort_soft (STB_LOCAL)
ffffffff81406e86-ffffffff81406e93: __journal_abort_soft.cold (STB_LOCAL)
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
