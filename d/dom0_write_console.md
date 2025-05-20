# Function: <code>dom0_write_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff814fe8e0)
Location: drivers/tty/hvc/hvc_xen.c:182
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff814fe8e0-ffffffff814fe903: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f469)
Location: drivers/tty/hvc/hvc_xen.c:183
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8154f430-ffffffff8154f453: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bce9)
Location: drivers/tty/hvc/hvc_xen.c:183
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8157bcb0-ffffffff8157bcd3: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8158ff59)
Location: drivers/tty/hvc/hvc_xen.c:183
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8158ff20-ffffffff8158ff43: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4a59)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff815f4a20-ffffffff815f4a43: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162dbc5)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8162db90-ffffffff8162dbb5: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164be15)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8164bde0-ffffffff8164be05: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680975)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81680940-ffffffff81680967: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3025)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816a2ff0-ffffffff816a3017: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755805)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff817557d0-ffffffff817557f7: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770a79)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81770a40-ffffffff81770a67: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754529)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff817544f0-ffffffff81754517: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7be9)
Location: drivers/tty/hvc/hvc_xen.c:205
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff817d7bb0-ffffffff817d7bd7: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81915e09)
Location: drivers/tty/hvc/hvc_xen.c:205
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81915dc0-ffffffff81915df7: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a711f9)
Location: drivers/tty/hvc/hvc_xen.c:210
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81a711a0-ffffffff81a711d7: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abb9e9)
Location: drivers/tty/hvc/hvc_xen.c:221
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81abb990-ffffffff81abb9c5: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t dom0_write_console(uint32_t vtermno, const u8 *str, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0e749)
Location: drivers/tty/hvc/hvc_xen.c:222
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81b0e6f0-ffffffff81b0e72c: dom0_write_console (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffff80001087ba64)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffff80001087ba08-ffff80001087ba48: dom0_write_console (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668a85)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81668a50-ffffffff81668a77: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81696e65)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81696e30-ffffffff81696e57: dom0_write_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dom0_write_console(uint32_t vtermno, const char *str, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1415)
Location: drivers/tty/hvc/hvc_xen.c:170
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xenboot_earlycon_write
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816b13e0-ffffffff816b1407: dom0_write_console (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char *str</code> ➡️ <code>const u8 *str</code>
</li>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>size_t len</code>
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
