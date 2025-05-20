# Function: <code>link_mem_sections</code>

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
In drivers/base/node.c (ffffffff81560cba)
Location: drivers/base/node.c:460
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815b53fa)
Location: drivers/base/node.c:471
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815e46d6)
Location: drivers/base/node.c:471
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815f91d0)
Location: drivers/base/node.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff815f91d0-ffffffff815f928d: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816612a0)
Location: drivers/base/node.c:481
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff816612a0-ffffffff81661376: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages, bool check_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8169ca70)
Location: drivers/base/node.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff8169ca70-ffffffff8169cb3a: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bd2c0)
Location: drivers/base/node.c:492
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816bd2c0-ffffffff816bd2e8: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f8070)
Location: drivers/base/node.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816f8070-ffffffff816f80a3: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8171c470)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8171c470-ffffffff8171c4a3: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d8590)
Location: drivers/base/node.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817d8590-ffffffff817d85d4: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817ecfd0)
Location: drivers/base/node.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817ecfd0-ffffffff817ed014: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d17a0)
Location: drivers/base/node.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817d17a0-ffffffff817d17e1: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8185c3b0)
Location: drivers/base/node.c:892
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8185c3b0-ffffffff8185c3f1: link_mem_sections (STB_GLOBAL)
```
</details>
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffff8000109100d8)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffff8000109100d8-ffff80001091011c: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (c0000000009b0ce0)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
c0000000009b0ce0-c0000000009b0d34: link_mem_sections (STB_GLOBAL)
```
</details>
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816e27a0)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816e27a0-ffffffff816e27d3: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bcde0)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816bcde0-ffffffff816bce13: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8170f9a0)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8170f9a0-ffffffff8170f9d3: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8172aa90)
Location: drivers/base/node.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8172aa90-ffffffff8172aac3: link_mem_sections (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_nid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int end_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool check_nid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum meminit_context context</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
