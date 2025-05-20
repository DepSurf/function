# Function: <code>sb_start_write_trylock</code>

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
In fs/pipe.c (ffffffff81215095)
Location: include/linux/fs.h:1460
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81229170)
Location: include/linux/fs.h:1460
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
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
In fs/pipe.c (ffffffff8123bf1a)
Location: include/linux/fs.h:1537
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81251880)
Location: include/linux/fs.h:1537
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
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
In fs/pipe.c (ffffffff8124ec9b)
Location: include/linux/fs.h:1503
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81264a52)
Location: include/linux/fs.h:1503
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff812f7510)
Location: include/linux/fs.h:1503
Inline: True
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
In fs/pipe.c (ffffffff8125aba1)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81272284)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff8132bed0)
Location: include/linux/fs.h:1519
Inline: True
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
In fs/pipe.c (ffffffff8127cf3e)
Location: include/linux/fs.h:1548
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81294b98)
Location: include/linux/fs.h:1548
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81350388)
Location: include/linux/fs.h:1548
Inline: True
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
In fs/pipe.c (ffffffff812a3ea1)
Location: include/linux/fs.h:1559
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812bad36)
Location: include/linux/fs.h:1559
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff8137e548)
Location: include/linux/fs.h:1559
Inline: True
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
In fs/pipe.c (ffffffff812b8fef)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812cff24)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81396df8)
Location: include/linux/fs.h:1614
Inline: True
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
In fs/pipe.c (ffffffff812d5be8)
Location: include/linux/fs.h:1630
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812ece64)
Location: include/linux/fs.h:1630
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813c0e82)
Location: include/linux/fs.h:1630
Inline: True
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
In fs/pipe.c (ffffffff812e7758)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812fe9f4)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813da1d2)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffff8131f789)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81337a94)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff814270db)
Location: include/linux/fs.h:1680
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81165d86)
Location: include/linux/fs.h:1667
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8132acac)
Location: include/linux/fs.h:1667
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433d8)
Location: include/linux/fs.h:1667
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff8143eee2)
Location: include/linux/fs.h:1667
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81166ab6)
Location: include/linux/fs.h:1836
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8133095f)
Location: include/linux/fs.h:1836
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496c8)
Location: include/linux/fs.h:1836
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81444d22)
Location: include/linux/fs.h:1836
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8118c276)
Location: include/linux/fs.h:1886
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8137e0df)
Location: include/linux/fs.h:1886
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81397418)
Location: include/linux/fs.h:1886
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81498bb2)
Location: include/linux/fs.h:1886
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811bb687)
Location: include/linux/fs.h:1777
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff813fdd0f)
Location: include/linux/fs.h:1777
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814195d7)
Location: include/linux/fs.h:1777
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81523a73)
Location: include/linux/fs.h:1777
Inline: True
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
In kernel/acct.c (ffffffff811fd4a7)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8148792f)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5017)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff815c0c5a)
Location: include/linux/fs.h:1892
Inline: True
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
In kernel/acct.c (ffffffff81212634)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814bc790)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da297)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff815f83da)
Location: include/linux/fs.h:1572
Inline: True
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
In kernel/acct.c (ffffffff81229cb4)
Location: include/linux/fs.h:1780
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814eecd7)
Location: include/linux/fs.h:1780
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c886)
Location: include/linux/fs.h:1780
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff81630f8a)
Location: include/linux/fs.h:1780
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
In fs/pipe.c (ffff800010390474)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffff8000103af91c)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffff8000104ad828)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (c0576f38)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (c058f6fc)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (c067659c)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (c000000000488008)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (c0000000004ab500)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (c0000000005e65d0)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffe00025fe28)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffe00027433c)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffe000330bc2)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffff812dfd38)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812f6fd4)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813d27b2)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffff812d0978)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812e7bf4)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813c3232)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffff812ddb48)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812f4de4)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813cfc42)
Location: include/linux/fs.h:1656
Inline: True
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
In fs/pipe.c (ffffffff812eeac8)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81305f74)
Location: include/linux/fs.h:1656
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/super.c (ffffffff813e523d)
Location: include/linux/fs.h:1656
Inline: True
```
</details>
</li>
</ul>

## Differences
