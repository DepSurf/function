# Function: <code>trace_ext4_ext_convert_to_initialized_fastpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81322db8)
Location: include/trace/events/ext4.h:1564
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff81322db8-ffffffff81322e27: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81357af8)
Location: include/trace/events/ext4.h:1564
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81357af8-ffffffff81357b60: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8136dff5)
Location: include/trace/events/ext4.h:1564
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8136dff5-ffffffff8136e05d: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e6920)
Location: include/trace/events/ext4.h:1546
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff812e6920-ffffffff812e698c: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130b330)
Location: include/trace/events/ext4.h:1547
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8130b330-ffffffff8130b3a7: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813392e0)
Location: include/trace/events/ext4.h:1547
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813392e0-ffffffff81339357: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81350650)
Location: include/trace/events/ext4.h:1568
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff81350650-ffffffff813506c7: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ea6f)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81397132)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813de220)
Location: include/trace/events/ext4.h:1593
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813de220-ffffffff813de28e: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813efb10)
Location: include/trace/events/ext4.h:1620
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813efb10-ffffffff813efb55: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f5c90)
Location: include/trace/events/ext4.h:1562
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813f5c90-ffffffff813f5cd5: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81448510)
Location: include/trace/events/ext4.h:1562
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff81448510-ffffffff81448552: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c4db0)
Location: include/trace/events/ext4.h:1568
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff814c4db0-ffffffff814c4e4c: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155cfa0)
Location: include/trace/events/ext4.h:1570
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8155cfa0-ffffffff8155d03c: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81594dc0)
Location: include/trace/events/ext4.h:1577
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff81594dc0-ffffffff81594e5c: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_ext4_ext_convert_to_initialized_fastpath(struct inode *inode, struct ext4_map_blocks *map, struct ext4_extent *ux, struct ext4_extent *ix);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cda70)
Location: include/trace/events/ext4.h:1574
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff815cda70-ffffffff815cdb0c: trace_ext4_ext_convert_to_initialized_fastpath (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010469e1c)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062ac4c)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058900c)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f7718)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138f712)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813801a2)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138d072)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a0dc2)
Location: include/trace/events/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
