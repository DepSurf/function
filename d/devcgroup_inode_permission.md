# Function: <code>devcgroup_inode_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216e86)
Location: include/linux/device_cgroup.h:6
Inline: True
```
```
In fs/block_dev.c (ffffffff81248a06)
Location: include/linux/device_cgroup.h:6
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123dd17)
Location: include/linux/device_cgroup.h:6
Inline: True
```
```
In fs/block_dev.c (ffffffff8127186a)
Location: include/linux/device_cgroup.h:6
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250af7)
Location: include/linux/device_cgroup.h:6
Inline: True
```
```
In fs/block_dev.c (ffffffff81284d7f)
Location: include/linux/device_cgroup.h:6
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cc76)
Location: include/linux/device_cgroup.h:6
Inline: True
```
```
In fs/block_dev.c (ffffffff812920bf)
Location: include/linux/device_cgroup.h:6
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127effc)
Location: include/linux/device_cgroup.h:35
Inline: True
```
```
In fs/block_dev.c (ffffffff812b4e4a)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a79c0)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812dcfd4)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bca60)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812f2434)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9562)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81313e6b)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb072)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132764b)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813236c0)
Location: include/linux/device_cgroup.h:17
Inline: True
```
```
In fs/block_dev.c (ffffffff81360950)
Location: include/linux/device_cgroup.h:17
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132ec60)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff813349d4)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff81382314)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff814017be)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff8148b8be)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff814bf95e)
Location: include/linux/device_cgroup.h:17
Inline: True
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
In fs/namei.c (ffffffff814f1e4e)
Location: include/linux/device_cgroup.h:17
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010394754)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffff8000103e25b0)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579c34)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c05ba78c)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b140)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c0000000004e8294)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000263248)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffe000298a5a)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3652)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131fc2b)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d4292)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff813107cb)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1462)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131d6fb)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0a42)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132f3fb)
Location: include/linux/device_cgroup.h:35
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
</ul>

## Differences
