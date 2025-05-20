# Function: <code>ppp_gidle</code>

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
In fs/compat_ioctl.c (ffffffff812663c1)
Location: fs/compat_ioctl.c:454
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
In fs/compat_ioctl.c (ffffffff81292781)
Location: fs/compat_ioctl.c:476
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
In fs/compat_ioctl.c (ffffffff812a7501)
Location: fs/compat_ioctl.c:476
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
In fs/compat_ioctl.c (ffffffff812b3b61)
Location: fs/compat_ioctl.c:476
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
In fs/compat_ioctl.c (ffffffff812d715c)
Location: fs/compat_ioctl.c:459
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
In fs/compat_ioctl.c (ffffffff813023d7)
Location: fs/compat_ioctl.c:457
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
In fs/compat_ioctl.c (ffffffff813177b3)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff8133f37b)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff813578c0)
Location: fs/compat_ioctl.c:321
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041a6e0)
Location: fs/compat_ioctl.c:321
Inline: True
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001041a6e0-ffff80001041abec: ppp_gidle.isra.0 (STB_LOCAL)
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
In fs/compat_ioctl.c (c00000000052ba30)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff8134fea0)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff81340b80)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff8134d970)
Location: fs/compat_ioctl.c:321
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
In fs/compat_ioctl.c (ffffffff81360ef0)
Location: fs/compat_ioctl.c:321
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
</ul>

## Differences
