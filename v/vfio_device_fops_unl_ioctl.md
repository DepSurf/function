# Function: <code>vfio_device_fops_unl_ioctl</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0115)
Location: drivers/vfio/vfio.c:1667
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817d00e0-ffffffff817d0110: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189ab40)
Location: drivers/vfio/vfio.c:1660
Inline: False
```
**Symbols:**

```
ffffffff8189ab40-ffffffff8189ab70: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a96f0)
Location: drivers/vfio/vfio.c:1661
Inline: False
```
**Symbols:**

```
ffffffff818a96f0-ffffffff818a9720: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188cab0)
Location: drivers/vfio/vfio.c:1560
Inline: False
```
**Symbols:**

```
ffffffff8188cab0-ffffffff8188cadc: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8191ff90)
Location: drivers/vfio/vfio.c:1667
Inline: False
```
**Symbols:**

```
ffffffff8191ff90-ffffffff8191ffbc: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76c70)
Location: drivers/vfio/vfio.c:1649
Inline: False
```
**Symbols:**

```
ffffffff81a76c70-ffffffff81a76dea: vfio_device_fops_unl_ioctl (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aadc64)
Location: drivers/vfio/vfio.c:1667
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_fops_compat_ioctl
```
**Symbols:**

```
c000000000aadbe0-c000000000aadc48: vfio_device_fops_unl_ioctl (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a1c5)
Location: drivers/vfio/vfio.c:1667
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_fops_compat_ioctl
```
**Symbols:**

```
ffffffff8177a190-ffffffff8177a1c0: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c4f95)
Location: drivers/vfio/vfio.c:1667
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817c4f60-ffffffff817c4f90: vfio_device_fops_unl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int vfio_device_fops_unl_ioctl(struct file *filep, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df235)
Location: drivers/vfio/vfio.c:1667
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_fops_compat_ioctl
```
**Symbols:**

```
ffffffff817df200-ffffffff817df230: vfio_device_fops_unl_ioctl (STB_LOCAL)
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
