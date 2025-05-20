# Function: <code>ptdump_walk_pgd_level_core</code>

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
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81073f50)
Location: arch/x86/mm/dump_pagetables.c:375
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81073f50-ffffffff8107435e: ptdump_walk_pgd_level_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81077ac0)
Location: arch/x86/mm/dump_pagetables.c:376
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81077ac0-ffffffff81077ed6: ptdump_walk_pgd_level_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81076370)
Location: arch/x86/mm/dump_pagetables.c:430
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81076370-ffffffff810767fb: ptdump_walk_pgd_level_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c5c0)
Location: arch/x86/mm/dump_pagetables.c:478
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff8107c5c0-ffffffff8107ca98: ptdump_walk_pgd_level_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:496
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff8107f280-ffffffff8107f788: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff8107fab5-ffffffff8107fae0: ptdump_walk_pgd_level_core.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:523
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81085e00-ffffffff810862d2: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff810865f4-ffffffff8108661f: ptdump_walk_pgd_level_core.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81089d20-ffffffff81089e7f: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff8108a1fc-ffffffff8108a227: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff8108a990-ffffffff8108aaef: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff8108ae78-ffffffff8108aea3: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81091790-ffffffff8109187e: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81091ff8-ffffffff81092023: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810910c0-ffffffff810911ae: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81bd9c85-ffffffff81bd9cb0: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81091ba0-ffffffff81091c8c: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81bcbcec-ffffffff81bcbd1b: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810a1760-ffffffff810a1889: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81ca1900-ffffffff81ca1989: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810b5870-ffffffff810b59bf: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81e50f1e-ffffffff81e50fa7: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810d0870-ffffffff810d09e2: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff82054f8b-ffffffff82054fe5: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810d3ea0-ffffffff810d4012: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff820d355a-ffffffff820d35b4: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, struct mm_struct *mm, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:365
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff810dc640-ffffffff810dc7b2: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff821ae3c8-ffffffff821ae422: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81089950-ffffffff81089aaf: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81089e38-ffffffff81089e63: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81078250-ffffffff81078683: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81078a18-ffffffff81078a43: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff81089900-ffffffff81089a5f: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff81089de8-ffffffff81089e13: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file *m, pgd_t *pgd, bool checkwx, bool dmesg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:518
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level
```
**Symbols:**

```
ffffffff8108bba0-ffffffff8108bcfb: ptdump_walk_pgd_level_core (STB_LOCAL)
ffffffff8108c088-ffffffff8108c0b3: ptdump_walk_pgd_level_core.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dmesg</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, pgd, checkwx, dmesg</code> ➡️ <code>m, mm, pgd, checkwx, dmesg</code>
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
