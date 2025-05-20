# Function: <code>get_latch_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c278)
Location: drivers/pci/hotplug/pci_hotplug_core.c:83
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cad0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:205
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144efb0)
Location: drivers/pci/hotplug/pciehp_core.c:188
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814519c0)
Location: drivers/pci/hotplug/acpiphp_core.c:240
Inline: False
```
**Symbols:**

```
ffffffff8144cad0-ffffffff8144cae7: get_latch_status (STB_LOCAL)
ffffffff8144efb0-ffffffff8144efc6: get_latch_status (STB_LOCAL)
ffffffff814519c0-ffffffff81451a17: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498988)
Location: drivers/pci/hotplug/pci_hotplug_core.c:83
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814991f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:205
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b750)
Location: drivers/pci/hotplug/pciehp_core.c:188
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e1d0)
Location: drivers/pci/hotplug/acpiphp_core.c:240
Inline: False
```
**Symbols:**

```
ffffffff814991f0-ffffffff81499207: get_latch_status (STB_LOCAL)
ffffffff8149b750-ffffffff8149b766: get_latch_status (STB_LOCAL)
ffffffff8149e1d0-ffffffff8149e223: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba578)
Location: drivers/pci/hotplug/pci_hotplug_core.c:80
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bade0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:205
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd330)
Location: drivers/pci/hotplug/pciehp_core.c:190
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814bfe00)
Location: drivers/pci/hotplug/acpiphp_core.c:240
Inline: False
```
**Symbols:**

```
ffffffff814bade0-ffffffff814badf7: get_latch_status (STB_LOCAL)
ffffffff814bd330-ffffffff814bd346: get_latch_status (STB_LOCAL)
ffffffff814bfe00-ffffffff814bfe53: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c4d98)
Location: drivers/pci/hotplug/pci_hotplug_core.c:80
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c55f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:206
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c7b00)
Location: drivers/pci/hotplug/pciehp_core.c:190
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca570)
Location: drivers/pci/hotplug/acpiphp_core.c:240
Inline: False
```
**Symbols:**

```
ffffffff814c55f0-ffffffff814c5607: get_latch_status (STB_LOCAL)
ffffffff814c7b00-ffffffff814c7b16: get_latch_status (STB_LOCAL)
ffffffff814ca570-ffffffff814ca5c3: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815052f8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:80
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505b80)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:206
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815080a0)
Location: drivers/pci/hotplug/pciehp_core.c:190
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150ab20)
Location: drivers/pci/hotplug/acpiphp_core.c:240
Inline: False
```
**Symbols:**

```
ffffffff81505b80-ffffffff81505b97: get_latch_status (STB_LOCAL)
ffffffff815080a0-ffffffff815080b6: get_latch_status (STB_LOCAL)
ffffffff8150ab20-ffffffff8150ab73: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536208)
Location: drivers/pci/hotplug/pci_hotplug_core.c:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536b60)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:192
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81538fe0)
Location: drivers/pci/hotplug/pciehp_core.c:182
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bbd0)
Location: drivers/pci/hotplug/shpchp_core.c:243
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8153f790)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81536b60-ffffffff81536b77: get_latch_status (STB_LOCAL)
ffffffff81538fe0-ffffffff81538ff6: get_latch_status (STB_LOCAL)
ffffffff8153bbd0-ffffffff8153bc54: get_latch_status (STB_LOCAL)
ffffffff8153f790-ffffffff8153f7e3: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154d928)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e200)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81550370)
Location: drivers/pci/hotplug/pciehp_core.c:124
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815530b0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556bb0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8154e200-ffffffff8154e216: get_latch_status (STB_LOCAL)
ffffffff81550370-ffffffff815503b7: get_latch_status (STB_LOCAL)
ffffffff815530b0-ffffffff8155312c: get_latch_status (STB_LOCAL)
ffffffff81556bb0-ffffffff81556bff: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157d748)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e060)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815801f0)
Location: drivers/pci/hotplug/pciehp_core.c:122
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586bf0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8157e060-ffffffff8157e076: get_latch_status (STB_LOCAL)
ffffffff815801f0-ffffffff81580237: get_latch_status (STB_LOCAL)
ffffffff81583010-ffffffff8158305d: get_latch_status (STB_LOCAL)
ffffffff81583523-ffffffff81583559: get_latch_status.cold (STB_LOCAL)
ffffffff81586bf0-ffffffff81586c3f: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f1a8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159faa0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1c60)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a85c0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8159faa0-ffffffff8159fab6: get_latch_status (STB_LOCAL)
ffffffff815a1c60-ffffffff815a1ca7: get_latch_status (STB_LOCAL)
ffffffff815a49f0-ffffffff815a4a3d: get_latch_status (STB_LOCAL)
ffffffff815a4f03-ffffffff815a4f39: get_latch_status.cold (STB_LOCAL)
ffffffff815a85c0-ffffffff815a860f: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647ab8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648420)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164a670)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81651260)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81648420-ffffffff81648436: get_latch_status (STB_LOCAL)
ffffffff8164a670-ffffffff8164a6b7: get_latch_status (STB_LOCAL)
ffffffff8164d640-ffffffff8164d68d: get_latch_status (STB_LOCAL)
ffffffff8164db90-ffffffff8164dbc6: get_latch_status.cold (STB_LOCAL)
ffffffff81651260-ffffffff816512af: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166cc38)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d4d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166eed0)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673c90)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8166d4d0-ffffffff8166d4e6: get_latch_status (STB_LOCAL)
ffffffff8166eed0-ffffffff8166ef17: get_latch_status (STB_LOCAL)
ffffffff81671800-ffffffff8167184d: get_latch_status (STB_LOCAL)
ffffffff81bfc3e9-ffffffff81bfc41f: get_latch_status.cold (STB_LOCAL)
ffffffff81673c90-ffffffff81673cdf: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f1d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fa60)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81651410)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816561c0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8164fa60-ffffffff8164fa76: get_latch_status (STB_LOCAL)
ffffffff81651410-ffffffff81651457: get_latch_status (STB_LOCAL)
ffffffff81653d10-ffffffff81653d5d: get_latch_status (STB_LOCAL)
ffffffff81bee2d4-ffffffff81bee30a: get_latch_status.cold (STB_LOCAL)
ffffffff816561c0-ffffffff8165620f: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c0cf8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c17b0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816c3150)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c81b0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff816c17b0-ffffffff816c17c6: get_latch_status (STB_LOCAL)
ffffffff816c3150-ffffffff816c3197: get_latch_status (STB_LOCAL)
ffffffff816c5b00-ffffffff816c5b60: get_latch_status (STB_LOCAL)
ffffffff81ce9178-ffffffff81ce91c3: get_latch_status.cold (STB_LOCAL)
ffffffff816c81b0-ffffffff816c81fc: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e645c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e6ff0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff817e8b90)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff817ee2c0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff817e6ff0-ffffffff817e700e: get_latch_status (STB_LOCAL)
ffffffff817e8b90-ffffffff817e8bdf: get_latch_status (STB_LOCAL)
ffffffff817eb980-ffffffff817eb9ef: get_latch_status (STB_LOCAL)
ffffffff81eb0214-ffffffff81eb025f: get_latch_status.cold (STB_LOCAL)
ffffffff817ee2c0-ffffffff817ee318: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b2bc)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190bfe0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8190e590)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81916270)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8190bfe0-ffffffff8190bffe: get_latch_status (STB_LOCAL)
ffffffff8190e590-ffffffff8190e5df: get_latch_status (STB_LOCAL)
ffffffff81911e90-ffffffff81911f2e: get_latch_status (STB_LOCAL)
ffffffff8208f9c6-ffffffff8208f9db: get_latch_status.cold (STB_LOCAL)
ffffffff81916270-ffffffff819162c8: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194e93c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f660)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81951c10)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:208
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81959860)
Location: drivers/pci/hotplug/acpiphp_core.c:225
Inline: False
```
**Symbols:**

```
ffffffff8194f660-ffffffff8194f67e: get_latch_status (STB_LOCAL)
ffffffff81951c10-ffffffff81951c5f: get_latch_status (STB_LOCAL)
ffffffff81955520-ffffffff819555be: get_latch_status (STB_LOCAL)
ffffffff8210fd26-ffffffff8210fd3b: get_latch_status.cold (STB_LOCAL)
ffffffff81959860-ffffffff819598b8: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81997d6c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998a90)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b070)
Location: drivers/pci/hotplug/pciehp_core.c:128
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:208
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a2dd0)
Location: drivers/pci/hotplug/acpiphp_core.c:224
Inline: False
```
**Symbols:**

```
ffffffff81998a90-ffffffff81998aae: get_latch_status (STB_LOCAL)
ffffffff8199b070-ffffffff8199b0bf: get_latch_status (STB_LOCAL)
ffffffff8199e9e0-ffffffff8199ea7e: get_latch_status (STB_LOCAL)
ffffffff821eda4e-ffffffff821eda63: get_latch_status.cold (STB_LOCAL)
ffffffff819a2dd0-ffffffff819a2e28: get_latch_status (STB_LOCAL)
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
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff8000107076a4)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010707f88)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a430)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d620)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff800010711630)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffff800010707f88-ffff800010707fc0: get_latch_status (STB_LOCAL)
ffff80001070a430-ffff80001070a48c: get_latch_status (STB_LOCAL)
ffff80001070d620-ffff80001070d6bc: get_latch_status (STB_LOCAL)
ffff800010711630-ffff8000107116bc: get_latch_status (STB_LOCAL)
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
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000087fa60)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880820)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
**Symbols:**

