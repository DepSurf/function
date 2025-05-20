# Function: <code>lineinfo_watch_read</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *filep, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81611ab0)
Location: drivers/gpio/gpiolib.c:1418
Inline: False
```
**Symbols:**

```
ffffffff81611ab0-ffffffff81611cb5: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163bdc0)
Location: drivers/gpio/gpiolib-cdev.c:2193
Inline: False
```
**Symbols:**

```
ffffffff8163bdc0-ffffffff8163bfcb: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161fae0)
Location: drivers/gpio/gpiolib-cdev.c:2194
Inline: False
```
**Symbols:**

```
ffffffff8161fae0-ffffffff8161fceb: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ee90)
Location: drivers/gpio/gpiolib-cdev.c:2194
Inline: False
```
**Symbols:**

```
ffffffff8168ee90-ffffffff8168f099: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aba20)
Location: drivers/gpio/gpiolib-cdev.c:2389
Inline: False
```
**Symbols:**

```
ffffffff817aba20-ffffffff817abcdf: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c66c0)
Location: drivers/gpio/gpiolib-cdev.c:2634
Inline: False
```
**Symbols:**

```
ffffffff818c66c0-ffffffff818c672d: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909760)
Location: drivers/gpio/gpiolib-cdev.c:2631
Inline: False
```
**Symbols:**

```
ffffffff81909760-ffffffff819097cd: lineinfo_watch_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t lineinfo_watch_read(struct file *file, char *buf, size_t count, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819500a0)
Location: drivers/gpio/gpiolib-cdev.c:2611
Inline: False
```
**Symbols:**

```
ffffffff819500a0-ffffffff819503d8: lineinfo_watch_read (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filep</code>
</li>
</ul>
</details>
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
