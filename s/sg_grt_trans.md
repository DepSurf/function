# Function: <code>sg_grt_trans</code>

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
In fs/compat_ioctl.c (ffffffff812665b4)
Location: fs/compat_ioctl.c:383
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812926da)
Location: fs/compat_ioctl.c:405
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812a745a)
Location: fs/compat_ioctl.c:405
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812b3a89)
Location: fs/compat_ioctl.c:405
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff812d6ca9)
Location: fs/compat_ioctl.c:388
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff81301b88)
Location: fs/compat_ioctl.c:386
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff81317b12)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff8133f4a5)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff813579eb)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
int sg_grt_trans(struct file *file, unsigned int cmd, struct compat_sg_req_info *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041b228)
Location: fs/compat_ioctl.c:250
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001041b228-ffff80001041b8c0: sg_grt_trans (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052b7e0)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/compat_ioctl.c (ffffffff8134ffcb)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff81340cab)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff8134da9b)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
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
In fs/compat_ioctl.c (ffffffff8136101b)
Location: fs/compat_ioctl.c:250
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
