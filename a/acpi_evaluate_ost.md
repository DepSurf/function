# Function: <code>acpi_evaluate_ost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147aab1)
Location: drivers/acpi/utils.c:447
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff8147aab1-ffffffff8147ab4c: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c9062)
Location: drivers/acpi/utils.c:444
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff814c9062-ffffffff814c90fd: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eafa6)
Location: drivers/acpi/utils.c:444
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff814eafa6-ffffffff814eb041: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f6fa0)
Location: drivers/acpi/utils.c:444
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff814f6fa0-ffffffff814f704c: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81537fc0)
Location: drivers/acpi/utils.c:445
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff81537fc0-ffffffff8153806c: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156dc40)
Location: drivers/acpi/utils.c:445
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff8156dc40-ffffffff8156dcec: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585800)
Location: drivers/acpi/utils.c:445
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff81585800-ffffffff815858ac: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6460)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff815b6460-ffffffff815b6511: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7690)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff815d7690-ffffffff815d7741: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816813d0)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff816813d0-ffffffff81681470: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8169fd20)
Location: drivers/acpi/utils.c:428
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff8169fd20-ffffffff8169fdc0: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682ae0)
Location: drivers/acpi/utils.c:408
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff81682ae0-ffffffff81682b80: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7c30)
Location: drivers/acpi/utils.c:422
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff816f7c30-ffffffff816f7cd0: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81824bb0)
Location: drivers/acpi/utils.c:422
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81824bb0-ffffffff81824c75: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81955cf0)
Location: drivers/acpi/utils.c:460
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81955cf0-ffffffff81955db5: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c0f0)
Location: drivers/acpi/utils.c:460
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff8199c0f0-ffffffff8199c1b5: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4640)
Location: drivers/acpi/utils.c:532
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff819e4640-ffffffff819e4705: acpi_evaluate_ost (STB_GLOBAL)
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
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010764dc0)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffff800010764dc0-ffff800010764e98: acpi_evaluate_ost (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cac60)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff815cac60-ffffffff815cad11: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b3cb0)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff815b3cb0-ffffffff815b3d61: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb970)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff815cb970-ffffffff815cba21: acpi_evaluate_ost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_evaluate_ost(acpi_handle handle, u32 source_event, u32 status_code, struct acpi_buffer *status_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5810)
Location: drivers/acpi/utils.c:432
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
```
**Symbols:**

```
ffffffff815e5810-ffffffff815e58c1: acpi_evaluate_ost (STB_GLOBAL)
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
