# Function: <code>handle_button_press_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f4ec)
Location: drivers/pci/hotplug/pciehp_ctrl.c:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149bc88)
Location: drivers/pci/hotplug/pciehp_ctrl.c:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bd818)
Location: drivers/pci/hotplug/pciehp_ctrl.c:247
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c7ff5)
Location: drivers/pci/hotplug/pciehp_ctrl.c:247
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8150859b)
Location: drivers/pci/hotplug/pciehp_ctrl.c:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539609)
Location: drivers/pci/hotplug/pciehp_ctrl.c:234
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c320)
Location: drivers/pci/hotplug/shpchp_ctrl.c:471
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553764)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8158375b)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a513b)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:459
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8164ddb0-ffffffff8164de40: handle_button_press_event (STB_LOCAL)
ffffffff8164eb39-ffffffff8164ec97: handle_button_press_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff81671d20-ffffffff81671db0: handle_button_press_event (STB_LOCAL)
ffffffff81bfc58a-ffffffff81bfc6e8: handle_button_press_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff81654230-ffffffff816542c0: handle_button_press_event (STB_LOCAL)
ffffffff81bee475-ffffffff81bee5d3: handle_button_press_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff816c6070-ffffffff816c6100: handle_button_press_event (STB_LOCAL)
ffffffff81ce939c-ffffffff81ce94fa: handle_button_press_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff817ebf60-ffffffff817ebff2: handle_button_press_event (STB_LOCAL)
ffffffff81eb0434-ffffffff81eb0598: handle_button_press_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819126a0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff819126a0-ffffffff81912892: handle_button_press_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81955d30)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff81955d30-ffffffff81955f17: handle_button_press_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_button_press_event(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8199f250)
Location: drivers/pci/hotplug/shpchp_ctrl.c:458
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8199f250-ffffffff8199f437: handle_button_press_event (STB_LOCAL)
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070dd48)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da392)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8159894b)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81587adb)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81598e8b)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b32cb)
Location: drivers/pci/hotplug/shpchp_ctrl.c:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
