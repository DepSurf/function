# Function: <code>inode_reclaim_dmap_range</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:308
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff8149cdb0-ffffffff8149cf1d: inode_reclaim_dmap_range.constprop.0 (STB_LOCAL)
ffffffff81bef7bb-ffffffff81bef7d2: inode_reclaim_dmap_range.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:308
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
**Symbols:**

```
ffffffff814a2de0-ffffffff814a2f4d: inode_reclaim_dmap_range.constprop.0 (STB_LOCAL)
ffffffff81be1863-ffffffff81be187a: inode_reclaim_dmap_range.constprop.0.cold (STB_LOCAL)
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
In fs/fuse/dax.c (ffffffff814fb06a)
Location: fs/fuse/dax.c:309
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dax.c (ffffffff8158b53a)
Location: fs/fuse/dax.c:309
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dax.c (ffffffff81631d7a)
Location: fs/fuse/dax.c:309
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dax.c (ffffffff81669fba)
Location: fs/fuse/dax.c:309
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dax.c (ffffffff816a42fa)
Location: fs/fuse/dax.c:309
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
