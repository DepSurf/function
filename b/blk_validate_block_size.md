# Function: <code>blk_validate_block_size</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186ef95)
Location: include/linux/blkdev.h:238
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
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
In drivers/block/loop.c (ffffffff819b7fa9)
Location: include/linux/blkdev.h:215
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
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
In drivers/block/loop.c (ffffffff81b2d2f9)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
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
In drivers/block/loop.c (ffffffff81b7d62e)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/block/virtio_blk.c (ffffffff81b81013)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
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
In drivers/block/loop.c (ffffffff81bd15ae)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4fac)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
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
