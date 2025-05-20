# Function: <code>serdev_tty_port_unregister</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: include/linux/serdev.h:319
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8160a4a0)
Location: drivers/tty/serdev/serdev-ttyport.c:278
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff8160a4a0-ffffffff8160a4fa: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81643de0)
Location: drivers/tty/serdev/serdev-ttyport.c:306
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81643de0-ffffffff81643e38: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816620b0)
Location: drivers/tty/serdev/serdev-ttyport.c:306
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff816620b0-ffffffff81662108: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81697c40)
Location: drivers/tty/serdev/serdev-ttyport.c:306
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81697c40-ffffffff81697c9a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba7c0)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff816ba7c0-ffffffff816ba81a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176ec30)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff8176ec30-ffffffff8176ec8a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81789530)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81789530-ffffffff8178958a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176ce10)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff8176ce10-ffffffff8176ce6a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817f2550)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff817f2550-ffffffff817f25aa: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81932dc0)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81932dc0-ffffffff81932e26: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a91a10)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81a91a10-ffffffff81a91a76: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81add280)
Location: drivers/tty/serdev/serdev-ttyport.c:316
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81add280-ffffffff81add2e6: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b30690)
Location: drivers/tty/serdev/serdev-ttyport.c:317
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81b30690-ffffffff81b306f6: serdev_tty_port_unregister (STB_GLOBAL)
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
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aaa10)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffff8000108aaa10-ffff8000108aaa78: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c09a6d54)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
c09a6d54-c09a6db8: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c0000000009421b0)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
c0000000009421b0-c000000000942250: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffe00055fa42)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffe00055fa42-ffffffe00055faa6: serdev_tty_port_unregister (STB_GLOBAL)
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
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81680220)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81680220-ffffffff8168027a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: include/linux/serdev.h:324
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ae600)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff816ae600-ffffffff816ae65a: serdev_tty_port_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c8a60)
Location: drivers/tty/serdev/serdev-ttyport.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff816c8a60-ffffffff816c8aba: serdev_tty_port_unregister (STB_GLOBAL)
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
