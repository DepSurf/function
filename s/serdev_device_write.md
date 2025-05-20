# Function: <code>serdev_device_write</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81609730)
Location: drivers/tty/serdev/core.c:158
Inline: False
```
**Symbols:**

```
ffffffff81609730-ffffffff8160984b: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81642fa0)
Location: drivers/tty/serdev/core.c:210
Inline: False
```
**Symbols:**

```
ffffffff81642fa0-ffffffff816430ae: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816611c0)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff816611c0-ffffffff816612f0: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81696c00)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff81696c00-ffffffff81696d30: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816b9790)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff816b9790-ffffffff816b98c0: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176db20)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff8176db20-ffffffff8176dc50: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788500)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff81788500-ffffffff81788630: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176be50)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff8176be50-ffffffff8176bf7e: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f1590)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff817f1590-ffffffff817f16be: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81931bc0)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff81931bc0-ffffffff81931cfa: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a90580)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff81a90580-ffffffff81a906ba: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adbd90)
Location: drivers/tty/serdev/core.c:270
Inline: False
```
**Symbols:**

```
ffffffff81adbd90-ffffffff81adbeca: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t serdev_device_write(struct serdev_device *serdev, const u8 *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2f030)
Location: drivers/tty/serdev/core.c:261
Inline: False
```
**Symbols:**

```
ffffffff81b2f030-ffffffff81b2f1a2: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a94f8)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffff8000108a94f8-ffff8000108a9628: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a5d68)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
c09a5d68-c09a5e80: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c000000000940b20)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
c000000000940b20-c000000000940cec: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055ec2c)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffe00055ec2c-ffffffe00055ed26: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8167f1f0)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff8167f1f0-ffffffff8167f320: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816ad5d0)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff816ad5d0-ffffffff816ad700: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int serdev_device_write(struct serdev_device *serdev, const unsigned char *buf, size_t count, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816c7a30)
Location: drivers/tty/serdev/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff816c7a30-ffffffff816c7b60: serdev_device_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int timeout</code> ➡️ <code>long int timeout</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *buf</code> ➡️ <code>const u8 *buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
