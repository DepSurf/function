# Function: <code>sg_ioctl_trans</code>

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
In fs/compat_ioctl.c (ffffffff81265bc2)
Location: fs/compat_ioctl.c:279
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
In fs/compat_ioctl.c (ffffffff81291db3)
Location: fs/compat_ioctl.c:301
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
In fs/compat_ioctl.c (ffffffff812a6b33)
Location: fs/compat_ioctl.c:301
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
In fs/compat_ioctl.c (ffffffff812b3122)
Location: fs/compat_ioctl.c:301
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
In fs/compat_ioctl.c (ffffffff812d6ea2)
Location: fs/compat_ioctl.c:284
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
In fs/compat_ioctl.c (ffffffff813020f0)
Location: fs/compat_ioctl.c:282
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
In fs/compat_ioctl.c (ffffffff81317535)
Location: fs/compat_ioctl.c:146
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sg_ioctl_trans(struct file *file, unsigned int cmd, sg_io_hdr32_t *sgio32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133ed90)
Location: fs/compat_ioctl.c:146
Inline: False
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
**Symbols:**

```
ffffffff8133ed90-ffffffff8133f069: sg_ioctl_trans (STB_LOCAL)
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
In fs/compat_ioctl.c (ffffffff81357625)
Location: fs/compat_ioctl.c:146
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
int sg_ioctl_trans(struct file *file, unsigned int cmd, sg_io_hdr32_t *sgio32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041c490)
Location: fs/compat_ioctl.c:146
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
**Symbols:**

```
ffff80001041c490-ffff80001041d09c: sg_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sg_ioctl_trans(struct file *file, unsigned int cmd, sg_io_hdr32_t *sgio32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052a690)
Location: fs/compat_ioctl.c:146
Inline: False
Direct callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
```
**Symbols:**

```
c00000000052a690-c00000000052b0ac: sg_ioctl_trans (STB_LOCAL)
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
In fs/compat_ioctl.c (ffffffff8134fc05)
Location: fs/compat_ioctl.c:146
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
In fs/compat_ioctl.c (ffffffff813408e5)
Location: fs/compat_ioctl.c:146
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
In fs/compat_ioctl.c (ffffffff8134d6d5)
Location: fs/compat_ioctl.c:146
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
In fs/compat_ioctl.c (ffffffff81360c55)
Location: fs/compat_ioctl.c:146
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
