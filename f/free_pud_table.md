# Function: <code>free_pud_table</code>

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
In arch/x86/mm/init_64.c (ffffffff8181c785)
Location: arch/x86/mm/init_64.c:770
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
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
void free_pud_table(pud_t *pud_start, p4d_t *p4d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3c63)
Location: arch/x86/mm/init_64.c:947
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81bc3c63-ffffffff81bc3cdc: free_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pud_table(pud_t *pud_start, p4d_t *p4d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3cb7f)
Location: arch/x86/mm/init_64.c:941
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
**Symbols:**

```
ffffffff81c3cb7f-ffffffff81c3cbf0: free_pud_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f62b)
Location: arch/x86/mm/init_64.c:1039
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
In arch/x86/mm/init_64.c (ffffffff81d4dd28)
Location: arch/x86/mm/init_64.c:1040
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1040
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
In arch/x86/mm/init_64.c (ffffffff820c5ec8)
Location: arch/x86/mm/init_64.c:1041
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
In arch/x86/mm/init_64.c (ffffffff82149f28)
Location: arch/x86/mm/init_64.c:1041
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
In arch/x86/mm/init_64.c (ffffffff8222c9d8)
Location: arch/x86/mm/init_64.c:1041
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
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
</ul>
