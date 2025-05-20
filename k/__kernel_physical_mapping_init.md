# Function: <code>__kernel_physical_mapping_init</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94a4d)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a94a4d-ffffffff81a94cf0: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc32d)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81acc32d-ffffffff81acc5d0: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc4e2e)
Location: arch/x86/mm/init_64.c:730
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81bc4e2e-ffffffff81bc504c: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3dd27)
Location: arch/x86/mm/init_64.c:725
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81c3dd27-ffffffff81c3df1d: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3006a)
Location: arch/x86/mm/init_64.c:725
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81c3006a-ffffffff81c30266: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4e7b9)
Location: arch/x86/mm/init_64.c:726
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81d4e7b9-ffffffff81d4e9f1: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1e5ac)
Location: arch/x86/mm/init_64.c:725
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81f1e5ac-ffffffff81f1e800: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c6ed0)
Location: arch/x86/mm/init_64.c:726
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff820c6ed0-ffffffff820c72ab: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214af40)
Location: arch/x86/mm/init_64.c:726
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8214af40-ffffffff8214b336: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222d9f0)
Location: arch/x86/mm/init_64.c:726
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8222d9f0-ffffffff8222dde6: __kernel_physical_mapping_init (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6b19d)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a6b19d-ffffffff81a6b440: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a27760)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81a27760-ffffffff81a2798d: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad75ad)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81ad75ad-ffffffff81ad7850: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3a6d)
Location: arch/x86/mm/init_64.c:722
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_change
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81ae3a6d-ffffffff81ae3d10: __kernel_physical_mapping_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param reordered. </b>
<code>paddr_start, paddr_end, page_size_mask, init</code> ➡️ <code>paddr_start, paddr_end, page_size_mask, prot, init</code>
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
