# Function: <code>ppp_sock_fprog_ioctl_trans</code>

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
In fs/compat_ioctl.c (ffffffff81265efe)
Location: fs/compat_ioctl.c:415
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
In fs/compat_ioctl.c (ffffffff812920cc)
Location: fs/compat_ioctl.c:437
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
In fs/compat_ioctl.c (ffffffff812a6e4c)
Location: fs/compat_ioctl.c:437
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
In fs/compat_ioctl.c (ffffffff812b34d5)
Location: fs/compat_ioctl.c:437
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
In fs/compat_ioctl.c (ffffffff812d72ea)
Location: fs/compat_ioctl.c:420
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
In fs/compat_ioctl.c (ffffffff81301c81)
Location: fs/compat_ioctl.c:418
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
In fs/compat_ioctl.c (ffffffff81317be6)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff8133f0cb)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff813573de)
Location: fs/compat_ioctl.c:282
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
int ppp_sock_fprog_ioctl_trans(struct file *file, unsigned int cmd, struct sock_fprog32 *u_fprog32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041a1a8)
Location: fs/compat_ioctl.c:282
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001041a1a8-ffff80001041a6dc: ppp_sock_fprog_ioctl_trans (STB_LOCAL)
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
In fs/compat_ioctl.c (c00000000052bc40)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff8134f9be)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff8134069e)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff8134d48e)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff81360a0e)
Location: fs/compat_ioctl.c:282
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
