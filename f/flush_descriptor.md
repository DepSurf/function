# Function: <code>flush_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff812ed660)
Location: fs/jbd2/revoke.c:655
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff812ed660-ffffffff812ed7a6: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8131b0c0)
Location: fs/jbd2/revoke.c:633
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8131b0c0-ffffffff8131b0fe: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813310a0)
Location: fs/jbd2/revoke.c:634
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813310a0-ffffffff813310de: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81346000)
Location: fs/jbd2/revoke.c:634
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81346000-ffffffff8134603e: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8136a690)
Location: fs/jbd2/revoke.c:634
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8136a690-ffffffff8136a6d0: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81398bf0)
Location: fs/jbd2/revoke.c:627
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81398bf0-ffffffff81398c41: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813b1960)
Location: fs/jbd2/revoke.c:627
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813b1960-ffffffff813b19b1: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void flush_descriptor(journal_t *journal, struct buffer_head *descriptor, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813dbf90)
Location: fs/jbd2/revoke.c:635
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813dbf90-ffffffff813dbff4: flush_descriptor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813f6732)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813f5ff0-ffffffff813f6047: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff814435ba)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81443470-ffffffff814434c9: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8145f69a)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8145f550-ffffffff8145f5a9: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8146550a)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81464dc0-ffffffff81464e19: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff814bae8a)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff814ba710-ffffffff814ba769: flush_descriptor.part.0 (STB_LOCAL)
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
In fs/jbd2/revoke.c (ffffffff81544d58)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff815444b0-ffffffff81544504: flush_descriptor.part.0 (STB_LOCAL)
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
In fs/jbd2/revoke.c (ffffffff815e3e98)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff815e34e0-ffffffff815e3534: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8161b65b)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8161aca0-ffffffff8161acf4: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8165457b)
Location: fs/jbd2/revoke.c:641
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81653bc0-ffffffff81653c14: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffff8000104d29e4)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffff8000104d2180-ffff8000104d2264: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (c0694f64)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
c0694864-c06948dc: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (c00000000060c1c0)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
c00000000060b3f0-c00000000060b4c8: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffe0003498ba)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffe000349038-ffffffe0003490da: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813eed12)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813ee5d0-ffffffff813ee627: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813df792)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813df050-ffffffff813df0a7: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813ec092)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813eb950-ffffffff813eb9a7: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81401a32)
Location: fs/jbd2/revoke.c:635
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81401440-ffffffff81401497: flush_descriptor.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int write_op</code>
</li>
</ul>
</details>
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
</ul>
