# Function: <code>__vfio_group_unset_container</code>

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
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0d00)
Location: drivers/vfio/vfio.c:1308
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff817d0d00-ffffffff817d0e4e: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b4b0)
Location: drivers/vfio/vfio.c:1312
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff8189b4b0-ffffffff8189b62c: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aa250)
Location: drivers/vfio/vfio.c:1313
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff818aa250-ffffffff818aa3cc: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d460)
Location: drivers/vfio/vfio.c:1212
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff8188d460-ffffffff8188d5dc: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819209c0)
Location: drivers/vfio/vfio.c:1298
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff819209c0-ffffffff81920b3c: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a770c0)
Location: drivers/vfio/vfio.c:926
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81a770c0-ffffffff81a7728c: __vfio_group_unset_container (STB_LOCAL)
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
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae750)
Location: drivers/vfio/vfio.c:1308
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
c000000000aae750-c000000000aae980: __vfio_group_unset_container (STB_LOCAL)
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
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177adb0)
Location: drivers/vfio/vfio.c:1308
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff8177adb0-ffffffff8177aefe: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5b80)
Location: drivers/vfio/vfio.c:1308
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff817c5b80-ffffffff817c5cce: __vfio_group_unset_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __vfio_group_unset_container(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817dfe20)
Location: drivers/vfio/vfio.c:1308
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
**Symbols:**

```
ffffffff817dfe20-ffffffff817dff6e: __vfio_group_unset_container (STB_LOCAL)
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
