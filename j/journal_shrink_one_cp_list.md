# Function: <code>journal_shrink_one_cp_list</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff814ba390)
Location: fs/jbd2/checkpoint.c:461
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
Direct callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
**Symbols:**

```
ffffffff814ba1b0-ffffffff814ba255: journal_shrink_one_cp_list.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff815440e9)
Location: fs/jbd2/checkpoint.c:461
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
Direct callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
**Symbols:**

```
ffffffff81543f60-ffffffff81544011: journal_shrink_one_cp_list.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff815e30c9)
Location: fs/jbd2/checkpoint.c:461
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
Direct callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
**Symbols:**

```
ffffffff815e2f30-ffffffff815e2fe1: journal_shrink_one_cp_list.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int journal_shrink_one_cp_list(struct journal_head *jh, bool destroy, bool *released);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8161a810)
Location: fs/jbd2/checkpoint.c:362
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
**Symbols:**

```
ffffffff8161a810-ffffffff8161a8c9: journal_shrink_one_cp_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int journal_shrink_one_cp_list(struct journal_head *jh, enum shrink_type type, bool *released);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81653730)
Location: fs/jbd2/checkpoint.c:352
Inline: False
Direct callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
**Symbols:**

```
ffffffff81653730-ffffffff816537eb: journal_shrink_one_cp_list (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum shrink_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool destroy</code>
</li>
</ul>
</details>
</li>
</ul>
