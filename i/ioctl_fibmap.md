# Function: <code>ioctl_fibmap</code>

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
In fs/ioctl.c (ffffffff81220254)
Location: fs/ioctl.c:50
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
In fs/ioctl.c (ffffffff81247ced)
Location: fs/ioctl.c:50
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
In fs/ioctl.c (ffffffff8125ad2d)
Location: fs/ioctl.c:50
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
In fs/ioctl.c (ffffffff8126770a)
Location: fs/ioctl.c:52
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
In fs/ioctl.c (ffffffff81289fac)
Location: fs/ioctl.c:53
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
In fs/ioctl.c (ffffffff812b0329)
Location: fs/ioctl.c:53
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
In fs/ioctl.c (ffffffff812c5482)
Location: fs/ioctl.c:54
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
In fs/ioctl.c (ffffffff812e1f26)
Location: fs/ioctl.c:54
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
In fs/ioctl.c (ffffffff812f39f6)
Location: fs/ioctl.c:55
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ioctl_fibmap(struct file *filp, int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ioctl.c (0)
Location: fs/ioctl.c:56
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8132b360-ffffffff8132b45d: ioctl_fibmap (STB_LOCAL)
ffffffff8132c28d-ffffffff8132c2c4: ioctl_fibmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ioctl_fibmap(struct file *filp, int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ioctl.c (0)
Location: fs/ioctl.c:56
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81336920-ffffffff81336a1d: ioctl_fibmap (STB_LOCAL)
ffffffff81bea66b-ffffffff81bea6a2: ioctl_fibmap.cold (STB_LOCAL)
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
In fs/ioctl.c (ffffffff8133dabb)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffffffff8138b43b)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffffffff8140c764)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffffffff8149719f)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffffffff814cc1c1)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffffffff814fea80)
Location: fs/ioctl.c:59
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
In fs/ioctl.c (ffff80001039eeb4)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (c05835bc)
Location: fs/ioctl.c:55
Inline: True
Inline callers:
  - fs/ioctl.c:file_ioctl
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
In fs/ioctl.c (c000000000499528)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (ffffffe000269b68)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (ffffffff812ebfd6)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (ffffffff812dcc06)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (ffffffff812e9de6)
Location: fs/ioctl.c:55
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
In fs/ioctl.c (ffffffff812fade4)
Location: fs/ioctl.c:55
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
