# Function: <code>ptdump_pgd_entry</code>

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
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8130cb20)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff8130cb20-ffffffff8130cb54: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81318a60)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff81318a60-ffffffff81318a94: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8131ec50)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff8131ec50-ffffffff8131ec84: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8136c030)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff8136c030-ffffffff8136c064: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff813ea260)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff813ea260-ffffffff813ea2b1: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81472320)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff81472320-ffffffff81472378: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814a6a80)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff814a6a80-ffffffff814a6ad8: ptdump_pgd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptdump_pgd_entry(pgd_t *pgd, long unsigned int addr, long unsigned int next, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814d7a80)
Location: mm/ptdump.c:28
Inline: False
```
**Symbols:**

```
ffffffff814d7a80-ffffffff814d7ad8: ptdump_pgd_entry (STB_LOCAL)
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
