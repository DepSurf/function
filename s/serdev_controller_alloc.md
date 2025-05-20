# Function: <code>serdev_controller_alloc</code>

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
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81609ae0)
Location: drivers/tty/serdev/core.c:345
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81609ae0-ffffffff81609be4: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81643310)
Location: drivers/tty/serdev/core.c:388
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81643310-ffffffff8164340c: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81661630)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81661630-ffffffff81661742: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff8169744f-ffffffff81697484: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff81697060-ffffffff81697153: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816ba002-ffffffff816ba021: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff816b9c00-ffffffff816b9d02: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:478
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff8176e455-ffffffff8176e474: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff8176e120-ffffffff8176e222: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:478
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81c08453-ffffffff81c08472: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff81788af0-ffffffff81788bf2: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:478
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81bfa018-ffffffff81bfa037: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff8176c2e0-ffffffff8176c3e2: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:476
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81cfa8c8-ffffffff81cfa8e7: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff817f1a30-ffffffff817f1b2f: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:476
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81ec2b4a-ffffffff81ec2b66: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff81932170-ffffffff8193227c: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a90c10)
Location: drivers/tty/serdev/core.c:476
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81a90c10-ffffffff81a90d38: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adc420)
Location: drivers/tty/serdev/core.c:487
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81adc420-ffffffff81adc548: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *host, struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2f700)
Location: drivers/tty/serdev/core.c:478
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81b2f700-ffffffff81b2f83c: serdev_controller_alloc (STB_GLOBAL)
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
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9e48)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffff8000108a9e48-ffff8000108a9f88: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a6328)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
c09a6328-c09a6460: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c000000000941110)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
c000000000941110-c0000000009412a8: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055f02e)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffe00055f02e-ffffffe00055f154: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff8167fa62-ffffffff8167fa81: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff8167f660-ffffffff8167f762: serdev_controller_alloc (STB_GLOBAL)
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
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816ade42-ffffffff816ade61: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff816ada40-ffffffff816adb42: serdev_controller_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct serdev_controller *serdev_controller_alloc(struct device *parent, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:477
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816c82a2-ffffffff816c82c1: serdev_controller_alloc.cold (STB_LOCAL)
ffffffff816c7ea0-ffffffff816c7fa2: serdev_controller_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *host</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, size</code> ➡️ <code>host, parent, size</code>
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
