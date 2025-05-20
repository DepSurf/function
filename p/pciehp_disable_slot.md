# Function: <code>pciehp_disable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144fb30)
Location: drivers/pci/hotplug/pciehp_ctrl.c:445
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
```
**Symbols:**

```
ffffffff8144fb30-ffffffff8144fbf5: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c2d0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:445
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff8149c2d0-ffffffff8149c3a2: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bde50)
Location: drivers/pci/hotplug/pciehp_ctrl.c:423
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff814bde50-ffffffff814bdf22: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c8630)
Location: drivers/pci/hotplug/pciehp_ctrl.c:423
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff814c8630-ffffffff814c8700: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508be0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:424
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff81508be0-ffffffff81508cb0: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pciehp_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539b30)
Location: drivers/pci/hotplug/pciehp_ctrl.c:410
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_power_thread
```
**Symbols:**

```
ffffffff81539b30-ffffffff81539c02: pciehp_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815507a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:334
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff815507a0-ffffffff815508aa: pciehp_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:340
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81580670-ffffffff8158075d: pciehp_disable_slot (STB_LOCAL)
ffffffff81580c1d-ffffffff81580c4d: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff815a2130-ffffffff815a2227: pciehp_disable_slot (STB_LOCAL)
ffffffff815a2856-ffffffff815a2886: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff8164ac10-ffffffff8164ad05: pciehp_disable_slot (STB_LOCAL)
ffffffff8164b3d0-ffffffff8164b400: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff8166f360-ffffffff8166f455: pciehp_disable_slot (STB_LOCAL)
ffffffff81bfbd80-ffffffff81bfbdb0: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81651880-ffffffff81651975: pciehp_disable_slot (STB_LOCAL)
ffffffff81bedc03-ffffffff81bedc33: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff816c3600-ffffffff816c36f5: pciehp_disable_slot (STB_LOCAL)
ffffffff81ce89ca-ffffffff81ce89fa: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff817e9060-ffffffff817e9162: pciehp_disable_slot (STB_LOCAL)
ffffffff81eafa65-ffffffff81eafa95: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ec00)
Location: drivers/pci/hotplug/pciehp_ctrl.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff8190ec00-ffffffff8190ed32: pciehp_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952280)
Location: drivers/pci/hotplug/pciehp_ctrl.c:354
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81952280-ffffffff819523af: pciehp_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b710)
Location: drivers/pci/hotplug/pciehp_ctrl.c:354
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff8199b710-ffffffff8199b83f: pciehp_disable_slot (STB_LOCAL)
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
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070a9a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffff80001070a9a0-ffff80001070aae4: pciehp_disable_slot (STB_LOCAL)
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
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d772a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffe0004d772a-ffffffe0004d781e: pciehp_disable_slot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81595940-ffffffff81595a37: pciehp_disable_slot (STB_LOCAL)
ffffffff81596066-ffffffff81596096: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81584ad0-ffffffff81584bc7: pciehp_disable_slot (STB_LOCAL)
ffffffff815851f6-ffffffff81585226: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff81595e80-ffffffff81595f77: pciehp_disable_slot (STB_LOCAL)
ffffffff815965a6-ffffffff815965d6: pciehp_disable_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pciehp_disable_slot(struct controller *ctrl, bool safe_removal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:347
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
```
**Symbols:**

```
ffffffff815b0300-ffffffff815b03f7: pciehp_disable_slot (STB_LOCAL)
ffffffff815b0a21-ffffffff815b0a51: pciehp_disable_slot.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller *ctrl</code>
</li>
<li>
<b>Param added. </b>
<code>bool safe_removal</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot *p_slot</code>
</li>
</ul>
</details>
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
