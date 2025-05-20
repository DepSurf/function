# Function: <code>unregister_mem_sect_under_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81560af0)
Location: drivers/base/node.c:425
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff81560af0-ffffffff81560bc3: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815b5230)
Location: drivers/base/node.c:436
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff815b5230-ffffffff815b530a: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815e44e0)
Location: drivers/base/node.c:436
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff815e44e0-ffffffff815e45d9: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815f90e0)
Location: drivers/base/node.c:429
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff815f90e0-ffffffff815f91cf: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816611b0)
Location: drivers/base/node.c:446
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff816611b0-ffffffff8166129f: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8169c980)
Location: drivers/base/node.c:458
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff8169c980-ffffffff8169ca6f: unregister_mem_sect_under_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_mem_sect_under_nodes(struct memory_block *mem_blk, long unsigned int phys_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bd1d0)
Location: drivers/base/node.c:457
Inline: False
Direct callers:
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff816bd1d0-ffffffff816bd2bf: unregister_mem_sect_under_nodes (STB_GLOBAL)
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
