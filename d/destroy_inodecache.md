# Function: <code>destroy_inodecache</code>

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
In fs/ext4/super.c (ffffffff820af463)
Location: fs/ext4/super.c:981
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff820e70cc)
Location: fs/ext4/super.c:1007
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
```
```
In fs/squashfs/super.c (ffffffff820e7136)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff821ccfdc)
Location: fs/ext4/super.c:1012
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
```
```
In fs/squashfs/super.c (ffffffff821cd046)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff822c213b)
Location: fs/ext4/super.c:1054
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
```
```
In fs/squashfs/super.c (ffffffff822c21a6)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828d52bb)
Location: fs/ext4/super.c:1055
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
```
```
In fs/squashfs/super.c (ffffffff828d5326)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82906b0d)
Location: fs/ext4/super.c:1096
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82906b78)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82ade8cf)
Location: fs/ext4/super.c:1150
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82ade93f)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82b039f2)
Location: fs/ext4/super.c:1163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82b03a62)
Location: fs/squashfs/super.c:417
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82b1289f)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82b12914)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82f2431a)
Location: fs/ext4/super.c:1206
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82f2438f)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8321c8ba)
Location: fs/ext4/super.c:1371
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff8321c92f)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff834508b7)
Location: fs/ext4/super.c:1380
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff8345092c)
Location: fs/squashfs/super.c:429
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83543e41)
Location: fs/ext4/super.c:1386
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83543eb6)
Location: fs/squashfs/super.c:513
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83721ddd)
Location: fs/ext4/super.c:1426
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83721e6e)
Location: fs/squashfs/super.c:547
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff842af908)
Location: fs/ext4/super.c:1421
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff842af9f0)
Location: fs/squashfs/super.c:608
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83af2488)
Location: fs/ext4/super.c:1487
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83af2570)
Location: fs/squashfs/super.c:625
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83d4e198)
Location: fs/ext4/super.c:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83d4e280)
Location: fs/squashfs/super.c:625
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000114b87a0)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffff8000114b8830)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c15bea6c)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (c15beb04)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000013cb8c4)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (c0000000013cb9bc)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0000a08c0)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffe0000a097e)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82af2abf)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82af2b34)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82ac2ee7)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82ac2f5c)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82b0db87)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82b0dbfc)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82b026d7)
Location: fs/ext4/super.c:1171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82b0274c)
Location: fs/squashfs/super.c:430
Inline: True
Inline callers:
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
```
</details>
</li>
</ul>

## Differences
