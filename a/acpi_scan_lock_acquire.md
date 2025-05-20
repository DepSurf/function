# Function: <code>acpi_scan_lock_acquire</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147f486)
Location: drivers/acpi/scan.c:61
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_freeze_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8147f486-ffffffff8147f49d: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cdd0f)
Location: drivers/acpi/scan.c:62
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_freeze_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814cdd0f-ffffffff814cdd26: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814efc74)
Location: drivers/acpi/scan.c:63
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_freeze_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814efc74-ffffffff814efc8b: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ffa74)
Location: drivers/acpi/scan.c:57
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_freeze_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff814fcdc0-ffffffff814fcdd7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81541bb4)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8153eb00-ffffffff8153eb17: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81577a8f)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff81574a40-ffffffff81574a57: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158f6cf)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff8158c660-ffffffff8158c677: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815c0331)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815bd440-ffffffff815bd457: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815e15f1)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815de700-ffffffff815de717: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c2e3)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff816890b0-ffffffff816890c7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816aa363)
Location: drivers/acpi/scan.c:58
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff816a6c40-ffffffff816a6c57: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168cbe3)
Location: drivers/acpi/scan.c:56
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff816898d0-ffffffff816898e7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81702415)
Location: drivers/acpi/scan.c:53
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff816fedb0-ffffffff816fedc7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81830155)
Location: drivers/acpi/scan.c:54
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff8182c760-ffffffff8182c77d: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81963365)
Location: drivers/acpi/scan.c:53
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff8195f3c0-ffffffff8195f3dd: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a9815)
Location: drivers/acpi/scan.c:52
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff819a57c0-ffffffff819a57dd: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f1e95)
Location: drivers/acpi/scan.c:52
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:undock_store
```
**Symbols:**

```
ffffffff819ee140-ffffffff819ee15d: acpi_scan_lock_acquire (STB_GLOBAL)
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
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076df04)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffff80001076ab60-ffff80001076ab84: acpi_scan_lock_acquire (STB_GLOBAL)
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
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d38c1)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin
```
**Symbols:**

```
ffffffff815d0be0-ffffffff815d0bf7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bd481)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
```
**Symbols:**

```
ffffffff815ba7a0-ffffffff815ba7b7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d58d1)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815d29e0-ffffffff815d29f7: acpi_scan_lock_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_scan_lock_acquire();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ef791)
Location: drivers/acpi/scan.c:59
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_table_events_fn
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_s2idle_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/dock.c:write_undock
```
**Symbols:**

```
ffffffff815ec8a0-ffffffff815ec8b7: acpi_scan_lock_acquire (STB_GLOBAL)
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
