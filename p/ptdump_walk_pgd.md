# Function: <code>ptdump_walk_pgd</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8130cd60)
Location: mm/ptdump.c:140
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8130cd60-ffffffff8130cde3: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81318ca0)
Location: mm/ptdump.c:143
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81318ca0-ffffffff81318d58: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8131ee90)
Location: mm/ptdump.c:143
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8131ee90-ffffffff8131ef45: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8136c270)
Location: mm/ptdump.c:143
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8136c270-ffffffff8136c319: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff813ea550)
Location: mm/ptdump.c:151
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff813ea550-ffffffff813ea613: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81472680)
Location: mm/ptdump.c:151
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81472680-ffffffff8147274c: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814a6dd0)
Location: mm/ptdump.c:151
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff814a6dd0-ffffffff814a6eb6: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct ptdump_state *st, struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814d7dd0)
Location: mm/ptdump.c:151
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff814d7dd0-ffffffff814d7eb6: ptdump_walk_pgd (STB_GLOBAL)
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
void ptdump_walk_pgd(struct seq_file *m, struct ptdump_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dump.c (ffff8000100b1f28)
Location: arch/arm64/mm/dump.c:364
Inline: False
```
**Symbols:**

```
ffff8000100b1f28-ffff8000100b1fb0: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ptdump_walk_pgd(struct seq_file *m, struct ptdump_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dump.c (c0320498)
Location: arch/arm/mm/dump.c:391
Inline: False
```
**Symbols:**

```
c0320498-c0320558: ptdump_walk_pgd (STB_GLOBAL)
```
</details>
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
