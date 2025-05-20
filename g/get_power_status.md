# Function: <code>get_power_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c3d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:81
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144ca70)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144ef20)
Location: drivers/pci/hotplug/pciehp_core.c:172
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81451a20)
Location: drivers/pci/hotplug/acpiphp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffff8144ca70-ffffffff8144caa3: get_power_status (STB_LOCAL)
ffffffff8144ef20-ffffffff8144ef36: get_power_status (STB_LOCAL)
ffffffff81451a20-ffffffff81451a77: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498ae8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:81
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499190)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b6c0)
Location: drivers/pci/hotplug/pciehp_core.c:172
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e230)
Location: drivers/pci/hotplug/acpiphp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffff81499190-ffffffff814991c3: get_power_status (STB_LOCAL)
ffffffff8149b6c0-ffffffff8149b6d6: get_power_status (STB_LOCAL)
ffffffff8149e230-ffffffff8149e283: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba6d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bad80)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd2a0)
Location: drivers/pci/hotplug/pciehp_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814bfe60)
Location: drivers/pci/hotplug/acpiphp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffff814bad80-ffffffff814badb3: get_power_status (STB_LOCAL)
ffffffff814bd2a0-ffffffff814bd2b6: get_power_status (STB_LOCAL)
ffffffff814bfe60-ffffffff814bfeb3: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c4ef8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5590)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:175
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c7a70)
Location: drivers/pci/hotplug/pciehp_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca5d0)
Location: drivers/pci/hotplug/acpiphp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffff814c5590-ffffffff814c55c5: get_power_status (STB_LOCAL)
ffffffff814c7a70-ffffffff814c7a86: get_power_status (STB_LOCAL)
ffffffff814ca5d0-ffffffff814ca623: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81505478)
Location: drivers/pci/hotplug/pci_hotplug_core.c:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505b20)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:175
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81508010)
Location: drivers/pci/hotplug/pciehp_core.c:174
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150ab80)
Location: drivers/pci/hotplug/acpiphp_core.c:194
Inline: False
```
**Symbols:**

```
ffffffff81505b20-ffffffff81505b58: get_power_status (STB_LOCAL)
ffffffff81508010-ffffffff81508026: get_power_status (STB_LOCAL)
ffffffff8150ab80-ffffffff8150abd3: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536388)
Location: drivers/pci/hotplug/pci_hotplug_core.c:64
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536b00)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:161
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81538f30)
Location: drivers/pci/hotplug/pciehp_core.c:166
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bab0)
Location: drivers/pci/hotplug/shpchp_core.c:213
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8153f7f0)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff81536b00-ffffffff81536b36: get_power_status (STB_LOCAL)
ffffffff81538f30-ffffffff81538f46: get_power_status (STB_LOCAL)
ffffffff8153bab0-ffffffff8153bb33: get_power_status (STB_LOCAL)
ffffffff8153f7f0-ffffffff8153f843: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154da88)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e1a0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815503c0)
Location: drivers/pci/hotplug/pciehp_core.c:113
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81552fb0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556d40)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8154e1a0-ffffffff8154e1d6: get_power_status (STB_LOCAL)
ffffffff815503c0-ffffffff81550407: get_power_status (STB_LOCAL)
ffffffff81552fb0-ffffffff8155302c: get_power_status (STB_LOCAL)
ffffffff81556d40-ffffffff81556d8f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157d8a8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e000)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81580240)
Location: drivers/pci/hotplug/pciehp_core.c:111
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586d80)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8157e000-ffffffff8157e036: get_power_status (STB_LOCAL)
ffffffff81580240-ffffffff81580287: get_power_status (STB_LOCAL)
ffffffff81582f70-ffffffff81582fbd: get_power_status (STB_LOCAL)
ffffffff815834b7-ffffffff815834ed: get_power_status.cold (STB_LOCAL)
ffffffff81586d80-ffffffff81586dcf: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f308)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159fa40)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1cb0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a8750)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8159fa40-ffffffff8159fa76: get_power_status (STB_LOCAL)
ffffffff815a1cb0-ffffffff815a1cf7: get_power_status (STB_LOCAL)
ffffffff815a4950-ffffffff815a499d: get_power_status (STB_LOCAL)
ffffffff815a4e97-ffffffff815a4ecd: get_power_status.cold (STB_LOCAL)
ffffffff815a8750-ffffffff815a879f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647c18)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816483c0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164a6c0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816513f0)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff816483c0-ffffffff816483f9: get_power_status (STB_LOCAL)
ffffffff8164a6c0-ffffffff8164a707: get_power_status (STB_LOCAL)
ffffffff8164d5a0-ffffffff8164d5ed: get_power_status (STB_LOCAL)
ffffffff8164db24-ffffffff8164db5a: get_power_status.cold (STB_LOCAL)
ffffffff816513f0-ffffffff8165143f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166cd98)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d470)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166ef20)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673e20)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8166d470-ffffffff8166d4a9: get_power_status (STB_LOCAL)
ffffffff8166ef20-ffffffff8166ef67: get_power_status (STB_LOCAL)
ffffffff81671760-ffffffff816717ad: get_power_status (STB_LOCAL)
ffffffff81bfc37d-ffffffff81bfc3b3: get_power_status.cold (STB_LOCAL)
ffffffff81673e20-ffffffff81673e6f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f338)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fa00)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81651460)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81656350)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8164fa00-ffffffff8164fa39: get_power_status (STB_LOCAL)
ffffffff81651460-ffffffff816514a7: get_power_status (STB_LOCAL)
ffffffff81653c70-ffffffff81653cbd: get_power_status (STB_LOCAL)
ffffffff81bee268-ffffffff81bee29e: get_power_status.cold (STB_LOCAL)
ffffffff81656350-ffffffff8165639f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c0e58)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c1750)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816c31a0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c8340)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff816c1750-ffffffff816c1789: get_power_status (STB_LOCAL)
ffffffff816c31a0-ffffffff816c31e7: get_power_status (STB_LOCAL)
ffffffff816c5a40-ffffffff816c5aa0: get_power_status (STB_LOCAL)
ffffffff81ce90e2-ffffffff81ce912d: get_power_status.cold (STB_LOCAL)
ffffffff816c8340-ffffffff816c838c: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e65dc)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e6f80)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff817e8be0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff817ee460)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff817e6f80-ffffffff817e6fc3: get_power_status (STB_LOCAL)
ffffffff817e8be0-ffffffff817e8c2f: get_power_status (STB_LOCAL)
ffffffff817eb8a0-ffffffff817eb90f: get_power_status (STB_LOCAL)
ffffffff81eb017e-ffffffff81eb01c9: get_power_status.cold (STB_LOCAL)
ffffffff817ee460-ffffffff817ee4b8: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b45c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190bf50)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8190e5f0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81916440)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff8190bf50-ffffffff8190bf93: get_power_status (STB_LOCAL)
ffffffff8190e5f0-ffffffff8190e63f: get_power_status (STB_LOCAL)
ffffffff81911d30-ffffffff81911dce: get_power_status (STB_LOCAL)
ffffffff8208f99c-ffffffff8208f9b1: get_power_status.cold (STB_LOCAL)
ffffffff81916440-ffffffff81916498: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194eadc)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f5d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81951c70)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81959a30)
Location: drivers/pci/hotplug/acpiphp_core.c:179
Inline: False
```
**Symbols:**

```
ffffffff8194f5d0-ffffffff8194f613: get_power_status (STB_LOCAL)
ffffffff81951c70-ffffffff81951cbf: get_power_status (STB_LOCAL)
ffffffff819553c0-ffffffff8195545e: get_power_status (STB_LOCAL)
ffffffff8210fcfc-ffffffff8210fd11: get_power_status.cold (STB_LOCAL)
ffffffff81959a30-ffffffff81959a88: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81997f0c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998a00)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b0d0)
Location: drivers/pci/hotplug/pciehp_core.c:117
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a2fa0)
Location: drivers/pci/hotplug/acpiphp_core.c:178
Inline: False
```
**Symbols:**

```
ffffffff81998a00-ffffffff81998a43: get_power_status (STB_LOCAL)
ffffffff8199b0d0-ffffffff8199b11f: get_power_status (STB_LOCAL)
ffffffff8199e880-ffffffff8199e91e: get_power_status (STB_LOCAL)
ffffffff821eda24-ffffffff821eda39: get_power_status.cold (STB_LOCAL)
ffffffff819a2fa0-ffffffff819a2ff8: get_power_status (STB_LOCAL)
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
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707834)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010707ef8)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a490)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d4e0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff800010711830)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffff800010707ef8-ffff800010707f4c: get_power_status (STB_LOCAL)
ffff80001070a490-ffff80001070a4ec: get_power_status (STB_LOCAL)
ffff80001070d4e0-ffff80001070d57c: get_power_status (STB_LOCAL)
ffff800010711830-ffff8000107118bc: get_power_status (STB_LOCAL)
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
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000087fc80)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880780)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
**Symbols:**

