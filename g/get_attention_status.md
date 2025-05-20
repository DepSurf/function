# Function: <code>get_attention_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c328)
Location: drivers/pci/hotplug/pci_hotplug_core.c:82
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cb60)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:183
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144ef90)
Location: drivers/pci/hotplug/pciehp_core.c:180
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81451ae0)
Location: drivers/pci/hotplug/acpiphp_core.c:216
Inline: False
```
**Symbols:**

```
ffffffff8144cb60-ffffffff8144cb7d: get_attention_status (STB_LOCAL)
ffffffff8144ef90-ffffffff8144efa6: get_attention_status (STB_LOCAL)
ffffffff81451ae0-ffffffff81451b78: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498a38)
Location: drivers/pci/hotplug/pci_hotplug_core.c:82
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499280)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:183
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b730)
Location: drivers/pci/hotplug/pciehp_core.c:180
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e2e0)
Location: drivers/pci/hotplug/acpiphp_core.c:216
Inline: False
```
**Symbols:**

```
ffffffff81499280-ffffffff8149929d: get_attention_status (STB_LOCAL)
ffffffff8149b730-ffffffff8149b746: get_attention_status (STB_LOCAL)
ffffffff8149e2e0-ffffffff8149e374: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba628)
Location: drivers/pci/hotplug/pci_hotplug_core.c:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bae70)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:183
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd310)
Location: drivers/pci/hotplug/pciehp_core.c:182
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814bff10)
Location: drivers/pci/hotplug/acpiphp_core.c:216
Inline: False
```
**Symbols:**

```
ffffffff814bae70-ffffffff814bae8d: get_attention_status (STB_LOCAL)
ffffffff814bd310-ffffffff814bd326: get_attention_status (STB_LOCAL)
ffffffff814bff10-ffffffff814bffa4: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c4e48)
Location: drivers/pci/hotplug/pci_hotplug_core.c:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5680)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c7ae0)
Location: drivers/pci/hotplug/pciehp_core.c:182
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca680)
Location: drivers/pci/hotplug/acpiphp_core.c:216
Inline: False
```
**Symbols:**

```
ffffffff814c5680-ffffffff814c569d: get_attention_status (STB_LOCAL)
ffffffff814c7ae0-ffffffff814c7af6: get_attention_status (STB_LOCAL)
ffffffff814ca680-ffffffff814ca70f: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815053b8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505c10)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:184
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81508080)
Location: drivers/pci/hotplug/pciehp_core.c:182
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150ac30)
Location: drivers/pci/hotplug/acpiphp_core.c:216
Inline: False
```
**Symbols:**

```
ffffffff81505c10-ffffffff81505c2d: get_attention_status (STB_LOCAL)
ffffffff81508080-ffffffff81508096: get_attention_status (STB_LOCAL)
ffffffff8150ac30-ffffffff8150acc5: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815362c8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536bd0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:170
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81538fc0)
Location: drivers/pci/hotplug/pciehp_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bb40)
Location: drivers/pci/hotplug/shpchp_core.c:228
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8153f8a0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff81536bd0-ffffffff81536bed: get_attention_status (STB_LOCAL)
ffffffff81538fc0-ffffffff81538fd6: get_attention_status (STB_LOCAL)
ffffffff8153bb40-ffffffff8153bbc4: get_attention_status (STB_LOCAL)
ffffffff8153f8a0-ffffffff8153f935: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154d9d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e270)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553030)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556c00)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8154e270-ffffffff8154e28d: get_attention_status (STB_LOCAL)
ffffffff81553030-ffffffff815530ac: get_attention_status (STB_LOCAL)
ffffffff81556c00-ffffffff81556c95: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157d7f8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e0d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586c40)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8157e0d0-ffffffff8157e0ed: get_attention_status (STB_LOCAL)
ffffffff81582fc0-ffffffff8158300d: get_attention_status (STB_LOCAL)
ffffffff815834ed-ffffffff81583523: get_attention_status.cold (STB_LOCAL)
ffffffff81586c40-ffffffff81586cda: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f258)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159fb10)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a8610)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8159fb10-ffffffff8159fb2d: get_attention_status (STB_LOCAL)
ffffffff815a49a0-ffffffff815a49ed: get_attention_status (STB_LOCAL)
ffffffff815a4ecd-ffffffff815a4f03: get_attention_status.cold (STB_LOCAL)
ffffffff815a8610-ffffffff815a86aa: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647b68)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648490)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816512b0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff81648490-ffffffff816484b0: get_attention_status (STB_LOCAL)
ffffffff8164d5f0-ffffffff8164d63d: get_attention_status (STB_LOCAL)
ffffffff8164db5a-ffffffff8164db90: get_attention_status.cold (STB_LOCAL)
ffffffff816512b0-ffffffff8165134a: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166cce8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d540)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673ce0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8166d540-ffffffff8166d560: get_attention_status (STB_LOCAL)
ffffffff816717b0-ffffffff816717fd: get_attention_status (STB_LOCAL)
ffffffff81bfc3b3-ffffffff81bfc3e9: get_attention_status.cold (STB_LOCAL)
ffffffff81673ce0-ffffffff81673d7a: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f288)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fad0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81656210)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8164fad0-ffffffff8164faf0: get_attention_status (STB_LOCAL)
ffffffff81653cc0-ffffffff81653d0d: get_attention_status (STB_LOCAL)
ffffffff81bee29e-ffffffff81bee2d4: get_attention_status.cold (STB_LOCAL)
ffffffff81656210-ffffffff816562aa: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c0da8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c1820)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c8200)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff816c1820-ffffffff816c1840: get_attention_status (STB_LOCAL)
ffffffff816c5aa0-ffffffff816c5b00: get_attention_status (STB_LOCAL)
ffffffff81ce912d-ffffffff81ce9178: get_attention_status.cold (STB_LOCAL)
ffffffff816c8200-ffffffff816c8297: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e651c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e7070)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff817ee320)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff817e7070-ffffffff817e7098: get_attention_status (STB_LOCAL)
ffffffff817eb910-ffffffff817eb97f: get_attention_status (STB_LOCAL)
ffffffff81eb01c9-ffffffff81eb0214: get_attention_status.cold (STB_LOCAL)
ffffffff817ee320-ffffffff817ee3be: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b38c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190c0a0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819162e0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff8190c0a0-ffffffff8190c0c8: get_attention_status (STB_LOCAL)
ffffffff81911de0-ffffffff81911e7e: get_attention_status (STB_LOCAL)
ffffffff8208f9b1-ffffffff8208f9c6: get_attention_status.cold (STB_LOCAL)
ffffffff819162e0-ffffffff8191637e: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194ea0c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f720)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:193
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819598d0)
Location: drivers/pci/hotplug/acpiphp_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff8194f720-ffffffff8194f748: get_attention_status (STB_LOCAL)
ffffffff81955470-ffffffff8195550e: get_attention_status (STB_LOCAL)
ffffffff8210fd11-ffffffff8210fd26: get_attention_status.cold (STB_LOCAL)
ffffffff819598d0-ffffffff8195996e: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81997e3c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998b50)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:193
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a2e40)
Location: drivers/pci/hotplug/acpiphp_core.c:200
Inline: False
```
**Symbols:**

```
ffffffff81998b50-ffffffff81998b78: get_attention_status (STB_LOCAL)
ffffffff8199e930-ffffffff8199e9ce: get_attention_status (STB_LOCAL)
ffffffff821eda39-ffffffff821eda4e: get_attention_status.cold (STB_LOCAL)
ffffffff819a2e40-ffffffff819a2ede: get_attention_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff80001070776c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708040)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d580)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff8000107116c0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffff800010708040-ffff80001070807c: get_attention_status (STB_LOCAL)
ffff80001070d580-ffff80001070d61c: get_attention_status (STB_LOCAL)
ffff8000107116c0-ffff800010711774: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000087fb70)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880900)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
**Symbols:**

