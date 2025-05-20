# Function: <code>queue_interrupt_event</code>

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
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c580)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff8153c580-ffffffff8153c5f9: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815539a0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff815539a0-ffffffff81553a19: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81583850)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81583850-ffffffff815838c9: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a5230)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff815a5230-ffffffff815a52a9: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164e470)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff8164e470-ffffffff8164e4e0: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff816723e0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff816723e0-ffffffff81672450: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81654b30)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81654b30-ffffffff81654ba0: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff816c6a00)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff816c6a00-ffffffff816c6a70: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff817ec980)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff817ec980-ffffffff817ec9fe: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819136e0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff819136e0-ffffffff8191375e: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81956d50)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81956d50-ffffffff81956dce: queue_interrupt_event.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a0270)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff819a0270-ffffffff819a031c: queue_interrupt_event.isra.0 (STB_LOCAL)
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
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070df90)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffff80001070df90-ffff80001070e010: queue_interrupt_event (STB_LOCAL)
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
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da578)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffe0004da578-ffffffe0004da5f2: queue_interrupt_event (STB_LOCAL)
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
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81598a40)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81598a40-ffffffff81598ab9: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81587bd0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81587bd0-ffffffff81587c49: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81598f80)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff81598f80-ffffffff81598ff9: queue_interrupt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b33c0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:28
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
```
**Symbols:**

```
ffffffff815b33c0-ffffffff815b3439: queue_interrupt_event (STB_LOCAL)
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
