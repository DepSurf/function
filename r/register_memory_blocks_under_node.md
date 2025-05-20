# Function: <code>register_memory_blocks_under_node</code>

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
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff834baabb)
Location: drivers/base/node.c:893
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff819a3530-ffffffff819a357f: register_memory_blocks_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff83ef83da)
Location: drivers/base/node.c:841
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81b154c0-ffffffff81b1550f: register_memory_blocks_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8371df7a)
Location: drivers/base/node.c:851
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
**Symbols:**

```
ffffffff81b64230-ffffffff81b6427f: register_memory_blocks_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8395194a)
Location: drivers/base/node.c:850
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
**Symbols:**

```
ffffffff81bb7dd0-ffffffff81bb7e1f: register_memory_blocks_under_node (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
