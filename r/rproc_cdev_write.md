# Function: <code>rproc_cdev_write</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff819cd310-ffffffff819cd43b: rproc_cdev_write (STB_LOCAL)
ffffffff81c2f0ec-ffffffff81c2f109: rproc_cdev_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff819b2540-ffffffff819b26b9: rproc_cdev_write (STB_LOCAL)
ffffffff81c213b0-ffffffff81c213ce: rproc_cdev_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff81a60bd0-ffffffff81a60d49: rproc_cdev_write (STB_LOCAL)
ffffffff81d32df4-ffffffff81d32e12: rproc_cdev_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff81bd1190-ffffffff81bd12dc: rproc_cdev_write (STB_LOCAL)
ffffffff81eff24d-ffffffff81eff26b: rproc_cdev_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81d7cae0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff81d7cae0-ffffffff81d7cc41: rproc_cdev_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81deaca0)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff81deaca0-ffffffff81deae04: rproc_cdev_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t rproc_cdev_write(struct file *filp, const char *buf, size_t len, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81ea0f10)
Location: drivers/remoteproc/remoteproc_cdev.c:21
Inline: False
```
**Symbols:**

```
ffffffff81ea0f10-ffffffff81ea1074: rproc_cdev_write (STB_LOCAL)
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
