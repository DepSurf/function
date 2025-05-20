# Function: <code>acpi_scan_lock_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147f49d)
Location: drivers/acpi/scan.c:67
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_freeze_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8147f49d-ffffffff8147f4b4: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cdd26)
Location: drivers/acpi/scan.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_freeze_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814cdd26-ffffffff814cdd3d: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814efc8b)
Location: drivers/acpi/scan.c:69
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_freeze_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814efc8b-ffffffff814efca2: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ffa8c)
Location: drivers/acpi/scan.c:63
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_freeze_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814fcde0-ffffffff814fcdf7: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81541bcc)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8153eb20-ffffffff8153eb37: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81577aa7)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff81574a60-ffffffff81574a77: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158f6e7)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8158c680-ffffffff8158c697: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815c0349)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815bd460-ffffffff815bd477: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815e1609)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815de720-ffffffff815de737: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c2fb)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff816890d0-ffffffff816890e7: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816aa37b)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff816a6c60-ffffffff816a6c77: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168cbfb)
Location: drivers/acpi/scan.c:62
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff816898f0-ffffffff81689907: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81702436)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff816fedd0-ffffffff816fede7: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81830175)
Location: drivers/acpi/scan.c:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff8182c780-ffffffff8182c79d: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81963385)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff8195f3f0-ffffffff8195f40d: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a9835)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff819a57f0-ffffffff819a580d: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f1eb5)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff819ee170-ffffffff819ee18d: acpi_scan_lock_release (STB_GLOBAL)
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
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076df1c)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffff80001076ab88-ffff80001076abac: acpi_scan_lock_release (STB_GLOBAL)
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
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d38d9)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815d0c00-ffffffff815d0c17: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bd499)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815ba7c0-ffffffff815ba7d7: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d58e9)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815d2a00-ffffffff815d2a17: acpi_scan_lock_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_release();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ef7a9)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_s2idle_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815ec8c0-ffffffff815ec8d7: acpi_scan_lock_release (STB_GLOBAL)
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