```
c000000000880820-c000000000880840: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5144)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d586a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d7412)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9d70)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
**Symbols:**

```
ffffffe0004d586a-ffffffe0004d589c: get_latch_status (STB_LOCAL)
ffffffe0004d7412-ffffffe0004d7468: get_latch_status (STB_LOCAL)
ffffffe0004d9d70-ffffffe0004d9df2: get_latch_status (STB_LOCAL)
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
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815929b8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815932b0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595470)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159bdd0)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff815932b0-ffffffff815932c6: get_latch_status (STB_LOCAL)
ffffffff81595470-ffffffff815954b7: get_latch_status (STB_LOCAL)
ffffffff81598200-ffffffff8159824d: get_latch_status (STB_LOCAL)
ffffffff81598713-ffffffff81598749: get_latch_status.cold (STB_LOCAL)
ffffffff8159bdd0-ffffffff8159be1f: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581b48)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81582440)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81584600)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158af60)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81582440-ffffffff81582456: get_latch_status (STB_LOCAL)
ffffffff81584600-ffffffff81584647: get_latch_status (STB_LOCAL)
ffffffff81587390-ffffffff815873dd: get_latch_status (STB_LOCAL)
ffffffff815878a3-ffffffff815878d9: get_latch_status.cold (STB_LOCAL)
ffffffff8158af60-ffffffff8158afaf: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592ef8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815937f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815959b0)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c310)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff815937f0-ffffffff81593806: get_latch_status (STB_LOCAL)
ffffffff815959b0-ffffffff815959f7: get_latch_status (STB_LOCAL)
ffffffff81598740-ffffffff8159878d: get_latch_status (STB_LOCAL)
ffffffff81598c53-ffffffff81598c89: get_latch_status.cold (STB_LOCAL)
ffffffff8159c310-ffffffff8159c35f: get_latch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_latch_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad378)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815adc70)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:173
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815afe30)
Location: drivers/pci/hotplug/pciehp_core.c:127
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:209
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b6740)
Location: drivers/pci/hotplug/acpiphp_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff815adc70-ffffffff815adc86: get_latch_status (STB_LOCAL)
ffffffff815afe30-ffffffff815afe77: get_latch_status (STB_LOCAL)
ffffffff815b2b80-ffffffff815b2bcd: get_latch_status (STB_LOCAL)
ffffffff815b3093-ffffffff815b30c9: get_latch_status.cold (STB_LOCAL)
ffffffff815b6740-ffffffff815b678f: get_latch_status (STB_LOCAL)
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
