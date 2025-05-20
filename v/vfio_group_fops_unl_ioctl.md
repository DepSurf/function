# Function: <code>vfio_group_fops_unl_ioctl</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1513
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817d20b0-ffffffff817d2559: vfio_group_fops_unl_ioctl (STB_LOCAL)
ffffffff817d25a1-ffffffff817d25cd: vfio_group_fops_unl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189d0c0)
Location: drivers/vfio/vfio.c:1517
Inline: False
```
**Symbols:**

```
ffffffff8189d0c0-ffffffff8189d255: vfio_group_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818abcf0)
Location: drivers/vfio/vfio.c:1518
Inline: False
```
**Symbols:**

```
ffffffff818abcf0-ffffffff818abe85: vfio_group_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188ec70)
Location: drivers/vfio/vfio.c:1417
Inline: False
```
**Symbols:**

```
ffffffff8188ec70-ffffffff8188ee05: vfio_group_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819222f0)
Location: drivers/vfio/vfio.c:1519
Inline: False
```
**Symbols:**

```
ffffffff819222f0-ffffffff81922485: vfio_group_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a778d0)
Location: drivers/vfio/vfio.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81a778d0-ffffffff81a77c2b: vfio_group_fops_unl_ioctl (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaf310)
Location: drivers/vfio/vfio.c:1513
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl
```
**Symbols:**

```
c000000000aaf310-c000000000aafc24: vfio_group_fops_unl_ioctl (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1513
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl
```
**Symbols:**

```
ffffffff8177c160-ffffffff8177c609: vfio_group_fops_unl_ioctl (STB_LOCAL)
ffffffff8177c651-ffffffff8177c67d: vfio_group_fops_unl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1513
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817c6f30-ffffffff817c73d9: vfio_group_fops_unl_ioctl (STB_LOCAL)
ffffffff817c7421-ffffffff817c744d: vfio_group_fops_unl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1513
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817e11d0-ffffffff817e1679: vfio_group_fops_unl_ioctl (STB_LOCAL)
ffffffff817e16c1-ffffffff817e16ed: vfio_group_fops_unl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
