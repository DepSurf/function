# Function: <code>create_memory_block_devices</code>

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
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8fb0)
Location: drivers/base/memory.c:720
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816f8fb0-ffffffff816f90f8: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171d330)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8171d330-ffffffff8171d478: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d9220)
Location: drivers/base/memory.c:637
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817d9220-ffffffff817d9345: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817edc00)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817edc00-ffffffff817edcec: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, long unsigned int vmemmap_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d2540)
Location: drivers/base/memory.c:696
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817d2540-ffffffff817d2633: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, long unsigned int vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d680)
Location: drivers/base/memory.c:716
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8185d680-ffffffff8185d789: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, long unsigned int vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4ae0)
Location: drivers/base/memory.c:813
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff819a4ae0-ffffffff819a4bf0: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, long unsigned int vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16bc0)
Location: drivers/base/memory.c:825
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81b16bc0-ffffffff81b16cd0: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, long unsigned int vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b65930)
Location: drivers/base/memory.c:820
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81b65930-ffffffff81b65a40: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size, struct vmem_altmap *altmap, struct memory_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb97b0)
Location: drivers/base/memory.c:870
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
```
**Symbols:**

```
ffffffff81bb97b0-ffffffff81bb98c0: create_memory_block_devices (STB_GLOBAL)
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
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910f98)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffff800010910f98-ffff8000109110fc: create_memory_block_devices (STB_GLOBAL)
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
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b22f0)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
c0000000009b22f0-c0000000009b24bc: create_memory_block_devices (STB_GLOBAL)
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
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e3660)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816e3660-ffffffff816e37a8: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdca0)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff816bdca0-ffffffff816bdde8: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817107f0)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff817107f0-ffffffff81710938: create_memory_block_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int create_memory_block_devices(long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172b950)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8172b950-ffffffff8172ba98: create_memory_block_devices (STB_GLOBAL)
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
<b>Param added. </b>
<code>long unsigned int vmemmap_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct memory_group *group</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int vmemmap_pages</code>
</li>
</ul>
</details>
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
