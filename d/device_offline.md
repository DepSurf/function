# Function: <code>device_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81549100)
Location: drivers/base/core.c:1518
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff81549100-ffffffff815491a6: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159ad30)
Location: drivers/base/core.c:1518
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff8159ad30-ffffffff8159addc: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c9290)
Location: drivers/base/core.c:2109
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff815c9290-ffffffff815c933c: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815ddfa0)
Location: drivers/base/core.c:2107
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff815ddfa0-ffffffff815de053: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644fa0)
Location: drivers/base/core.c:2242
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff81644fa0-ffffffff81645056: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816803e0)
Location: drivers/base/core.c:2289
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff816803e0-ffffffff81680497: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169fe70)
Location: drivers/base/core.c:2364
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff8169fe70-ffffffff8169ff27: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d85e0)
Location: drivers/base/core.c:2618
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff816d85e0-ffffffff816d8693: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fc6e0)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff816fc6e0-ffffffff816fc793: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b6000)
Location: drivers/base/core.c:3156
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:offline_and_remove_memory
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817b6000-ffffffff817b6110: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cb470)
Location: drivers/base/core.c:3568
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817cb470-ffffffff817cb580: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aede0)
Location: drivers/base/core.c:3795
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817aede0-ffffffff817aeef0: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81837ff0)
Location: drivers/base/core.c:3860
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81837ff0-ffffffff81838100: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8197a330)
Location: drivers/base/core.c:3894
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff8197a330-ffffffff8197a45a: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae7170)
Location: drivers/base/core.c:4113
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81ae7170-ffffffff81ae729a: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b355a0)
Location: drivers/base/core.c:4122
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81b355a0-ffffffff81b356ca: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8cfc0)
Location: drivers/base/core.c:4135
Inline: True
Direct callers:
  - kernel/cpu.c:remove_cpu
  - mm/memory_hotplug.c:try_offline_memory_block
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/core.c:online_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81b8cfc0-ffffffff81b8d0ea: device_offline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e7070)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffff8000108e7070-ffff8000108e7140: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5658)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - drivers/base/core.c:online_store
```
**Symbols:**

```
c09d5658-c09d571c: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097d1c0)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - drivers/base/core.c:online_store
```
**Symbols:**

```
c00000000097d1c0-c00000000097d2f8: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057b8ac)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffe00057b8ac-ffffffe00057b95a: device_offline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1ed0)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff816c1ed0-ffffffff816c1f83: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d180)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff8169d180-ffffffff8169d233: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f03a0)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff816f03a0-ffffffff816f0453: device_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_offline(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170abe0)
Location: drivers/base/core.c:2655
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffff8170abe0-ffffffff8170ac93: device_offline (STB_GLOBAL)
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
