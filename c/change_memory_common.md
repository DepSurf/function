# Function: <code>change_memory_common</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int change_memory_common(long unsigned int addr, int numpages, pgprot_t set_mask, pgprot_t clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0250)
Location: arch/arm64/mm/pageattr.c:53
Inline: False
Direct callers:
  - arch/arm64/mm/pageattr.c:set_memory_x
  - arch/arm64/mm/pageattr.c:set_memory_nx
  - arch/arm64/mm/pageattr.c:set_memory_rw
  - arch/arm64/mm/pageattr.c:set_memory_ro
```
**Symbols:**

```
ffff8000100b0250-ffff8000100b0378: change_memory_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int change_memory_common(long unsigned int addr, int numpages, pgprot_t set_mask, pgprot_t clear_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pageattr.c (c031fc3c)
Location: arch/arm/mm/pageattr.c:36
Inline: False
Direct callers:
  - arch/arm/mm/pageattr.c:set_memory_x
  - arch/arm/mm/pageattr.c:set_memory_nx
  - arch/arm/mm/pageattr.c:set_memory_rw
  - arch/arm/mm/pageattr.c:set_memory_ro
```
**Symbols:**

```
c031fc3c-c031fd94: change_memory_common (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
