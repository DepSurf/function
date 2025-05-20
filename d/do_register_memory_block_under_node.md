# Function: <code>do_register_memory_block_under_node</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d7f63)
Location: drivers/base/node.c:764
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:775
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff817ebdc0-ffffffff817ebe65: do_register_memory_block_under_node (STB_LOCAL)
ffffffff81c0f2ca-ffffffff81c0f30d: do_register_memory_block_under_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:778
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff817d05e0-ffffffff817d0685: do_register_memory_block_under_node (STB_LOCAL)
ffffffff81c01423-ffffffff81c01466: do_register_memory_block_under_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8185ae80)
Location: drivers/base/node.c:795
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff8185ae80-ffffffff8185b018: do_register_memory_block_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk, enum meminit_context context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff819a1de0)
Location: drivers/base/node.c:799
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff819a1de0-ffffffff819a1f8f: do_register_memory_block_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk, enum meminit_context context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b13d20)
Location: drivers/base/node.c:747
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff81b13d20-ffffffff81b13ef0: do_register_memory_block_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk, enum meminit_context context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b62a50)
Location: drivers/base/node.c:757
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff81b62a50-ffffffff81b62c20: do_register_memory_block_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block *mem_blk, enum meminit_context context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81bb6560)
Location: drivers/base/node.c:756
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_block_under_node_hotplug
  - drivers/base/node.c:register_mem_block_under_node_early
```
**Symbols:**

```
ffffffff81bb6560-ffffffff81bb6730: do_register_memory_block_under_node (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum meminit_context context</code>
</li>
</ul>
</details>
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
