# Function: <code>printk_prot</code>

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
In arch/x86/mm/dump_pagetables.c (ffffffff810738e3)
Location: arch/x86/mm/dump_pagetables.c:126
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff81077453)
Location: arch/x86/mm/dump_pagetables.c:127
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff81075cb9)
Location: arch/x86/mm/dump_pagetables.c:137
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff8107bf09)
Location: arch/x86/mm/dump_pagetables.c:166
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff8107ed20)
Location: arch/x86/mm/dump_pagetables.c:172
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108587a)
Location: arch/x86/mm/dump_pagetables.c:181
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff81089475)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108a0e5)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810918c0-ffffffff81091c2a: printk_prot (STB_LOCAL)
ffffffff81092023-ffffffff81092180: printk_prot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810911f0-ffffffff8109155a: printk_prot (STB_LOCAL)
ffffffff81bd9cb0-ffffffff81bd9e0d: printk_prot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff81091cd0-ffffffff8109203a: printk_prot (STB_LOCAL)
ffffffff81bcbd1b-ffffffff81bcbe78: printk_prot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810a18d0-ffffffff810a1c56: printk_prot (STB_LOCAL)
ffffffff81ca1989-ffffffff81ca1aff: printk_prot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810b5a10-ffffffff810b6157: printk_prot (STB_LOCAL)
ffffffff81e50fa7-ffffffff81e51152: printk_prot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d0a60)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810d0a60-ffffffff810d1290: printk_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d4090)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810d4090-ffffffff810d473e: printk_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void printk_prot(struct seq_file *m, pgprotval_t pr, int level, bool dmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810dc830)
Location: arch/x86/mm/dump_pagetables.c:179
Inline: False
Direct callers:
  - arch/x86/mm/dump_pagetables.c:note_page
```
**Symbols:**

```
ffffffff810dc830-ffffffff810dcede: printk_prot (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810890a5)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff81077d05)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff81089055)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108b2f5)
Location: arch/x86/mm/dump_pagetables.c:177
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:note_page
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
