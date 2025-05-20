# Function: <code>dm_grab_bdev_for_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device *md, struct block_device **bdev, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701630)
Location: drivers/md/dm.c:413
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81701630-ffffffff81701751: dm_grab_bdev_for_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device *md, struct block_device **bdev, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733390)
Location: drivers/md/dm.c:413
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff81733390-ffffffff817334ad: dm_grab_bdev_for_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device *md, struct block_device **bdev, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174c6b0)
Location: drivers/md/dm.c:408
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8174c6b0-ffffffff8174c7cc: dm_grab_bdev_for_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device *md, struct block_device **bdev, fmode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817be880)
Location: drivers/md/dm.c:415
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff817be880-ffffffff817be999: dm_grab_bdev_for_ioctl (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
