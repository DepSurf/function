# Function: <code>find_memory_block_hinted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561920)
Location: drivers/base/memory.c:541
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:register_new_memory
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff81561920-ffffffff81561986: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b61f0)
Location: drivers/base/memory.c:574
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815b61f0-ffffffff815b6258: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e5510)
Location: drivers/base/memory.c:575
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815e5510-ffffffff815e5578: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815f9fa0)
Location: drivers/base/memory.c:583
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815f9fa0-ffffffff815fa00b: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81662140)
Location: drivers/base/memory.c:594
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff81662140-ffffffff816621ab: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d930)
Location: drivers/base/memory.c:596
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:hotplug_memory_register
```
**Symbols:**

```
ffffffff8169d930-ffffffff8169d99b: find_memory_block_hinted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct memory_block *find_memory_block_hinted(struct mem_section *section, struct memory_block *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816be0d0)
Location: drivers/base/memory.c:583
Inline: False
Direct callers:
  - mm/memory_hotplug.c:walk_memory_range
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:hotplug_memory_register
```
**Symbols:**

```
ffffffff816be0d0-ffffffff816be138: find_memory_block_hinted (STB_GLOBAL)
```
</details>
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
</ul>
