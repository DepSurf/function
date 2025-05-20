# Function: <code>walk_pud_level</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8107405a)
Location: arch/x86/mm/dump_pagetables.c:329
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff81077bd2)
Location: arch/x86/mm/dump_pagetables.c:330
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff81076485)
Location: arch/x86/mm/dump_pagetables.c:349
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff8107c627)
Location: arch/x86/mm/dump_pagetables.c:398
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff8107f38d)
Location: arch/x86/mm/dump_pagetables.c:414
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff81085f57)
Location: arch/x86/mm/dump_pagetables.c:441
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void walk_pud_level(struct seq_file *m, struct pg_state *st, p4d_t addr, pgprotval_t eff_in, long unsigned int P);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810899c0)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff810899c0-ffffffff81089d19: walk_pud_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void walk_pud_level(struct seq_file *m, struct pg_state *st, p4d_t addr, pgprotval_t eff_in, long unsigned int P);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a630)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8108a630-ffffffff8108a989: walk_pud_level (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void walk_pud_level(struct seq_file *m, struct pg_state *st, p4d_t addr, pgprotval_t eff_in, long unsigned int P);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810895f0)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff810895f0-ffffffff81089949: walk_pud_level (STB_LOCAL)
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
In arch/x86/mm/dump_pagetables.c (ffffffff810783a1)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void walk_pud_level(struct seq_file *m, struct pg_state *st, p4d_t addr, pgprotval_t eff_in, long unsigned int P);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810895a0)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff810895a0-ffffffff810898f9: walk_pud_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void walk_pud_level(struct seq_file *m, struct pg_state *st, p4d_t addr, pgprotval_t eff_in, long unsigned int P);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b840)
Location: arch/x86/mm/dump_pagetables.c:438
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8108b840-ffffffff8108bb99: walk_pud_level (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
