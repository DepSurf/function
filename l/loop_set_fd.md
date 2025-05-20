# Function: <code>loop_set_fd</code>

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
In drivers/block/loop.c (ffffffff8156fce0)
Location: drivers/block/loop.c:905
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff815c5600)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff815f3cfc)
Location: drivers/block/loop.c:876
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff81608027)
Location: drivers/block/loop.c:906
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816709c8)
Location: drivers/block/loop.c:895
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816ac09c)
Location: drivers/block/loop.c:946
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816cdb69)
Location: drivers/block/loop.c:943
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81708640)
Location: drivers/block/loop.c:961
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81708640-ffffffff81708b03: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172c890)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8172c890-ffffffff8172cdee: loop_set_fd (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010922788)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffff800010922788-ffff800010922c28: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a06054)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0a06054-c0a064d4: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c8010)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0000000009c8010-c0000000009c863c: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a14c8)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffe0005a14c8-ffffffe0005a18e0: loop_set_fd (STB_LOCAL)
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
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f2670)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816f2670-ffffffff816f2bce: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cc770)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cc770-ffffffff816cccce: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171fd50)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8171fd50-ffffffff817202ae: loop_set_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int loop_set_fd(struct loop_device *lo, fmode_t mode, struct block_device *bdev, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8173b110)
Location: drivers/block/loop.c:971
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8173b110-ffffffff8173b66e: loop_set_fd (STB_LOCAL)
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
