# Function: <code>effective_prot</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f68c)
Location: arch/x86/mm/dump_pagetables.c:328
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108627d)
Location: arch/x86/mm/dump_pagetables.c:354
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff81089a4b)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108a6bb)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81091730)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff81091730-ffffffff81091784: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81091060)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff81091060-ffffffff810910b4: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff81091b40)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff81091b40-ffffffff81091b91: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810a16c0)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff810a16c0-ffffffff810a1754: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810b57d0)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff810b57d0-ffffffff810b5870: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d07c0)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff810d07c0-ffffffff810d0860: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d3df0)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff810d3df0-ffffffff810d3e90: effective_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state *pt_st, int level, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810dc590)
Location: arch/x86/mm/dump_pagetables.c:251
Inline: False
```
**Symbols:**

```
ffffffff810dc590-ffffffff810dc630: effective_prot (STB_LOCAL)
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108967b)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
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
In arch/x86/mm/dump_pagetables.c (ffffffff810783fd)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108962b)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
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
In arch/x86/mm/dump_pagetables.c (ffffffff8108b8cb)
Location: arch/x86/mm/dump_pagetables.c:351
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
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
