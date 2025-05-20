# Function: <code>pciehp_set_indicators</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3b80)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815a3b80-ffffffff815a3c42: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c7a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:509
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8164c7a0-ffffffff8164c862: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670af0)
Location: drivers/pci/hotplug/pciehp_hpc.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81670af0-ffffffff81670bb2: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652fb0)
Location: drivers/pci/hotplug/pciehp_hpc.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81652fb0-ffffffff81653069: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4d20)
Location: drivers/pci/hotplug/pciehp_hpc.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff816c4d20-ffffffff816c4dd2: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eaa00)
Location: drivers/pci/hotplug/pciehp_hpc.c:514
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff817eaa00-ffffffff817eaad5: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910c20)
Location: drivers/pci/hotplug/pciehp_hpc.c:514
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81910c20-ffffffff81910cf5: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954340)
Location: drivers/pci/hotplug/pciehp_hpc.c:508
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81954340-ffffffff81954415: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d7d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:509
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8199d7d0-ffffffff8199d8a5: pciehp_set_indicators (STB_GLOBAL)
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
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c6b8)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffff80001070c6b8-ffff80001070c7a4: pciehp_set_indicators (STB_GLOBAL)
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
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8f7e)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffe0004d8f7e-ffffffe0004d9042: pciehp_set_indicators (STB_GLOBAL)
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
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597390)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81597390-ffffffff81597452: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586520)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81586520-ffffffff815865e2: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815978d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815978d0-ffffffff81597992: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pciehp_set_indicators(struct controller *ctrl, int pwr, int attn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1d10)
Location: drivers/pci/hotplug/pciehp_hpc.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815b1d10-ffffffff815b1dd2: pciehp_set_indicators (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
