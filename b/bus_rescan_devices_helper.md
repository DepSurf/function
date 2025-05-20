# Function: <code>bus_rescan_devices_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a3c0)
Location: drivers/base/bus.c:773
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff8154a3c0-ffffffff8154a41a: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c000)
Location: drivers/base/bus.c:772
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff8159c000-ffffffff8159c05a: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca560)
Location: drivers/base/bus.c:772
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff815ca560-ffffffff815ca5ba: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df220)
Location: drivers/base/bus.c:734
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff815df220-ffffffff815df27b: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646250)
Location: drivers/base/bus.c:734
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff81646250-ffffffff816462ab: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816816c0)
Location: drivers/base/bus.c:732
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff816816c0-ffffffff81681743: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a1160)
Location: drivers/base/bus.c:737
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:store_drivers_probe
```
**Symbols:**

```
ffffffff816a1160-ffffffff816a11e3: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d9fa0)
Location: drivers/base/bus.c:709
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff816d9fa0-ffffffff816da01c: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fdf50)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff816fdf50-ffffffff816fdfcc: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7afd)
Location: drivers/base/bus.c:686
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
Direct callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff817b7380-ffffffff817b73fb: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc81d)
Location: drivers/base/bus.c:686
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
Direct callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff817cc0b0-ffffffff817cc12b: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b018d)
Location: drivers/base/bus.c:686
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
Direct callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff817afa20-ffffffff817afa98: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/bus.c (0)
Location: drivers/base/bus.c:682
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff81838cf0-ffffffff81838d9b: bus_rescan_devices_helper (STB_LOCAL)
ffffffff81d02cfe-ffffffff81d02d2e: bus_rescan_devices_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/bus.c (0)
Location: drivers/base/bus.c:684
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff8197b230-ffffffff8197b2dd: bus_rescan_devices_helper (STB_LOCAL)
ffffffff81ecb445-ffffffff81ecb46f: bus_rescan_devices_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/bus.c (0)
Location: drivers/base/bus.c:684
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff81ae8280-ffffffff81ae832d: bus_rescan_devices_helper (STB_LOCAL)
ffffffff820983b1-ffffffff820983db: bus_rescan_devices_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/bus.c (0)
Location: drivers/base/bus.c:749
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff81b35e10-ffffffff81b35ecf: bus_rescan_devices_helper (STB_LOCAL)
ffffffff821193dd-ffffffff8211940d: bus_rescan_devices_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/bus.c (0)
Location: drivers/base/bus.c:749
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff81b8d830-ffffffff81b8d8ef: bus_rescan_devices_helper (STB_LOCAL)
ffffffff821f73a0-ffffffff821f73d0: bus_rescan_devices_helper.cold (STB_LOCAL)
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
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8c50)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffff8000108e8c50-ffff8000108e8ce0: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6fac)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
c09d6fac-c09d703c: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097f5b0)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
c00000000097f5b0-c00000000097f6bc: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057ce4a)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffe00057ce4a-ffffffe00057ceca: bus_rescan_devices_helper (STB_LOCAL)
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
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3740)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff816c3740-ffffffff816c37bc: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e9f0)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff8169e9f0-ffffffff8169ea6c: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1c10)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff816f1c10-ffffffff816f1c8c: bus_rescan_devices_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_rescan_devices_helper(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c450)
Location: drivers/base/bus.c:685
Inline: False
Direct callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:drivers_probe_store
```
**Symbols:**

```
ffffffff8170c450-ffffffff8170c4cc: bus_rescan_devices_helper (STB_LOCAL)
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
