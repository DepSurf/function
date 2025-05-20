# Function: <code>xen_has_pv_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81024440)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81024440-ffffffff81024468: xen_has_pv_devices.part.0 (STB_LOCAL)
ffffffff81024470-ffffffff81024498: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff810237b0)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81023710-ffffffff81023738: xen_has_pv_devices.part.0 (STB_LOCAL)
ffffffff81023740-ffffffff81023768: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023ee0)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81023e40-ffffffff81023e68: xen_has_pv_devices.part.0 (STB_LOCAL)
ffffffff81023e70-ffffffff81023e98: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b670)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101b670-ffffffff8101b6be: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c350)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101c350-ffffffff8101c397: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101cd60)
Location: arch/x86/xen/platform-pci-unplug.c:71
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101cd60-ffffffff8101cda7: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c9e0)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101c9e0-ffffffff8101ca27: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101e500)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_nic_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101e500-ffffffff8101e547: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ee80)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_nic_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101ee80-ffffffff8101eec7: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021430)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81021430-ffffffff81021477: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021bf0)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81021bf0-ffffffff81021c37: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f80)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81023f80-ffffffff81023fc7: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81028333)
Location: arch/x86/xen/platform-pci-unplug.c:61
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81c97186-ffffffff81c9719a: xen_has_pv_devices.cold (STB_LOCAL)
ffffffff81028300-ffffffff81028363: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102c9ff)
Location: arch/x86/xen/platform-pci-unplug.c:61
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff81e46638-ffffffff81e4664c: xen_has_pv_devices.cold (STB_LOCAL)
ffffffff8102c8d0-ffffffff8102c953: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033b5f)
Location: arch/x86/xen/platform-pci-unplug.c:61
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff820518cf-ffffffff820518e3: xen_has_pv_devices.cold (STB_LOCAL)
ffffffff81033a10-ffffffff81033a93: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033aef)
Location: arch/x86/xen/platform-pci-unplug.c:61
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff820cfdbb-ffffffff820cfdcf: xen_has_pv_devices.cold (STB_LOCAL)
ffffffff810339a0-ffffffff81033a23: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff81039def)
Location: arch/x86/xen/platform-pci-unplug.c:61
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff821aa729-ffffffff821aa73d: xen_has_pv_devices.cold (STB_LOCAL)
ffffffff81039ca0-ffffffff81039d23: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: include/xen/platform_pci.h:56
Inline: True
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101efe0)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_nic_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101efe0-ffffffff8101f027: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ee40)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_nic_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101ee40-ffffffff8101ee87: xen_has_pv_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool xen_has_pv_devices();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f090)
Location: arch/x86/xen/platform-pci-unplug.c:59
Inline: True
Direct callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_disk_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_has_pv_nic_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff8101f090-ffffffff8101f0d7: xen_has_pv_devices (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
