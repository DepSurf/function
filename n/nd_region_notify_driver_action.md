# Function: <code>nd_region_notify_driver_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nd_region_notify_driver_action(struct nvdimm_bus *nvdimm_bus, struct device *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159a160)
Location: drivers/nvdimm/region_devs.c:388
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
  - drivers/nvdimm/region_devs.c:nd_region_disable
```
**Symbols:**

```
ffffffff8159a160-ffffffff8159a384: nd_region_notify_driver_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f0020)
Location: drivers/nvdimm/region_devs.c:500
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff815f0020-ffffffff815f02e6: nd_region_notify_driver_action.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161dba0)
Location: drivers/nvdimm/region_devs.c:534
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff8161dba0-ffffffff8161df02: nd_region_notify_driver_action.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81632030)
Location: drivers/nvdimm/region_devs.c:639
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff81632030-ffffffff816323ba: nd_region_notify_driver_action.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8169a990)
Location: drivers/nvdimm/region_devs.c:658
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff8169a990-ffffffff8169ad1e: nd_region_notify_driver_action.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6d60)
Location: drivers/nvdimm/region_devs.c:697
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff816d6d60-ffffffff816d70f3: nd_region_notify_driver_action.constprop.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f8bb0)
Location: drivers/nvdimm/region_devs.c:725
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff816f8bb0-ffffffff816f8f60: nd_region_notify_driver_action.constprop.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:723
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_disable
  - drivers/nvdimm/region_devs.c:nd_region_probe_success
```
**Symbols:**

```
ffffffff817322a0-ffffffff81732626: nd_region_notify_driver_action.constprop.0 (STB_LOCAL)
ffffffff81732aee-ffffffff81732b20: nd_region_notify_driver_action.constprop.0.cold (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
