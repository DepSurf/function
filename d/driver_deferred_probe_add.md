# Function: <code>driver_deferred_probe_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154bc98)
Location: drivers/base/dd.c:112
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159cd90)
Location: drivers/base/dd.c:119
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8159cd90-ffffffff8159ce29: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cb2f0)
Location: drivers/base/dd.c:118
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815cb2f0-ffffffff815cb389: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815dfec0)
Location: drivers/base/dd.c:119
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815dfec0-ffffffff815dff59: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81646ef0)
Location: drivers/base/dd.c:144
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81646ef0-ffffffff81646f89: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81682410)
Location: drivers/base/dd.c:141
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81682410-ffffffff816824a9: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a1eb0)
Location: drivers/base/dd.c:119
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816a1eb0-ffffffff816a1f49: driver_deferred_probe_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816db2d0)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816db2d0-ffffffff816db369: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ff2a0)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816ff2a0-ffffffff816ff339: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b9100)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817b9100-ffffffff817b918f: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cde90)
Location: drivers/base/dd.c:127
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817cde90-ffffffff817cdf1f: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff817b27a0)
Location: drivers/base/dd.c:131
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817b14f0-ffffffff817b157f: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff817b1890-ffffffff817b18aa: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8183bb22)
Location: drivers/base/dd.c:131
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8183a6b0-ffffffff8183a73c: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff8183ab40-ffffffff8183ab5a: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8197e1a7)
Location: drivers/base/dd.c:132
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8197cf00-ffffffff8197cf9a: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff8197d0e0-ffffffff8197d106: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff81aeafff)
Location: drivers/base/dd.c:132
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81aea1a0-ffffffff81aea23a: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff81aea480-ffffffff81aea4a6: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff81b392ff)
Location: drivers/base/dd.c:132
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81b38530-ffffffff81b385ca: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff81b38810-ffffffff81b38836: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff81b90dbf)
Location: drivers/base/dd.c:132
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81b8ffd0-ffffffff81b9006a: driver_deferred_probe_add.part.0 (STB_LOCAL)
ffffffff81b902d0-ffffffff81b902f6: driver_deferred_probe_add (STB_GLOBAL)
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
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108ea380)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffff8000108ea380-ffff8000108ea424: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8448)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c09d8448-c09d84e8: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000981420)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c000000000981420-c000000000981518: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057e1ee)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffe00057e1ee-ffffffe00057e2a0: driver_deferred_probe_add (STB_GLOBAL)
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
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c4a90)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816c4a90-ffffffff816c4b29: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169fd10)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8169fd10-ffffffff8169fda9: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f2f60)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816f2f60-ffffffff816f2ff9: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void driver_deferred_probe_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d790)
Location: drivers/base/dd.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8170d790-ffffffff8170d829: driver_deferred_probe_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