```
c000000000880900-c000000000880950: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d51d6)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d5904)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9cee)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffe0004d5904-ffffffe0004d593c: get_attention_status (STB_LOCAL)
ffffffe0004d9cee-ffffffe0004d9d70: get_attention_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592a68)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593320)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159be20)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff81593320-ffffffff8159333d: get_attention_status (STB_LOCAL)
ffffffff815981b0-ffffffff815981fd: get_attention_status (STB_LOCAL)
ffffffff815986dd-ffffffff81598713: get_attention_status.cold (STB_LOCAL)
ffffffff8159be20-ffffffff8159beba: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581bf8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815824b0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158afb0)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff815824b0-ffffffff815824cd: get_attention_status (STB_LOCAL)
ffffffff81587340-ffffffff8158738d: get_attention_status (STB_LOCAL)
ffffffff8158786d-ffffffff815878a3: get_attention_status.cold (STB_LOCAL)
ffffffff8158afb0-ffffffff8158b04a: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592fa8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593860)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c360)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff81593860-ffffffff8159387d: get_attention_status (STB_LOCAL)
ffffffff815986f0-ffffffff8159873d: get_attention_status (STB_LOCAL)
ffffffff81598c1d-ffffffff81598c53: get_attention_status.cold (STB_LOCAL)
ffffffff8159c360-ffffffff8159c3fa: get_attention_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_attention_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad428)
Location: drivers/pci/hotplug/pci_hotplug_core.c:63
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815adce0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:149
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:194
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b6790)
Location: drivers/pci/hotplug/acpiphp_core.c:202
Inline: False
```
**Symbols:**

```
ffffffff815adce0-ffffffff815adcfd: get_attention_status (STB_LOCAL)
ffffffff815b2b30-ffffffff815b2b7d: get_attention_status (STB_LOCAL)
ffffffff815b305d-ffffffff815b3093: get_attention_status.cold (STB_LOCAL)
ffffffff815b6790-ffffffff815b682a: get_attention_status (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
