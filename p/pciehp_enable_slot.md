# Function: <code>pciehp_enable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f8a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
**Symbols:**

```
ffffffff8144f8a0-ffffffff8144fb28: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c040)
Location: drivers/pci/hotplug/pciehp_ctrl.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff8149c040-ffffffff8149c2ca: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdbd0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:389
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff814bdbd0-ffffffff814bde49: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c83b0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:389
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff814c83b0-ffffffff814c8629: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508960)
Location: drivers/pci/hotplug/pciehp_ctrl.c:390
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff81508960-ffffffff81508bdf: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815398a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:376
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff815398a0-ffffffff81539b24: pciehp_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550c31)
Location: drivers/pci/hotplug/pciehp_ctrl.c:300
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580d86)
Location: drivers/pci/hotplug/pciehp_ctrl.c:306
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a24da)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8164adc0-ffffffff8164aef2: pciehp_enable_slot (STB_LOCAL)
ffffffff8164b4c5-ffffffff8164b51f: pciehp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:309
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8166f550-ffffffff8166f682: pciehp_enable_slot (STB_LOCAL)
ffffffff81bfbe1b-ffffffff81bfbe75: pciehp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:309
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff81651980-ffffffff81651b90: pciehp_enable_slot (STB_LOCAL)
ffffffff81bedc33-ffffffff81bedced: pciehp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:309
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff816c3700-ffffffff816c3910: pciehp_enable_slot (STB_LOCAL)
ffffffff81ce89fa-ffffffff81ce8ab4: pciehp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:309
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff817e9170-ffffffff817e937d: pciehp_enable_slot (STB_LOCAL)
ffffffff81eafa95-ffffffff81eafb4f: pciehp_enable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ed50)
Location: drivers/pci/hotplug/pciehp_ctrl.c:309
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8190ed50-ffffffff8190f001: pciehp_enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff819523c0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:318
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff819523c0-ffffffff81952671: pciehp_enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_enable_slot(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b850)
Location: drivers/pci/hotplug/pciehp_ctrl.c:318
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
**Symbols:**

```
ffffffff8199b850-ffffffff8199bb01: pciehp_enable_slot (STB_LOCAL)
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070af0c)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7bbc)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595cea)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584e7a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8159622a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b06aa)
Location: drivers/pci/hotplug/pciehp_ctrl.c:311
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
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
