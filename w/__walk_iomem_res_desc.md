# Function: <code>__walk_iomem_res_desc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __walk_iomem_res_desc(struct resource *res, long unsigned int desc, bool first_level_children_only, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810923b0)
Location: kernel/resource.c:405
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810923b0-ffffffff81092438: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __walk_iomem_res_desc(struct resource *res, long unsigned int desc, bool first_level_children_only, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095d10)
Location: kernel/resource.c:372
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81095d10-ffffffff81095da0: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e010)
Location: kernel/resource.c:379
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff8109e010-ffffffff8109e0c3: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2570)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a2570-ffffffff810a2627: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8b40)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a8b40-ffffffff810a8bf7: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b108a)
Location: kernel/resource.c:395
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac7ea)
Location: kernel/resource.c:400
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff810ad9ea)
Location: kernel/resource.c:387
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff810bf56a)
Location: kernel/resource.c:387
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff810d695a)
Location: kernel/resource.c:374
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff810f636a)
Location: kernel/resource.c:374
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff811027ba)
Location: kernel/resource.c:374
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
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
In kernel/resource.c (ffffffff8110c0ea)
Location: kernel/resource.c:374
Inline: True
Inline callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100860)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffff800010100860-ffff80001010093c: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d608)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
c035d608-c035d6d8: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147960)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
c000000000147960-c000000000147a88: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7cac)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffe0000c7cac-ffffffe0000c7d30: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2460)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a2460-ffffffff810a2517: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090e40)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81090e40-ffffffff81090ef7: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2410)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a2410-ffffffff810a24c7: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa480)
Location: kernel/resource.c:395
Inline: False
Direct callers:
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810aa480-ffffffff810aa537: __walk_iomem_res_desc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t start</code>
</li>
<li>
<b>Param added. </b>
<code>resource_size_t end</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>bool first_lvl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource *res</code>
</li>
<li>
<b>Param removed. </b>
<code>bool first_level_children_only</code>
</li>
<li>
<b>Param reordered. </b>
<code>res, desc, first_level_children_only, arg, func</code> ➡️ <code>start, end, flags, desc, first_lvl, arg, func</code>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
