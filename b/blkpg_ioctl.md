# Function: <code>blkpg_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff813c8ac0)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff813c8ac0-ffffffff813c8f1e: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8140cd20)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8140cd20-ffffffff8140d176: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81428000)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81428000-ffffffff81428498: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81436350)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81436350-ffffffff814367f0: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814620e0)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814620e0-ffffffff81462580: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81495a00)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81495a00-ffffffff81495ea2: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814af8b0)
Location: block/ioctl.c:13
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814af8b0-ffffffff814afd52: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814ddc60)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814ddc60-ffffffff814de121: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814f70c0)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814f70c0-ffffffff814f757e: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8155874f)
Location: block/ioctl.c:60
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff81574d4b)
Location: block/ioctl.c:51
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff8157cddb)
Location: block/ioctl.c:51
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff815e2429)
Location: block/ioctl.c:52
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff81691060)
Location: block/ioctl.c:52
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff8174fc5c)
Location: block/ioctl.c:52
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff8178bf09)
Location: block/ioctl.c:54
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/ioctl.c (ffffffff817ce6a9)
Location: block/ioctl.c:55
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffff8000105f7fa8)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffff8000105f7fa8-ffff8000105f83bc: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c07a312c)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c07a312c-c07a36c0: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c0000000007900c0)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
c0000000007900c0-c000000000790604: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffe000434e8a)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffe000434e8a-ffffffe0004351fa: blkpg_ioctl (STB_LOCAL)
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
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814ef6a0)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814ef6a0-ffffffff814efb5e: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814dfbe0)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814dfbe0-ffffffff814e009e: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814eb730)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff814eb730-ffffffff814ebbee: blkpg_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkpg_ioctl(struct block_device *bdev, struct blkpg_ioctl_arg *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81504740)
Location: block/ioctl.c:14
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81504740-ffffffff81504bfe: blkpg_ioctl (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
