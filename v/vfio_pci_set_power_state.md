# Function: <code>vfio_pci_set_power_state</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7390)
Location: drivers/vfio/pci/vfio_pci.c:230
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817d7390-ffffffff817d745c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a4c80)
Location: drivers/vfio/pci/vfio_pci.c:239
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818a4c80-ffffffff818a4d4c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b3d50)
Location: drivers/vfio/pci/vfio_pci.c:281
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818b3d50-ffffffff818b3e1c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896f00)
Location: drivers/vfio/pci/vfio_pci.c:281
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81896f00-ffffffff81896fcd: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_core_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:210
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
**Symbols:**

```
ffffffff81d120d1-ffffffff81d120e6: vfio_pci_set_power_state.cold (STB_LOCAL)
ffffffff8192af60-ffffffff8192b04c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_core_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_hot_reset
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff81edce09-ffffffff81edce1e: vfio_pci_set_power_state.cold (STB_LOCAL)
ffffffff81a80300-ffffffff81a803f7: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6680)
Location: drivers/vfio/pci/vfio_pci.c:230
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
c000000000ab6680-c000000000ab6848: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781440)
Location: drivers/vfio/pci/vfio_pci.c:230
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81781440-ffffffff8178150c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc210)
Location: drivers/vfio/pci/vfio_pci.c:230
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817cc210-ffffffff817cc2dc: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_set_power_state(struct vfio_pci_device *vdev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e64b0)
Location: drivers/vfio/pci/vfio_pci.c:230
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817e64b0-ffffffff817e657c: vfio_pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
