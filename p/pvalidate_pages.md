# Function: <code>pvalidate_pages</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pvalidate_pages(long unsigned int vaddr, unsigned int npages, bool validate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a4210)
Location: arch/x86/kernel/sev.c:646
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:early_snp_set_memory_shared
  - arch/x86/kernel/sev.c:early_snp_set_memory_private
```
**Symbols:**

```
ffffffff810a4210-ffffffff810a4285: pvalidate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pvalidate_pages(long unsigned int vaddr, unsigned int npages, bool validate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bc6f0)
Location: arch/x86/kernel/sev.c:646
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:snp_set_memory_private
  - arch/x86/kernel/sev.c:snp_set_memory_shared
  - arch/x86/kernel/sev.c:snp_prep_memory
  - arch/x86/kernel/sev.c:snp_prep_memory
```
**Symbols:**

```
ffffffff810bc6f0-ffffffff810bc765: pvalidate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pvalidate_pages(struct snp_psc_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bed00)
Location: arch/x86/kernel/sev-shared.c:998
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:__set_pages_state
```
**Symbols:**

```
ffffffff810bed00-ffffffff810bee5f: pvalidate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pvalidate_pages(struct snp_psc_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c5fc0)
Location: arch/x86/kernel/sev-shared.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:__set_pages_state
```
**Symbols:**

```
ffffffff810c5fc0-ffffffff810c611f: pvalidate_pages (STB_LOCAL)
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
<code>struct snp_psc_desc *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int vaddr</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int npages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool validate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
