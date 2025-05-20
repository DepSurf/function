# Function: <code>__jbd2_journal_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __jbd2_journal_erase(journal_t *journal, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1753
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff814c06f0-ffffffff814c08fb: __jbd2_journal_erase (STB_LOCAL)
ffffffff81ccece1-ffffffff81cced1e: __jbd2_journal_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __jbd2_journal_erase(journal_t *journal, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1759
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff8154af50-ffffffff8154b142: __jbd2_journal_erase (STB_LOCAL)
ffffffff81e81d46-ffffffff81e81d73: __jbd2_journal_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __jbd2_journal_erase(journal_t *journal, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eaba0)
Location: fs/jbd2/journal.c:1765
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff815eaba0-ffffffff815eadc1: __jbd2_journal_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __jbd2_journal_erase(journal_t *journal, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81622610)
Location: fs/jbd2/journal.c:1779
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff81622610-ffffffff81622837: __jbd2_journal_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __jbd2_journal_erase(journal_t *journal, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165b670)
Location: fs/jbd2/journal.c:1950
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff8165b670-ffffffff8165b897: __jbd2_journal_erase (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
