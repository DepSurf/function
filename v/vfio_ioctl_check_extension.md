# Function: <code>vfio_ioctl_check_extension</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0700)
Location: drivers/vfio/vfio.c:1025
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff817d0700-ffffffff817d0808: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b0d0)
Location: drivers/vfio/vfio.c:1040
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8189b0d0-ffffffff8189b1d8: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9ce0)
Location: drivers/vfio/vfio.c:1041
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff818a9ce0-ffffffff818a9de8: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d080)
Location: drivers/vfio/vfio.c:935
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8188d080-ffffffff8188d188: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1021
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81920710-ffffffff81920832: vfio_ioctl_check_extension (STB_LOCAL)
ffffffff81d11678-ffffffff81d11693: vfio_ioctl_check_extension.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:708
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_file_enforced_coherent
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81a76540-ffffffff81a76671: vfio_ioctl_check_extension (STB_LOCAL)
ffffffff81edc3ba-ffffffff81edc3d5: vfio_ioctl_check_extension.cold (STB_LOCAL)
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
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaf0f0)
Location: drivers/vfio/vfio.c:1025
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
c000000000aaf0f0-c000000000aaf2ec: vfio_ioctl_check_extension (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a7b0)
Location: drivers/vfio/vfio.c:1025
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8177a7b0-ffffffff8177a8b8: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5580)
Location: drivers/vfio/vfio.c:1025
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff817c5580-ffffffff817c5688: vfio_ioctl_check_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df820)
Location: drivers/vfio/vfio.c:1025
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_external_check_extension
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff817df820-ffffffff817df928: vfio_ioctl_check_extension (STB_LOCAL)
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
