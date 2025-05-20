# Function: <code>pciehp_request</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815508b0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:127
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff815508b0-ffffffff815508d7: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580760)
Location: drivers/pci/hotplug/pciehp_ctrl.c:133
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff81580760-ffffffff81580786: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2230)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff815a2230-ffffffff815a2256: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b2ec)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
```
**Symbols:**

```
ffffffff8164af00-ffffffff8164af26: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166fa7c)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
```
**Symbols:**

```
ffffffff8166f690-ffffffff8166f6b6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651f7c)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81651b90-ffffffff81651bb6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c393d)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81ce8ab4-ffffffff81ce8ac8: pciehp_request.cold (STB_LOCAL)
ffffffff816c3910-ffffffff816c3950: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e93ba)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81eafb4f-ffffffff81eafb64: pciehp_request.cold (STB_LOCAL)
ffffffff817e9380-ffffffff817e93d6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f05a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8208f8a7-ffffffff8208f8bc: pciehp_request.cold (STB_LOCAL)
ffffffff8190f020-ffffffff8190f076: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff819526ca)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8210fc07-ffffffff8210fc1c: pciehp_request.cold (STB_LOCAL)
ffffffff81952690-ffffffff819526e6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bb5a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff821ed92f-ffffffff821ed944: pciehp_request.cold (STB_LOCAL)
ffffffff8199bb20-ffffffff8199bb76: pciehp_request (STB_GLOBAL)
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
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070aae8)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffff80001070aae8-ffff80001070ab5c: pciehp_request (STB_GLOBAL)
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
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d8044)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffe0004d781e-ffffffe0004d784c: pciehp_request.part.0 (STB_LOCAL)
ffffffe0004d784c-ffffffe0004d789a: pciehp_request (STB_GLOBAL)
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
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595a40)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff81595a40-ffffffff81595a66: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584bd0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff81584bd0-ffffffff81584bf6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f80)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff81595f80-ffffffff81595fa6: pciehp_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pciehp_request(struct controller *ctrl, int action);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0400)
Location: drivers/pci/hotplug/pciehp_ctrl.c:137
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff815b0400-ffffffff815b0426: pciehp_request (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