```
c000000000880780-c0000000008807f4: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5268)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d57f4)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d7468)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9c6c)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
**Symbols:**

```
ffffffe0004d57f4-ffffffe0004d5836: get_power_status (STB_LOCAL)
ffffffe0004d7468-ffffffe0004d74be: get_power_status (STB_LOCAL)
ffffffe0004d9c6c-ffffffe0004d9cee: get_power_status (STB_LOCAL)
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
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592b18)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593250)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815954c0)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159bf60)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff81593250-ffffffff81593286: get_power_status (STB_LOCAL)
ffffffff815954c0-ffffffff81595507: get_power_status (STB_LOCAL)
ffffffff81598160-ffffffff815981ad: get_power_status (STB_LOCAL)
ffffffff815986a7-ffffffff815986dd: get_power_status.cold (STB_LOCAL)
ffffffff8159bf60-ffffffff8159bfaf: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581ca8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815823e0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81584650)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158b0f0)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff815823e0-ffffffff81582416: get_power_status (STB_LOCAL)
ffffffff81584650-ffffffff81584697: get_power_status (STB_LOCAL)
ffffffff815872f0-ffffffff8158733d: get_power_status (STB_LOCAL)
ffffffff81587837-ffffffff8158786d: get_power_status.cold (STB_LOCAL)
ffffffff8158b0f0-ffffffff8158b13f: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593058)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593790)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595a00)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c4a0)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff81593790-ffffffff815937c6: get_power_status (STB_LOCAL)
ffffffff81595a00-ffffffff81595a47: get_power_status (STB_LOCAL)
ffffffff815986a0-ffffffff815986ed: get_power_status (STB_LOCAL)
ffffffff81598be7-ffffffff81598c1d: get_power_status.cold (STB_LOCAL)
ffffffff8159c4a0-ffffffff8159c4ef: get_power_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_power_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad4d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:62
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815adc10)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:140
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815afe80)
Location: drivers/pci/hotplug/pciehp_core.c:116
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:179
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b68d0)
Location: drivers/pci/hotplug/acpiphp_core.c:180
Inline: False
```
**Symbols:**

```
ffffffff815adc10-ffffffff815adc46: get_power_status (STB_LOCAL)
ffffffff815afe80-ffffffff815afec7: get_power_status (STB_LOCAL)
ffffffff815b2ae0-ffffffff815b2b2d: get_power_status (STB_LOCAL)
ffffffff815b3027-ffffffff815b305d: get_power_status.cold (STB_LOCAL)
ffffffff815b68d0-ffffffff815b691f: get_power_status (STB_LOCAL)
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
