# Function: <code>xen_mce_chrdev_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff814d5610)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff814d5610-ffffffff814d56fd: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff815263e0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff815263e0-ffffffff815264cd: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff81552900)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81552900-ffffffff815529ed: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff815670d0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff815670d0-ffffffff8156721f: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff815cb320)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff815cb320-ffffffff815cb46f: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81603aa0-ffffffff81603bcd: xen_mce_chrdev_read (STB_LOCAL)
ffffffff8160403b-ffffffff81604047: xen_mce_chrdev_read.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff8161eb40-ffffffff8161ec6d: xen_mce_chrdev_read (STB_LOCAL)
ffffffff8161f0db-ffffffff8161f0e7: xen_mce_chrdev_read.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81652140-ffffffff81652270: xen_mce_chrdev_read (STB_LOCAL)
ffffffff816526cd-ffffffff816526d9: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff816746e0-ffffffff81674810: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81674c6d-ffffffff81674c79: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81725060-ffffffff817251d1: xen_mce_chrdev_read (STB_LOCAL)
ffffffff8172573e-ffffffff8172574a: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81742020-ffffffff81742191: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81c05b1d-ffffffff81c05b29: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81725a10-ffffffff81725b83: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81bf77c8-ffffffff81bf77d4: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff817a49d0-ffffffff817a4b69: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81cf6891-ffffffff81cf689d: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff818de790-ffffffff818de8f9: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81ebe8f0-ffffffff81ebe8fc: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff81a31ce0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81a31ce0-ffffffff81a31e55: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff81a7b4e0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81a7b4e0-ffffffff81a7b655: xen_mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mcelog.c (ffffffff81acd990)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81acd990-ffffffff81acdb05: xen_mce_chrdev_read (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff8163a3d0-ffffffff8163a500: xen_mce_chrdev_read (STB_LOCAL)
ffffffff8163a95d-ffffffff8163a969: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81668520-ffffffff81668650: xen_mce_chrdev_read (STB_LOCAL)
ffffffff81668aad-ffffffff81668ab9: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t xen_mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/mcelog.c (0)
Location: drivers/xen/mcelog.c:106
Inline: False
```
**Symbols:**

```
ffffffff81682bb0-ffffffff81682ce0: xen_mce_chrdev_read (STB_LOCAL)
ffffffff8168306f-ffffffff8168307b: xen_mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
