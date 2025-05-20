# Function: <code>__driver_probe_device</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:733
Inline: False
Direct callers:
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8183b190-ffffffff8183b31a: __driver_probe_device (STB_LOCAL)
ffffffff81d02f3f-ffffffff81d02f53: __driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:743
Inline: False
Direct callers:
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8197d700-ffffffff8197d8a2: __driver_probe_device (STB_LOCAL)
ffffffff81ecb636-ffffffff81ecb64b: __driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:757
Inline: False
Direct callers:
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81aeabb0-ffffffff81aead41: __driver_probe_device (STB_LOCAL)
ffffffff820984a3-ffffffff820984b8: __driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:779
Inline: False
Direct callers:
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81b38ed0-ffffffff81b3904e: __driver_probe_device (STB_LOCAL)
ffffffff821194d5-ffffffff821194ea: __driver_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __driver_probe_device(struct device_driver *drv, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:779
Inline: False
Direct callers:
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81b90990-ffffffff81b90b0e: __driver_probe_device (STB_LOCAL)
ffffffff821f7498-ffffffff821f74ad: __driver_probe_device.cold (STB_LOCAL)
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
