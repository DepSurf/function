# Function: <code>rproc_cdev_release</code>

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
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff819cd220)
Location: drivers/remoteproc/remoteproc_cdev.c:79
Inline: False
```
**Symbols:**

```
ffffffff819cd220-ffffffff819cd252: rproc_cdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff819b2440)
Location: drivers/remoteproc/remoteproc_cdev.c:86
Inline: False
```
**Symbols:**

```
ffffffff819b2440-ffffffff819b248a: rproc_cdev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:86
Inline: False
```
**Symbols:**

```
ffffffff81a60e10-ffffffff81a60e80: rproc_cdev_release (STB_LOCAL)
ffffffff81d32e47-ffffffff81d32e5c: rproc_cdev_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:75
Inline: False
```
**Symbols:**

```
ffffffff81bd13b0-ffffffff81bd1417: rproc_cdev_release (STB_LOCAL)
ffffffff81eff2a0-ffffffff81eff2b5: rproc_cdev_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:75
Inline: False
```
**Symbols:**

```
ffffffff81d7cd50-ffffffff81d7cdb7: rproc_cdev_release (STB_LOCAL)
ffffffff820aa3bc-ffffffff820aa3d1: rproc_cdev_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:75
Inline: False
```
**Symbols:**

```
ffffffff81deaf20-ffffffff81deaf87: rproc_cdev_release (STB_LOCAL)
ffffffff8212b8bb-ffffffff8212b8d0: rproc_cdev_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rproc_cdev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:75
Inline: False
```
**Symbols:**

```
ffffffff81ea1190-ffffffff81ea11f7: rproc_cdev_release (STB_LOCAL)
ffffffff8220d4e2-ffffffff8220d4f7: rproc_cdev_release.cold (STB_LOCAL)
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
