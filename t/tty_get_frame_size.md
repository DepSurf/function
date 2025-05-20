# Function: <code>tty_get_frame_size</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char tty_get_frame_size(unsigned int cflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bce30)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_update_timeout
```
**Symbols:**

```
ffffffff817bce30-ffffffff817bce8d: tty_get_frame_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char tty_get_frame_size(unsigned int cflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818f90a0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_update_timeout
```
**Symbols:**

```
ffffffff818f90a0-ffffffff818f9105: tty_get_frame_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char tty_get_frame_size(unsigned int cflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a51f10)
Location: drivers/tty/tty_ioctl.c:315
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_update_timeout
```
**Symbols:**

```
ffffffff81a51f10-ffffffff81a51f82: tty_get_frame_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char tty_get_frame_size(unsigned int cflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9c220)
Location: drivers/tty/tty_ioctl.c:316
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_update_timeout
```
**Symbols:**

```
ffffffff81a9c220-ffffffff81a9c292: tty_get_frame_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char tty_get_frame_size(unsigned int cflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aeecf0)
Location: drivers/tty/tty_ioctl.c:298
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_update_timeout
```
**Symbols:**

```
ffffffff81aeecf0-ffffffff81aeed62: tty_get_frame_size (STB_GLOBAL)
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
