# Function: <code>device_driver_attach</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dbe80)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff816dbe80-ffffffff816dbee2: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ffeb0)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff816ffeb0-ffffffff816fff12: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b9e20)
Location: drivers/base/dd.c:961
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff817b9e20-ffffffff817b9ed0: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cec70)
Location: drivers/base/dd.c:1007
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff817cec70-ffffffff817ced20: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b2690)
Location: drivers/base/dd.c:1028
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff817b2690-ffffffff817b2740: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1062
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
```
**Symbols:**

```
ffffffff81d02fa5-ffffffff81d02fce: device_driver_attach.cold (STB_LOCAL)
ffffffff8183b4d0-ffffffff8183b59a: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1081
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
```
**Symbols:**

```
ffffffff81ecb69f-ffffffff81ecb6c8: device_driver_attach.cold (STB_LOCAL)
ffffffff8197da90-ffffffff8197db59: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1100
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
```
**Symbols:**

```
ffffffff8209856d-ffffffff82098596: device_driver_attach.cold (STB_LOCAL)
ffffffff81aeb300-ffffffff81aeb3c9: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1122
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
```
**Symbols:**

```
ffffffff8211959f-ffffffff821195c8: device_driver_attach.cold (STB_LOCAL)
ffffffff81b39600-ffffffff81b396c9: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1122
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
```
**Symbols:**

```
ffffffff821f7562-ffffffff821f758b: device_driver_attach.cold (STB_LOCAL)
ffffffff81b910c0-ffffffff81b91189: device_driver_attach (STB_GLOBAL)
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
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eb198)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffff8000108eb198-ffff8000108eb214: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d92b4)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
c09d92b4-c09d9324: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009826c0)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
c0000000009826c0-c000000000982794: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057ee50)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffe00057ee50-ffffffe00057eeb6: device_driver_attach (STB_GLOBAL)
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
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c56a0)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff816c56a0-ffffffff816c5702: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a0920)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff816a0920-ffffffff816a0982: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3b70)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff816f3b70-ffffffff816f3bd2: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_driver_attach(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170e3a0)
Location: drivers/base/dd.c:987
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
```
**Symbols:**

```
ffffffff8170e3a0-ffffffff8170e402: device_driver_attach (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
