# Function: <code>fiemap_check_ranges</code>

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
In fs/ioctl.c (ffffffff8121ff26)
Location: fs/ioctl.c:151
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff81247ba4)
Location: fs/ioctl.c:151
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff8125abe4)
Location: fs/ioctl.c:151
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff81267538)
Location: fs/ioctl.c:153
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff81289dd4)
Location: fs/ioctl.c:154
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff812b019c)
Location: fs/ioctl.c:154
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff812c52ea)
Location: fs/ioctl.c:155
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e1b1d)
Location: fs/ioctl.c:155
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff812f35ed)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffff813b6bde)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039e368)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffff80001048c420)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (c05838fc)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (c064dc50)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (c000000000498e00)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (c0000000005b30ec)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (ffffffe000269aea)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffe0003126d4)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (ffffffff812ebbcd)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffff813af1be)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (ffffffff812dc7fd)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffff8139fc4e)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (ffffffff812e99dd)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffff813aca1e)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
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
In fs/ioctl.c (ffffffff812fa9dd)
Location: fs/ioctl.c:156
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/ext4/ioctl.c (ffffffff813c13be)
Location: fs/ext4/ioctl.c:749
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
</ul>

## Differences
