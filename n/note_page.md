# Function: <code>note_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81073770)
Location: arch/x86/mm/dump_pagetables.c:192
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81073770-ffffffff81073f4f: note_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810772e0)
Location: arch/x86/mm/dump_pagetables.c:193
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff810772e0-ffffffff81077abf: note_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81075b40)
Location: arch/x86/mm/dump_pagetables.c:203
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81075b40-ffffffff8107636b: note_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8107bd90)
Location: arch/x86/mm/dump_pagetables.c:233
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8107bd90-ffffffff8107c5bd: note_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:239
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff8107eb90-ffffffff8107f27e: note_page (STB_LOCAL)
ffffffff8107f805-ffffffff8107fab5: note_page.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:271
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81085710-ffffffff81085df9: note_page (STB_LOCAL)
ffffffff8108636b-ffffffff810865f4: note_page.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
**Symbols:**

```
ffffffff81089310-ffffffff810899bc: note_page (STB_LOCAL)
ffffffff81089f1b-ffffffff8108a1fc: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
**Symbols:**

```
ffffffff81089f80-ffffffff8108a62c: note_page (STB_LOCAL)
ffffffff8108ab8b-ffffffff8108ae78: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff81091c30-ffffffff81091f74: note_page (STB_LOCAL)
ffffffff81092180-ffffffff81092243: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff81091560-ffffffff810918a0: note_page (STB_LOCAL)
ffffffff81bd9e0d-ffffffff81bd9ec8: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff81092040-ffffffff81092386: note_page (STB_LOCAL)
ffffffff81bcbe78-ffffffff81bcbf33: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff810a1c60-ffffffff810a2047: note_page (STB_LOCAL)
ffffffff81ca1aff-ffffffff81ca1d55: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff810b6160-ffffffff810b657d: note_page (STB_LOCAL)
ffffffff81e51152-ffffffff81e513a5: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff810d12a0-ffffffff810d17d0: note_page (STB_LOCAL)
ffffffff82054fe5-ffffffff82055149: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff810d4750-ffffffff810d4c80: note_page (STB_LOCAL)
ffffffff820d35b4-ffffffff820d3718: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void note_page(struct ptdump_state *pt_st, long unsigned int addr, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:274
Inline: False
```
**Symbols:**

```
ffffffff810dcef0-ffffffff810dd420: note_page (STB_LOCAL)
ffffffff821ae422-ffffffff821ae586: note_page.cold (STB_LOCAL)
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
void note_page(struct pg_state *st, long unsigned int addr, unsigned int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dump.c (ffff8000100b1970)
Location: arch/arm64/mm/dump.c:243
Inline: False
Direct callers:
  - arch/arm64/mm/dump.c:ptdump_check_wx
  - arch/arm64/mm/dump.c:ptdump_walk_pgd
  - arch/arm64/mm/dump.c:walk_pgd
```
**Symbols:**

```
ffff8000100b1970-ffff8000100b1cc4: note_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void note_page(struct pg_state *st, long unsigned int addr, unsigned int level, u64 val, const char *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dump.c (c031febc)
Location: arch/arm/mm/dump.c:254
Inline: False
Direct callers:
  - arch/arm/mm/dump.c:ptdump_check_wx
  - arch/arm/mm/dump.c:ptdump_walk_pgd
  - arch/arm/mm/dump.c:walk_pmd
  - arch/arm/mm/dump.c:walk_pmd
  - arch/arm/mm/dump.c:walk_pmd
```
**Symbols:**

```
c031febc-c03202e8: note_page (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
**Symbols:**

```
ffffffff81088f40-ffffffff810895ec: note_page (STB_LOCAL)
ffffffff81089b4b-ffffffff81089e38: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
**Symbols:**

```
ffffffff81077ba0-ffffffff8107824c: note_page (STB_LOCAL)
ffffffff8107872b-ffffffff81078a18: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
**Symbols:**

```
ffffffff81088ef0-ffffffff8108959c: note_page (STB_LOCAL)
ffffffff81089afb-ffffffff81089de8: note_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void note_page(struct seq_file *m, struct pg_state *st, pgprot_t new_prot, pgprotval_t new_eff, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:268
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
**Symbols:**

```
ffffffff8108b190-ffffffff8108b83c: note_page (STB_LOCAL)
ffffffff8108bd9b-ffffffff8108c088: note_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprotval_t new_eff</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, st, new_prot, level</code> ➡️ <code>m, st, new_prot, new_eff, level</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ptdump_state *pt_st</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 val</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pg_state *st</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprot_t new_prot</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprotval_t new_eff</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, st, new_prot, new_eff, level</code> ➡️ <code>pt_st, addr, level, val</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 val</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprot_t new_prot</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprotval_t new_eff</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, st, new_prot, new_eff, level</code> ➡️ <code>st, addr, level, val</code>
</li>
<li>
<b>Param type changed. </b>
<code>int level</code> ➡️ <code>unsigned int level</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 val</code>
</li>
<li>
<b>Param added. </b>
<code>const char *domain</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprot_t new_prot</code>
</li>
<li>
<b>Param removed. </b>
<code>pgprotval_t new_eff</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, st, new_prot, new_eff, level</code> ➡️ <code>st, addr, level, val, domain</code>
</li>
<li>
<b>Param type changed. </b>
<code>int level</code> ➡️ <code>unsigned int level</code>
</li>
</ul>
</details>
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
