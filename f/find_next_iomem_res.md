# Function: <code>find_next_iomem_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, char *name, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086610)
Location: kernel/resource.c:342
Inline: False
Direct callers:
  - kernel/resource.c:walk_iomem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_system_ram_range
```
**Symbols:**

```
ffffffff81086610-ffffffff81086735: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, long unsigned int desc, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089660)
Location: kernel/resource.c:361
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81089660-ffffffff81089776: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, long unsigned int desc, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e5b0)
Location: kernel/resource.c:361
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff8108e5b0-ffffffff8108e6c6: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, long unsigned int desc, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b5c0)
Location: kernel/resource.c:361
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff8108b5c0-ffffffff8108b6b7: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, long unsigned int desc, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810922a0)
Location: kernel/resource.c:361
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810922a0-ffffffff810923ad: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource *res, long unsigned int desc, bool first_level_children_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095bf0)
Location: kernel/resource.c:328
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81095bf0-ffffffff81095d09: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109df00)
Location: kernel/resource.c:340
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff8109df00-ffffffff8109e007: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2440)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a2440-ffffffff810a256a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8a10)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a8a10-ffffffff810a8b3a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0a20)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810b0a20-ffffffff810b0b57: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac150)
Location: kernel/resource.c:343
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810ac150-ffffffff810ac2b3: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad030)
Location: kernel/resource.c:338
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810ad030-ffffffff810ad126: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810beba0)
Location: kernel/resource.c:338
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810beba0-ffffffff810bec96: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5960)
Location: kernel/resource.c:325
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810d5960-ffffffff810d5ab4: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4960)
Location: kernel/resource.c:325
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810f4960-ffffffff810f4ab4: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81100d90)
Location: kernel/resource.c:325
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81100d90-ffffffff81100ee4: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81109f40)
Location: kernel/resource.c:325
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - kernel/resource.c:walk_mem_res
  - kernel/resource.c:walk_system_ram_res_rev
  - kernel/resource.c:walk_system_ram_res
  - kernel/resource.c:walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81109f40-ffffffff8110a094: find_next_iomem_res (STB_LOCAL)
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101006c0)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffff8000101006c0-ffff800010100860: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d4a8)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
c035d4a8-c035d608: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147710)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
c000000000147710-c000000000147958: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7b90)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffe0000c7b90-ffffffe0000c7cac: find_next_iomem_res (STB_LOCAL)
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2330)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a2330-ffffffff810a245a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090d10)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff81090d10-ffffffff81090e3a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a22e0)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810a22e0-ffffffff810a240a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa340)
Location: kernel/resource.c:341
Inline: False
Direct callers:
  - kernel/resource.c:walk_system_ram_range
  - kernel/resource.c:__walk_iomem_res_desc
```
**Symbols:**

```
ffffffff810aa340-ffffffff810aa47a: find_next_iomem_res (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int desc</code>
</li>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
</ul>
</details>
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
<code>bool first_level_children_only</code>
</li>
<li>
<b>Param reordered. </b>
<code>res, desc, first_level_children_only</code> ➡️ <code>start, end, flags, desc, first_lvl, res</code>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool first_lvl</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, flags, desc, first_lvl, res</code> ➡️ <code>start, end, flags, desc, res</code>
</li>
</ul>
</details>
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
