# Function: <code>driver_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8154c870)
Location: drivers/base/driver.c:211
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8154c870-ffffffff8154c8b1: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8159e660)
Location: drivers/base/driver.c:211
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8159e660-ffffffff8159e6a1: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815ccc10)
Location: drivers/base/driver.c:211
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff815ccc10-ffffffff815ccc51: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815e1740)
Location: drivers/base/driver.c:211
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff815e1740-ffffffff815e1781: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816488a0)
Location: drivers/base/driver.c:211
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816488a0-ffffffff816488e1: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81683e50)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81683e50-ffffffff81683e8f: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a3b20)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816a3b20-ffffffff816a3b60: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816dca10)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816dca10-ffffffff816dca53: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81700ab0)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81700ab0-ffffffff81700af3: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817bab1f)
Location: drivers/base/driver.c:214
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff817baa00-ffffffff817baa45: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817cf76f)
Location: drivers/base/driver.c:214
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff817cf650-ffffffff817cf695: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817b317f)
Location: drivers/base/driver.c:214
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff817b3060-ffffffff817b30a5: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8183c66f)
Location: drivers/base/driver.c:214
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8183c550-ffffffff8183c595: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8197f0bc)
Location: drivers/base/driver.c:284
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8197ef70-ffffffff8197efbb: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81aec7ee)
Location: drivers/base/driver.c:290
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_register
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81aec680-ffffffff81aec6cb: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36ac0)
Location: drivers/base/bus.c:1310
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81b36ac0-ffffffff81b36b2b: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e4e0)
Location: drivers/base/bus.c:1310
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81b8e4e0-ffffffff81b8e54b: driver_find (STB_GLOBAL)
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
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffff8000108ebef8)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffff8000108ebef8-ffff8000108ebf44: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c09d9f40)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
c09d9f40-c09d9f7c: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c000000000983840)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
c000000000983840-c0000000009838a0: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffe00057f53e)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffe00057f53e-ffffffe00057f584: driver_find (STB_GLOBAL)
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
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816c62a0)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816c62a0-ffffffff816c62e3: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a1500)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816a1500-ffffffff816a1543: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816f4770)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816f4770-ffffffff816f47b3: driver_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device_driver *driver_find(const char *name, struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8170f000)
Location: drivers/base/driver.c:213
Inline: False
Direct callers:
  - drivers/base/driver.c:driver_register
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8170f000-ffffffff8170f043: driver_find (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
