# Function: <code>pm_runtime_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557b40)
Location: drivers/base/power/runtime.c:1132
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81557b40-ffffffff81557bfe: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9c10)
Location: drivers/base/power/runtime.c:1136
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff815a9c10-ffffffff815a9cc0: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d7fe0)
Location: drivers/base/power/runtime.c:1224
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff815d7fe0-ffffffff815d8090: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ecf20)
Location: drivers/base/power/runtime.c:1224
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff815ecf20-ffffffff815ecfc4: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816542d0)
Location: drivers/base/power/runtime.c:1209
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff816542d0-ffffffff81654374: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168f920)
Location: drivers/base/power/runtime.c:1209
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff8168f920-ffffffff8168f9d0: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816afcb0)
Location: drivers/base/power/runtime.c:1216
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff816afcb0-ffffffff816afd60: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9ba0)
Location: drivers/base/power/runtime.c:1292
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff816e9ba0-ffffffff816e9c31: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170dc00)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff8170dc00-ffffffff8170dc91: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c8ec0)
Location: drivers/base/power/runtime.c:1315
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff817c8ec0-ffffffff817c8f51: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817ddc90)
Location: drivers/base/power/runtime.c:1347
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff817ddc90-ffffffff817ddd21: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c2010)
Location: drivers/base/power/runtime.c:1347
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff817c2010-ffffffff817c20a1: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184b970)
Location: drivers/base/power/runtime.c:1366
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff8184b970-ffffffff8184ba01: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819913d0)
Location: drivers/base/power/runtime.c:1395
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff819913d0-ffffffff81991462: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01770)
Location: drivers/base/power/runtime.c:1408
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff81b01770-ffffffff81b01802: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4f8a0)
Location: drivers/base/power/runtime.c:1408
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff81b4f8a0-ffffffff81b4f932: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7e20)
Location: drivers/base/power/runtime.c:1409
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff81ba7e20-ffffffff81ba7eb2: pm_runtime_barrier (STB_GLOBAL)
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
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd2f8)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffff8000108fd2f8-ffff8000108fd42c: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e83e8)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports
```
**Symbols:**

```
c09e83e8-c09e84b8: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999c00)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports
```
**Symbols:**

```
c000000000999c00-c000000000999d40: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c0e0)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports
```
**Symbols:**

```
ffffffe00058c0e0-ffffffe00058c1ac: pm_runtime_barrier (STB_GLOBAL)
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
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3350)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff816d3350-ffffffff816d33e1: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae630)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff816ae630-ffffffff816ae6bb: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817018c0)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff817018c0-ffffffff81701951: pm_runtime_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c240)
Location: drivers/base/power/runtime.c:1294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/base/core.c:device_shutdown
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
```
**Symbols:**

```
ffffffff8171c240-ffffffff8171c2c8: pm_runtime_barrier (STB_GLOBAL)
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
