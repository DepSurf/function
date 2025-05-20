# Function: <code>alloc_dax_mapping_reclaim</code>

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
struct fuse_dax_mapping *alloc_dax_mapping_reclaim(struct fuse_conn_dax *fcd, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d590)
Location: fs/fuse/dax.c:1028
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
**Symbols:**

```
ffffffff8149d590-ffffffff8149d68d: alloc_dax_mapping_reclaim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1028
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1027
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1024
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1024
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1024
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:1022
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
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
