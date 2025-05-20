# Function: <code>mpx_cmpxchg_bd_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075010)
Location: arch/x86/mm/mpx.c:378
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
**Symbols:**

```
ffffffff81075010-ffffffff8107508e: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff810768c0)
Location: arch/x86/mm/mpx.c:378
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff810768c0-ffffffff81076932: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107a4b0)
Location: arch/x86/mm/mpx.c:378
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8107a4b0-ffffffff8107a522: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81078d20)
Location: arch/x86/mm/mpx.c:379
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff81078d20-ffffffff81078d92: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107f070)
Location: arch/x86/mm/mpx.c:273
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8107f070-ffffffff8107f0f8: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81081bd0)
Location: arch/x86/mm/mpx.c:273
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff81081bd0-ffffffff81081c58: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff810887e0)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff810887e0-ffffffff81088868: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108ca30)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8108ca30-ffffffff8108cab6: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108d690)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8108d690-ffffffff8108d716: mpx_cmpxchg_bd_entry (STB_LOCAL)
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
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c650)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8108c650-ffffffff8108c6d6: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b180)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8107b180-ffffffff8107b206: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c600)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8108c600-ffffffff8108c686: mpx_cmpxchg_bd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpx_cmpxchg_bd_entry(struct mm_struct *mm, long unsigned int *curval, long unsigned int *addr, long unsigned int old_val, long unsigned int new_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108e960)
Location: arch/x86/mm/mpx.c:261
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
**Symbols:**

```
ffffffff8108e960-ffffffff8108e9e6: mpx_cmpxchg_bd_entry (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
