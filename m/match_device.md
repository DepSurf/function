# Function: <code>match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff814b8270)
Location: drivers/pnp/driver.c:43
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_device_probe
  - drivers/pnp/driver.c:pnp_bus_match
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cea05)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff814b8270-ffffffff814b82b8: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81507cd0)
Location: drivers/pnp/driver.c:43
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815202b4)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff81507cd0-ffffffff81507d18: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff8152bef0)
Location: drivers/pnp/driver.c:43
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154c764)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff8152bef0-ffffffff8152bf38: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff8153efe0)
Location: drivers/pnp/driver.c:43
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560a54)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff8153efe0-ffffffff8153f028: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff815a2090)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c4d24)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff815a2090-ffffffff815a20d8: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff815d9d00)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd394)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff815d9d00-ffffffff815d9d48: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff815f3620)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81618474)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff815f3620-ffffffff815f3668: match_device.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81625500)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c161)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff81625500-ffffffff81625549: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81646ff0)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e5f1)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff81646ff0-ffffffff81647039: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff816f5e60)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e685)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81712ea0)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173b605)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff816f4260)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171f155)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff8176e6a0)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179df75)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff818a38b0)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7b25)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff819ed2e0)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a2a0f5)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81a35a60)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a738a5)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81a80f90)
Location: drivers/pnp/driver.c:44
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5a05)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffff8000107b4248)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010839350)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffff8000107b4248-ffff8000107b42b4: match_device.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff8160d050)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81634411)
Location: drivers/xen/xenbus/xenbus_probe.c:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff8160d050-ffffffff8160d099: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff816015a0)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
**Symbols:**

```
ffffffff816015a0-ffffffff816015e9: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff8163ae30)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81662431)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff8163ae30-ffffffff8163ae79: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/driver.c (ffffffff81655180)
Location: drivers/pnp/driver.c:44
Inline: True
Direct callers:
  - drivers/pnp/driver.c:pnp_bus_match
  - drivers/pnp/driver.c:pnp_device_probe
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167ca01)
Location: drivers/xen/xenbus/xenbus_probe.c:83
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_match
```
**Symbols:**

```
ffffffff81655180-ffffffff816551c9: match_device.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
