# Function: <code>__jbd2_journal_unfile_buffer</code>

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
In fs/jbd2/transaction.c (ffffffff812e813e)
Location: fs/jbd2/transaction.c:1889
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
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
In fs/jbd2/transaction.c (ffffffff813171fa)
Location: fs/jbd2/transaction.c:1874
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff8132d1ea)
Location: fs/jbd2/transaction.c:1879
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813423b8)
Location: fs/jbd2/transaction.c:1897
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813669e8)
Location: fs/jbd2/transaction.c:1900
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813950d3)
Location: fs/jbd2/transaction.c:1903
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813ade43)
Location: fs/jbd2/transaction.c:1943
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813d81ae)
Location: fs/jbd2/transaction.c:1977
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813f2293)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __jbd2_journal_unfile_buffer(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143cd20)
Location: fs/jbd2/transaction.c:2027
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
**Symbols:**

```
ffffffff8143cd20-ffffffff8143cd52: __jbd2_journal_unfile_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __jbd2_journal_unfile_buffer(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814590a0)
Location: fs/jbd2/transaction.c:2030
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
**Symbols:**

```
ffffffff814590a0-ffffffff814590d2: __jbd2_journal_unfile_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __jbd2_journal_unfile_buffer(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145e6e0)
Location: fs/jbd2/transaction.c:2035
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
**Symbols:**

```
ffffffff8145e6e0-ffffffff8145e712: __jbd2_journal_unfile_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b6697)
Location: fs/jbd2/transaction.c:2052
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81540093)
Location: fs/jbd2/transaction.c:2071
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815deb93)
Location: fs/jbd2/transaction.c:2079
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816165f3)
Location: fs/jbd2/transaction.c:2078
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164f413)
Location: fs/jbd2/transaction.c:2088
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffff8000104cc9b0)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0690280)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0000000006060b0)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffe000345336)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813ea873)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813db2f3)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813e7bf3)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
In fs/jbd2/transaction.c (ffffffff813fd3f3)
Location: fs/jbd2/transaction.c:1984
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
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
</ul>
