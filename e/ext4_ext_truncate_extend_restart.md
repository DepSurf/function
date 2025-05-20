# Function: <code>ext4_ext_truncate_extend_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_ext_truncate_extend_restart(handle_t *handle, struct inode *inode, int needed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c31d0)
Location: fs/ext4/extents.c:115
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812c31d0-ffffffff812c3222: ext4_ext_truncate_extend_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f639c)
Location: fs/ext4/extents.c:115
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812f2bc0-ffffffff812f2c0c: ext4_ext_truncate_extend_restart.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130c34c)
Location: fs/ext4/extents.c:115
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81308b90-ffffffff81308bdc: ext4_ext_truncate_extend_restart.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812eaba8)
Location: fs/ext4/extents.c:115
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812e7360-ffffffff812e73ae: ext4_ext_truncate_extend_restart.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130f64b)
Location: fs/ext4/extents.c:115
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8130bd60-ffffffff8130bdae: ext4_ext_truncate_extend_restart.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133b010)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81339470-ffffffff813394bd: ext4_ext_truncate_extend_restart.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff81352392)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81351080-ffffffff813510cd: ext4_ext_truncate_extend_restart.part.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137bcd0)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81379c80-ffffffff81379cd2: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff813941a0)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff813921a0-ffffffff813921f2: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffff800010466ed8)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffff800010464800-ffff800010464888: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (c0627a04)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
c06254d0-c0625530: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (c000000000585064)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
c000000000582790-c000000000582840: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f4e5c)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffe0002f3394-ffffffe0002f33f2: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138c780)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8138a780-ffffffff8138a7d2: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137d210)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8137b210-ffffffff8137b262: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138a0e0)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff813880e0-ffffffff81388132: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139de10)
Location: fs/ext4/extents.c:103
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
Direct callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff8139bde0-ffffffff8139be32: ext4_ext_truncate_extend_restart.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
