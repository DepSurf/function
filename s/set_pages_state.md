# Function: <code>set_pages_state</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_pages_state(long unsigned int vaddr, unsigned int npages, int op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81e4ee58)
Location: arch/x86/kernel/sev.c:880
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
```
**Symbols:**

```
ffffffff810a4290-ffffffff810a4419: set_pages_state (STB_LOCAL)
ffffffff81e4ee58-ffffffff81e4ee64: set_pages_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_pages_state(long unsigned int vaddr, unsigned int npages, int op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bc780)
Location: arch/x86/kernel/sev.c:880
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
```
**Symbols:**

```
ffffffff810bc780-ffffffff810bc915: set_pages_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_pages_state(long unsigned int vaddr, long unsigned int npages, int op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c0270)
Location: arch/x86/kernel/sev.c:837
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_accept_memory
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
```
**Symbols:**

```
ffffffff810c0270-ffffffff810c02b9: set_pages_state.part.0 (STB_LOCAL)
ffffffff810c02d0-ffffffff810c037b: set_pages_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_pages_state(long unsigned int vaddr, long unsigned int npages, int op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c7660)
Location: arch/x86/kernel/sev.c:864
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_accept_memory
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
```
**Symbols:**

```
ffffffff810c7660-ffffffff810c76a9: set_pages_state.part.0 (STB_LOCAL)
ffffffff810c76c0-ffffffff810c776b: set_pages_state (STB_LOCAL)
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
