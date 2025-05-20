# Function: <code>linereq_ioctl_compat</code>

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
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163bcf0)
Location: drivers/gpio/gpiolib-cdev.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8163bcf0-ffffffff8163bdbb: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f450)
Location: drivers/gpio/gpiolib-cdev.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8161f450-ffffffff8161f4a2: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e970)
Location: drivers/gpio/gpiolib-cdev.c:1202
Inline: False
```
**Symbols:**

```
ffffffff8168e970-ffffffff8168ea3b: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ae310)
Location: drivers/gpio/gpiolib-cdev.c:1388
Inline: False
```
**Symbols:**

```
ffffffff817ae310-ffffffff817ae402: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7990)
Location: drivers/gpio/gpiolib-cdev.c:1470
Inline: False
```
**Symbols:**

```
ffffffff818c7990-ffffffff818c79f0: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190aa30)
Location: drivers/gpio/gpiolib-cdev.c:1469
Inline: False
```
**Symbols:**

```
ffffffff8190aa30-ffffffff8190aa90: linereq_ioctl_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int linereq_ioctl_compat(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81952760)
Location: drivers/gpio/gpiolib-cdev.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81952760-ffffffff8195277c: linereq_ioctl_compat (STB_LOCAL)
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
