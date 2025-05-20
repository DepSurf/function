# Function: <code>lineinfo_watch_poll</code>

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
__poll_t lineinfo_watch_poll(struct file *filep, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f200)
Location: drivers/gpio/gpiolib.c:1403
Inline: False
```
**Symbols:**

```
ffffffff8160f200-ffffffff8160f260: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b630)
Location: drivers/gpio/gpiolib-cdev.c:2178
Inline: False
```
**Symbols:**

```
ffffffff8163b630-ffffffff8163b690: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f4b0)
Location: drivers/gpio/gpiolib-cdev.c:2179
Inline: False
```
**Symbols:**

```
ffffffff8161f4b0-ffffffff8161f50d: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ea40)
Location: drivers/gpio/gpiolib-cdev.c:2179
Inline: False
```
**Symbols:**

```
ffffffff8168ea40-ffffffff8168ea9d: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad450)
Location: drivers/gpio/gpiolib-cdev.c:2374
Inline: False
```
**Symbols:**

```
ffffffff817ad450-ffffffff817ad4be: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c69c0)
Location: drivers/gpio/gpiolib-cdev.c:2546
Inline: False
```
**Symbols:**

```
ffffffff818c69c0-ffffffff818c6a78: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819097e0)
Location: drivers/gpio/gpiolib-cdev.c:2543
Inline: False
```
**Symbols:**

```
ffffffff819097e0-ffffffff81909898: lineinfo_watch_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t lineinfo_watch_poll(struct file *file, struct poll_table_struct *pollt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81952180)
Location: drivers/gpio/gpiolib-cdev.c:2591
Inline: False
```
**Symbols:**

```
ffffffff81952180-ffffffff8195223f: lineinfo_watch_poll (STB_LOCAL)
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
