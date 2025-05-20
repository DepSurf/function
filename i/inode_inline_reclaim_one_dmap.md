# Function: <code>inode_inline_reclaim_one_dmap</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fuse_dax_mapping *inode_inline_reclaim_one_dmap(struct fuse_conn_dax *fcd, struct inode *inode, bool *retry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d330)
Location: fs/fuse/dax.c:952
Inline: False
Direct callers:
  - fs/fuse/dax.c:alloc_dax_mapping_reclaim
```
**Symbols:**

```
ffffffff8149d330-ffffffff8149d583: inode_inline_reclaim_one_dmap (STB_LOCAL)
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
In fs/fuse/dax.c (ffffffff814a3580)
Location: fs/fuse/dax.c:952
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff814a3580-ffffffff814a37d3: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fb600)
Location: fs/fuse/dax.c:951
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff814fb600-ffffffff814fb833: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158bae0)
Location: fs/fuse/dax.c:948
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff8158bae0-ffffffff8158bd26: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (ffffffff81632310)
Location: fs/fuse/dax.c:948
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff81632310-ffffffff81632556: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166a260)
Location: fs/fuse/dax.c:948
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff8166a260-ffffffff8166a4a4: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a45a0)
Location: fs/fuse/dax.c:946
Inline: True
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff816a45a0-ffffffff816a47e4: inode_inline_reclaim_one_dmap.constprop.0 (STB_LOCAL)
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
</ul>
