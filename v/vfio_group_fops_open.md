# Function: <code>vfio_group_fops_open</code>

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
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d13f0)
Location: drivers/vfio/vfio.c:1589
Inline: False
```
**Symbols:**

```
ffffffff817d13f0-ffffffff817d150d: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189d540)
Location: drivers/vfio/vfio.c:1584
Inline: False
```
**Symbols:**

```
ffffffff8189d540-ffffffff8189d6d4: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ac170)
Location: drivers/vfio/vfio.c:1585
Inline: False
```
**Symbols:**

```
ffffffff818ac170-ffffffff818ac304: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188f2a0)
Location: drivers/vfio/vfio.c:1484
Inline: False
```
**Symbols:**

```
ffffffff8188f2a0-ffffffff8188f430: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1586
Inline: False
```
**Symbols:**

```
ffffffff81922870-ffffffff81922a17: vfio_group_fops_open (STB_LOCAL)
ffffffff81d117d9-ffffffff81d117ee: vfio_group_fops_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a786a0)
Location: drivers/vfio/vfio.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81a786a0-ffffffff81a787db: vfio_group_fops_open (STB_LOCAL)
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
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaeae0)
Location: drivers/vfio/vfio.c:1589
Inline: False
```
**Symbols:**

```
c000000000aaeae0-c000000000aaec90: vfio_group_fops_open (STB_LOCAL)
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
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b4a0)
Location: drivers/vfio/vfio.c:1589
Inline: False
```
**Symbols:**

```
ffffffff8177b4a0-ffffffff8177b5bd: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6270)
Location: drivers/vfio/vfio.c:1589
Inline: False
```
**Symbols:**

```
ffffffff817c6270-ffffffff817c638d: vfio_group_fops_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_group_fops_open(struct inode *inode, struct file *filep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0510)
Location: drivers/vfio/vfio.c:1589
Inline: False
```
**Symbols:**

```
ffffffff817e0510-ffffffff817e062d: vfio_group_fops_open (STB_LOCAL)
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
