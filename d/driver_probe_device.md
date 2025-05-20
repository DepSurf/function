# Function: <code>driver_probe_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154baf0)
Location: drivers/base/dd.c:415
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8154baf0-ffffffff8154bf85: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d890)
Location: drivers/base/dd.c:485
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8159d890-ffffffff8159dcb8: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cbc20)
Location: drivers/base/dd.c:507
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff815cbc20-ffffffff815cc075: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e07f0)
Location: drivers/base/dd.c:514
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff815e07f0-ffffffff815e0c32: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816478b0)
Location: drivers/base/dd.c:551
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816478b0-ffffffff81647d38: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:565
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816837c0-ffffffff81683803: driver_probe_device.cold.14 (STB_LOCAL)
ffffffff81682da0-ffffffff816831f1: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:649
Inline: False
Direct callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816a34b4-ffffffff816a34dc: driver_probe_device.cold.15 (STB_LOCAL)
ffffffff816a2e00-ffffffff816a2efc: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:691
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816dc3a0-ffffffff816dc3ef: driver_probe_device.cold (STB_LOCAL)
ffffffff816dbbc0-ffffffff816dbc95: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8170044d-ffffffff81700475: driver_probe_device.cold (STB_LOCAL)
ffffffff816ffbd0-ffffffff816ffccf: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b9a90)
Location: drivers/base/dd.c:679
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817b9a90-ffffffff817b9be3: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817ce570)
Location: drivers/base/dd.c:725
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817ce570-ffffffff817ce6c3: driver_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b1f70)
Location: drivers/base/dd.c:744
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff817b1f70-ffffffff817b20ca: driver_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:778
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8183b320-ffffffff8183b3d3: driver_probe_device (STB_LOCAL)
ffffffff81d02f53-ffffffff81d02f7b: driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:788
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8197d8b0-ffffffff8197d97a: driver_probe_device (STB_LOCAL)
ffffffff81ecb64b-ffffffff81ecb675: driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:802
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81aead60-ffffffff81aeae2a: driver_probe_device (STB_LOCAL)
ffffffff820984b8-ffffffff820984e2: driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:824
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81b39060-ffffffff81b3912a: driver_probe_device (STB_LOCAL)
ffffffff821194ea-ffffffff82119514: driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:824
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff81b90b20-ffffffff81b90bea: driver_probe_device (STB_LOCAL)
ffffffff821f74ad-ffffffff821f74d7: driver_probe_device.cold (STB_LOCAL)
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
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eadf8)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffff8000108eadf8-ffff8000108eaf2c: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8ef8)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
c09d8ef8-c09d905c: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009821c0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
c0000000009821c0-c000000000982380: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057eb2c)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffe00057eb2c-ffffffe00057ec4e: driver_probe_device (STB_GLOBAL)
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
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816c5c3d-ffffffff816c5c65: driver_probe_device.cold (STB_LOCAL)
ffffffff816c53c0-ffffffff816c54bf: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816a0ebd-ffffffff816a0ee5: driver_probe_device.cold (STB_LOCAL)
ffffffff816a0640-ffffffff816a073f: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff816f410d-ffffffff816f4135: driver_probe_device.cold (STB_LOCAL)
ffffffff816f3890-ffffffff816f398f: driver_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:706
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
**Symbols:**

```
ffffffff8170e939-ffffffff8170e961: driver_probe_device.cold (STB_LOCAL)
ffffffff8170e0c0-ffffffff8170e1bf: driver_probe_device (STB_GLOBAL)
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
