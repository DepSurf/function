# Function: <code>ioctl_file_dedupe_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81247985)
Location: fs/ioctl.c:571
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
In fs/ioctl.c (ffffffff8125a9c5)
Location: fs/ioctl.c:575
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
In fs/ioctl.c (ffffffff812673be)
Location: fs/ioctl.c:577
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
In fs/ioctl.c (ffffffff81289c57)
Location: fs/ioctl.c:578
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
In fs/ioctl.c (ffffffff812b00e9)
Location: fs/ioctl.c:578
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
In fs/ioctl.c (ffffffff812c5237)
Location: fs/ioctl.c:587
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
In fs/ioctl.c (ffffffff812e1c7a)
Location: fs/ioctl.c:587
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812f374a)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ioctl_file_dedupe_range(struct file *file, struct file_dedupe_range *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132b290)
Location: fs/ioctl.c:620
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8132b290-ffffffff8132b360: ioctl_file_dedupe_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioctl_file_dedupe_range(struct file *file, struct file_dedupe_range *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81336850)
Location: fs/ioctl.c:620
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81336850-ffffffff81336920: ioctl_file_dedupe_range (STB_LOCAL)
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
In fs/ioctl.c (ffffffff8133d79e)
Location: fs/ioctl.c:623
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff8138b11e)
Location: fs/ioctl.c:420
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff8140c40c)
Location: fs/ioctl.c:416
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff81496e43)
Location: fs/ioctl.c:416
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff814cbf5b)
Location: fs/ioctl.c:416
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
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
In fs/ioctl.c (ffffffff814fe810)
Location: fs/ioctl.c:417
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffff80001039e76c)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0583c94)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (c0000000004990b8)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffe000269bda)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812ebd2a)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812dc95a)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812e9b3a)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff812fab3a)
Location: fs/ioctl.c:588
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
