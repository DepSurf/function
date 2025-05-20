# Function: <code>fuse_is_inode_dax_mode</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584f9a)
Location: fs/fuse/fuse_i.h:491
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
```
In fs/fuse/dax.c (ffffffff8158c879)
Location: fs/fuse/fuse_i.h:491
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162b14a)
Location: fs/fuse/fuse_i.h:491
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
```
In fs/fuse/dax.c (ffffffff81633169)
Location: fs/fuse/fuse_i.h:491
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8166336a)
Location: fs/fuse/fuse_i.h:493
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
```
In fs/fuse/dax.c (ffffffff8166b459)
Location: fs/fuse/fuse_i.h:493
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169d4e9)
Location: fs/fuse/fuse_i.h:513
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
```
In fs/fuse/dax.c (ffffffff816a57d9)
Location: fs/fuse/fuse_i.h:513
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
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
