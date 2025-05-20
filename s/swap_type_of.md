# Function: <code>swap_type_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d52a0)
Location: mm/swapfile.c:1036
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811d52a0-ffffffff811d53ae: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f3270)
Location: mm/swapfile.c:1035
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811f3270-ffffffff811f338c: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81203d10)
Location: mm/swapfile.c:1055
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81203d10-ffffffff81203e2c: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120f3b0)
Location: mm/swapfile.c:1467
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8120f3b0-ffffffff8120f4cb: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8122ac20)
Location: mm/swapfile.c:1679
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8122ac20-ffffffff8122ad3b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124beb0)
Location: mm/swapfile.c:1679
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8124beb0-ffffffff8124bfb6: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812603d0)
Location: mm/swapfile.c:1651
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff812603d0-ffffffff812604d6: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127b440)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8127b440-ffffffff8127b55b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128af20)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8128af20-ffffffff8128b03b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812be110)
Location: mm/swapfile.c:1797
Inline: False
Direct callers:
  - kernel/power/swap.c:get_swap_writer
  - kernel/power/user.c:snapshot_set_swap_area
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff812be110-ffffffff812be22b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9d10)
Location: mm/swapfile.c:1815
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_swap_check
  - kernel/power/user.c:snapshot_set_swap_area
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff812c9d10-ffffffff812c9dc5: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812d0780)
Location: mm/swapfile.c:1814
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff812d0780-ffffffff812d0835: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81315da0)
Location: mm/swapfile.c:1801
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81315da0-ffffffff81315e6f: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81381f00)
Location: mm/swapfile.c:1676
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81381f00-ffffffff81381fd7: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814006d0)
Location: mm/swapfile.c:1663
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff814006d0-ffffffff814007a7: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81433570)
Location: mm/swapfile.c:1645
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81433570-ffffffff81433647: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146c960)
Location: mm/swapfile.c:1645
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8146c960-ffffffff8146ca37: swap_type_of (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053dc10)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
c053dc10-c053dd68: swap_type_of (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81283500)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81283500-ffffffff8128361b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812753a0)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff812753a0-ffffffff812754bb: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281310)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81281310-ffffffff8128142b: swap_type_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int swap_type_of(dev_t device, sector_t offset, struct block_device **bdev_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81291020)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81291020-ffffffff81291166: swap_type_of (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device **bdev_p</code>
</li>
</ul>
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
