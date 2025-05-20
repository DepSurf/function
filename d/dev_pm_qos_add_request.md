# Function: <code>dev_pm_qos_add_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81555400)
Location: drivers/base/power/qos.c:349
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff81555400-ffffffff81555452: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815a7450)
Location: drivers/base/power/qos.c:349
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff815a7450-ffffffff815a74a2: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815d5c10)
Location: drivers/base/power/qos.c:349
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff815d5c10-ffffffff815d5c62: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815ea630)
Location: drivers/base/power/qos.c:336
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff815ea630-ffffffff815ea682: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816519e0)
Location: drivers/base/power/qos.c:339
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816519e0-ffffffff81651a32: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8168d2b0)
Location: drivers/base/power/qos.c:339
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff8168d2b0-ffffffff8168d302: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ad500)
Location: drivers/base/power/qos.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816ad500-ffffffff816ad552: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816e71f0)
Location: drivers/base/power/qos.c:395
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff816e71f0-ffffffff816e7246: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8170b480)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff8170b480-ffffffff8170b4d6: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817c6791)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817c6490-ffffffff817c64e6: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817db211)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817daf10-ffffffff817daf66: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817bf6d1)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817bf350-ffffffff817bf3a6: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81849a41)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818496c0-ffffffff81849716: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8198e9a0)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8198e5b0-ffffffff8198e60e: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81afe9e0)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81afe3f0-ffffffff81afe44e: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81b4cda0)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b4c7b0-ffffffff81b4c80e: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81ba52cf)
Location: drivers/base/power/qos.c:388
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ba4c80-ffffffff81ba4cde: dev_pm_qos_add_request (STB_GLOBAL)
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
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffff8000108f9fa8)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffff8000108f9fa8-ffff8000108fa01c: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c09e5240)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
c09e5240-c09e529c: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c000000000996630)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
c000000000996630-c0000000009966b8: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffe0005897a6)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffe0005897a6-ffffffe00058980c: dev_pm_qos_add_request (STB_GLOBAL)
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
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816d0bd0)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816d0bd0-ffffffff816d0c26: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816abef0)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816abef0-ffffffff816abf46: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ff140)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816ff140-ffffffff816ff196: dev_pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_qos_add_request(struct device *dev, struct dev_pm_qos_request *req, enum dev_pm_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817195a0)
Location: drivers/base/power/qos.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/base/power/qos.c:dev_pm_qos_add_ancestor_request
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff817195a0-ffffffff817195f6: dev_pm_qos_add_request (STB_GLOBAL)
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
