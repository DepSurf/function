# Function: <code>dm_blk_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a07a0)
Location: drivers/md/dm.c:601
Inline: False
```
**Symbols:**

```
ffffffff816a07a0-ffffffff816a0854: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701b30)
Location: drivers/md/dm.c:457
Inline: False
```
**Symbols:**

```
ffffffff81701b30-ffffffff81701ba5: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733880)
Location: drivers/md/dm.c:457
Inline: False
```
**Symbols:**

```
ffffffff81733880-ffffffff817338f5: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ca90)
Location: drivers/md/dm.c:452
Inline: False
```
**Symbols:**

```
ffffffff8174ca90-ffffffff8174cb47: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bec70)
Location: drivers/md/dm.c:459
Inline: False
```
**Symbols:**

```
ffffffff817bec70-ffffffff817bed27: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:502
Inline: False
```
**Symbols:**

```
ffffffff81807250-ffffffff81807324: dm_blk_ioctl (STB_LOCAL)
ffffffff8180a97f-ffffffff8180a9a9: dm_blk_ioctl.cold.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:553
Inline: False
```
**Symbols:**

```
ffffffff81833280-ffffffff81833354: dm_blk_ioctl (STB_LOCAL)
ffffffff8183697f-ffffffff818369a9: dm_blk_ioctl.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff81877590-ffffffff81877670: dm_blk_ioctl (STB_LOCAL)
ffffffff818795b3-ffffffff818795dd: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff818a9320-ffffffff818a9400: dm_blk_ioctl (STB_LOCAL)
ffffffff818ab3cd-ffffffff818ab3f7: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:564
Inline: False
```
**Symbols:**

```
ffffffff81978ba0-ffffffff81978c80: dm_blk_ioctl (STB_LOCAL)
ffffffff8197b59e-ffffffff8197b5c8: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197de10)
Location: drivers/md/dm.c:559
Inline: False
```
**Symbols:**

```
ffffffff8197de10-ffffffff8197df3f: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81961bc0)
Location: drivers/md/dm.c:564
Inline: False
```
**Symbols:**

```
ffffffff81961bc0-ffffffff81961cef: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a08da0)
Location: drivers/md/dm.c:445
Inline: False
```
**Symbols:**

```
ffffffff81a08da0-ffffffff81a08ec8: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b70b10)
Location: drivers/md/dm.c:454
Inline: False
```
**Symbols:**

```
ffffffff81b70b10-ffffffff81b70c3b: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d8b0)
Location: drivers/md/dm.c:449
Inline: False
```
**Symbols:**

```
ffffffff81d0d8b0-ffffffff81d0d9db: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d76810)
Location: drivers/md/dm.c:451
Inline: False
```
**Symbols:**

```
ffffffff81d76810-ffffffff81d76935: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2da40)
Location: drivers/md/dm.c:451
Inline: False
```
**Symbols:**

```
ffffffff81e2da40-ffffffff81e2db65: dm_blk_ioctl (STB_LOCAL)
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
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afd5e0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffff800010afd5e0-ffff800010afd6fc: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdf3a4)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
c0bdf3a4-c0bdf4f8: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bee660)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
c000000000bee660-c000000000bee7c0: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef51e)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffe0006ef51e-ffffffe0006ef5ec: dm_blk_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff8184f1a0-ffffffff8184f280: dm_blk_ioctl (STB_LOCAL)
ffffffff8185124d-ffffffff81851277: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff818167b0-ffffffff81816890: dm_blk_ioctl (STB_LOCAL)
ffffffff8181885d-ffffffff81818887: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff8189e7d0-ffffffff8189e8b0: dm_blk_ioctl (STB_LOCAL)
ffffffff818a087d-ffffffff818a08a7: dm_blk_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dm_blk_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:533
Inline: False
```
**Symbols:**

```
ffffffff818bacf0-ffffffff818badd0: dm_blk_ioctl (STB_LOCAL)
ffffffff818bcaff-ffffffff818bcb29: dm_blk_ioctl.cold (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
