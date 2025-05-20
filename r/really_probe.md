# Function: <code>really_probe</code>

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
In drivers/base/dd.c (ffffffff8154bb37)
Location: drivers/base/dd.c:278
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d8cf)
Location: drivers/base/dd.c:328
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cbc69)
Location: drivers/base/dd.c:324
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e0839)
Location: drivers/base/dd.c:325
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816478f9)
Location: drivers/base/dd.c:362
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81682de9)
Location: drivers/base/dd.c:384
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:449
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816a2910-ffffffff816a2cbf: really_probe (STB_LOCAL)
ffffffff816a3472-ffffffff816a34b4: really_probe.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816db6c0-ffffffff816dba54: really_probe (STB_LOCAL)
ffffffff816dc325-ffffffff816dc387: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816ff690-ffffffff816ffa61: really_probe (STB_LOCAL)
ffffffff8170036e-ffffffff81700434: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:461
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff817b9360-ffffffff817b9787: really_probe (STB_LOCAL)
ffffffff817ba2d6-ffffffff817ba3a3: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:497
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff817ce110-ffffffff817ce56f: really_probe (STB_LOCAL)
ffffffff81c0e356-ffffffff81c0e42e: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:516
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff817b1ab0-ffffffff817b1f67: really_probe (STB_LOCAL)
ffffffff81c00740-ffffffff81c0082d: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:541
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
```
**Symbols:**

```
ffffffff8183ad70-ffffffff8183b18c: really_probe (STB_LOCAL)
ffffffff81d02e42-ffffffff81d02f3f: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:579
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
```
**Symbols:**

```
ffffffff8197d350-ffffffff8197d6f1: really_probe (STB_LOCAL)
ffffffff81ecb587-ffffffff81ecb636: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:584
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
```
**Symbols:**

```
ffffffff81aea760-ffffffff81aeab9f: really_probe (STB_LOCAL)
ffffffff8209848e-ffffffff820984a3: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:603
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
```
**Symbols:**

```
ffffffff81b38ab0-ffffffff81b38eba: really_probe (STB_LOCAL)
ffffffff821194c0-ffffffff821194d5: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:603
Inline: False
Direct callers:
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
```
**Symbols:**

```
ffffffff81b90570-ffffffff81b9097a: really_probe (STB_LOCAL)
ffffffff821f7483-ffffffff821f7498: really_probe.cold (STB_LOCAL)
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
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108ea7c8)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffff8000108ea7c8-ffff8000108eac0c: really_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8894)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
c09d8894-c09d8d38: really_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009819f0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
c0000000009819f0-c000000000981f70: really_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057e5d4)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffe00057e5d4-ffffffe00057e97e: really_probe (STB_LOCAL)
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
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816c4e80-ffffffff816c5251: really_probe (STB_LOCAL)
ffffffff816c5b5e-ffffffff816c5c24: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816a0100-ffffffff816a04d1: really_probe (STB_LOCAL)
ffffffff816a0dde-ffffffff816a0ea4: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816f3350-ffffffff816f3721: really_probe (STB_LOCAL)
ffffffff816f402e-ffffffff816f40f4: really_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int really_probe(struct device *dev, struct device_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:492
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8170db80-ffffffff8170df51: really_probe (STB_LOCAL)
ffffffff8170e85a-ffffffff8170e920: really_probe.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
