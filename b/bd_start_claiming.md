# Function: <code>bd_start_claiming</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81249059)
Location: fs/block_dev.c:839
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271b79)
Location: fs/block_dev.c:917
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812851d9)
Location: fs/block_dev.c:1169
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292861)
Location: fs/block_dev.c:1094
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5671)
Location: fs/block_dev.c:1084
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd4d3)
Location: fs/block_dev.c:1106
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2ab3)
Location: fs/block_dev.c:1145
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813144d0)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff813144d0-ffffffff813146ae: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326e40)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81326e40-ffffffff8132701e: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813612d0)
Location: fs/block_dev.c:1123
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff813612d0-ffffffff813614a6: bd_start_claiming (STB_GLOBAL)
```
</details>
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
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e15c8)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff8000103e15c8-ffff8000103e1818: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9a70)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c05b9a70-c05b9c6c: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7520)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000004e7520-c0000000004e7854: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe00029823a)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe00029823a-ffffffe000298458: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f420)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131f420-ffffffff8131f5fe: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130ffc0)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8130ffc0-ffffffff8131019e: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cef0)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131cef0-ffffffff8131d0ce: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct block_device *bd_start_claiming(struct block_device *bdev, void *holder);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ebe0)
Location: fs/block_dev.c:1142
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8132ebe0-ffffffff8132edb0: bd_start_claiming (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
