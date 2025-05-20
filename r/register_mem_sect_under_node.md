# Function: <code>register_mem_sect_under_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815609d0)
Location: drivers/base/node.c:379
Inline: True
Direct callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815609d0-ffffffff81560ae5: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815b5120)
Location: drivers/base/node.c:390
Inline: True
Direct callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815b5120-ffffffff815b522d: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815e43d0)
Location: drivers/base/node.c:390
Inline: True
Direct callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815e43d0-ffffffff815e44dd: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815f8fd0)
Location: drivers/base/node.c:383
Inline: True
Direct callers:
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815f8fd0-ffffffff815f90d6: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81661090)
Location: drivers/base/node.c:400
Inline: True
Direct callers:
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff81661090-ffffffff816611aa: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, int nid, bool check_nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8169c840)
Location: drivers/base/node.c:402
Inline: True
Direct callers:
  - drivers/base/node.c:link_mem_sections
  - drivers/base/memory.c:hotplug_memory_register
```
**Symbols:**

```
ffffffff8169c840-ffffffff8169c97a: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bc6f0)
Location: drivers/base/node.c:407
Inline: False
```
**Symbols:**

```
ffffffff816bc6f0-ffffffff816bc7fe: register_mem_sect_under_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f6f50)
Location: drivers/base/node.c:756
Inline: False
```
**Symbols:**

```
ffffffff816f6f50-ffffffff816f703b: register_mem_sect_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8171b360)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffffffff8171b360-ffffffff8171b454: register_mem_sect_under_node (STB_LOCAL)
```
</details>
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
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffff80001090ec90)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffff80001090ec90-ffff80001090edd8: register_mem_sect_under_node (STB_LOCAL)
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
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (c0000000009af770)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
c0000000009af770-c0000000009af938: register_mem_sect_under_node (STB_LOCAL)
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
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816e1690)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffffffff816e1690-ffffffff816e1784: register_mem_sect_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bbcd0)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffffffff816bbcd0-ffffffff816bbdc4: register_mem_sect_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8170ebc0)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffffffff8170ebc0-ffffffff8170ecb4: register_mem_sect_under_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_mem_sect_under_node(struct memory_block *mem_blk, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81729980)
Location: drivers/base/node.c:762
Inline: False
```
**Symbols:**

```
ffffffff81729980-ffffffff81729a74: register_mem_sect_under_node (STB_LOCAL)
```
</details>
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
<code>void *arg</code>
</li>
<li>
<b>Param removed. </b>
<code>int nid</code>
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
