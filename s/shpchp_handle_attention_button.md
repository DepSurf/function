# Function: <code>shpchp_handle_attention_button</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d1b0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8153d1b0-ffffffff8153d290: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815545b0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815545b0-ffffffff81554687: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81584a65-ffffffff81584aab: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81584080-ffffffff8158411e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815a6445-ffffffff815a648b: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff815a5a60-ffffffff815a5afe: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8164f14f-ffffffff8164f195: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff8164e740-ffffffff8164e7de: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81bfcba0-ffffffff81bfcbe6: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff816726b0-ffffffff8167274e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81beea7b-ffffffff81beeac1: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81654ba0-ffffffff81654c3e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81ce9a5f-ffffffff81ce9aba: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff816c6a70-ffffffff816c6b21: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81eb0b25-ffffffff81eb0b81: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff817eca00-ffffffff817ecab8: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8208fb61-ffffffff8208fb76: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81913770-ffffffff81913865: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8210febd-ffffffff8210fed2: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81956de0-ffffffff81956ed5: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff821edbe5-ffffffff821edbfa: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff819a0330-ffffffff819a0425: shpchp_handle_attention_button (STB_GLOBAL)
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070eb80)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffff80001070eb80-ffff80001070ec74: shpchp_handle_attention_button (STB_GLOBAL)
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004daf8a)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffe0004daf8a-ffffffe0004db05e: shpchp_handle_attention_button (STB_GLOBAL)
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
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81599c55-ffffffff81599c9b: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81599270-ffffffff8159930e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81588de5-ffffffff81588e2b: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff81588400-ffffffff8158849e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8159a195-ffffffff8159a1db: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff815997b0-ffffffff8159984e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_attention_button(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:45
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815b45d5-ffffffff815b461b: shpchp_handle_attention_button.cold (STB_LOCAL)
ffffffff815b3bf0-ffffffff815b3c8e: shpchp_handle_attention_button (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
