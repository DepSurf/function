# Function: <code>__ext4_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81414520)
Location: fs/ext4/ioctl.c:812
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff81414520-ffffffff814154a4: __ext4_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8141a790)
Location: fs/ext4/ioctl.c:803
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff8141a790-ffffffff8141b53f: __ext4_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ioctl.c:852
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff8146d970-ffffffff8146e857: __ext4_ioctl (STB_LOCAL)
ffffffff81ccb1aa-ffffffff81ccb1c9: __ext4_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ioctl.c (0)
Location: fs/ext4/ioctl.c:1134
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff814ee220-ffffffff814ef212: __ext4_ioctl (STB_LOCAL)
ffffffff81e7e074-ffffffff81e7e09f: __ext4_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81588110)
Location: fs/ext4/ioctl.c:1216
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff81588110-ffffffff81589448: __ext4_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815beb10)
Location: fs/ext4/ioctl.c:1223
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff815beb10-ffffffff815bfc70: __ext4_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ext4_ioctl(struct file *filp, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815f78c0)
Location: fs/ext4/ioctl.c:1233
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
**Symbols:**

```
ffffffff815f78c0-ffffffff815f8a06: __ext4_ioctl (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
