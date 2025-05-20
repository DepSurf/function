# Function: <code>get_user_bd_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int get_user_bd_entry(struct mm_struct *mm, long unsigned int *bd_entry_ret, long int *bd_entry_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075ec0)
Location: arch/x86/mm/mpx.c:593
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff81075ec0-ffffffff81075eed: get_user_bd_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int get_user_bd_entry(struct mm_struct *mm, long unsigned int *bd_entry_ret, long int *bd_entry_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81077625)
Location: arch/x86/mm/mpx.c:593
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff81077400-ffffffff8107742d: get_user_bd_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int get_user_bd_entry(struct mm_struct *mm, long unsigned int *bd_entry_ret, long int *bd_entry_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b1d5)
Location: arch/x86/mm/mpx.c:592
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff8107afb0-ffffffff8107afdd: get_user_bd_entry (STB_GLOBAL)
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
In arch/x86/mm/mpx.c (ffffffff810799c2)
Location: arch/x86/mm/mpx.c:585
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff8107fbe5)
Location: arch/x86/mm/mpx.c:479
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff81082d00)
Location: arch/x86/mm/mpx.c:479
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff810898b0)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
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
In arch/x86/mm/mpx.c (ffffffff8108cdc3)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108da23)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c9e3)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8107b513)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108c993)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
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
In arch/x86/mm/mpx.c (ffffffff8108ed03)
Location: arch/x86/mm/mpx.c:467
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
