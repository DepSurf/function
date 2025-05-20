# Function: <code>early_set_pages_state</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_set_pages_state(long unsigned int paddr, unsigned int npages, enum psc_op op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83470d58)
Location: arch/x86/kernel/sev.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:early_snp_set_memory_shared
  - arch/x86/kernel/sev.c:early_snp_set_memory_private
```
**Symbols:**

```
ffffffff83470d58-ffffffff83470e4b: early_set_pages_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_set_pages_state(long unsigned int paddr, unsigned int npages, enum psc_op op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98120)
Location: arch/x86/kernel/sev.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
  - arch/x86/kernel/sev.c:snp_prep_memory
```
**Symbols:**

```
ffffffff83e98120-ffffffff83e98218: early_set_pages_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_set_pages_state(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages, enum psc_op op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c0090)
Location: arch/x86/kernel/sev.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
  - arch/x86/kernel/sev.c:snp_prep_memory
```
**Symbols:**

```
ffffffff810c0090-ffffffff810c0253: early_set_pages_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_set_pages_state(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages, enum psc_op op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c7480)
Location: arch/x86/kernel/sev.c:685
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
  - arch/x86/kernel/sev.c:snp_prep_memory
```
**Symbols:**

```
ffffffff810c7480-ffffffff810c7643: early_set_pages_state (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int vaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>paddr, npages, op</code> ➡️ <code>vaddr, paddr, npages, op</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
