# Function: <code>get_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c1c8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cab0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144ee40)
Location: drivers/pci/hotplug/pciehp_core.c:196
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81451960)
Location: drivers/pci/hotplug/acpiphp_core.c:260
Inline: False
```
**Symbols:**

```
ffffffff8144cab0-ffffffff8144cac7: get_adapter_status (STB_LOCAL)
ffffffff8144ee40-ffffffff8144ee56: get_adapter_status (STB_LOCAL)
ffffffff81451960-ffffffff814519b7: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814988d8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814991d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b5e0)
Location: drivers/pci/hotplug/pciehp_core.c:196
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e170)
Location: drivers/pci/hotplug/acpiphp_core.c:260
Inline: False
```
**Symbols:**

```
ffffffff814991d0-ffffffff814991e7: get_adapter_status (STB_LOCAL)
ffffffff8149b5e0-ffffffff8149b5f6: get_adapter_status (STB_LOCAL)
ffffffff8149e170-ffffffff8149e1c3: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba4c8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:81
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814badc0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd1c0)
Location: drivers/pci/hotplug/pciehp_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814bfda0)
Location: drivers/pci/hotplug/acpiphp_core.c:260
Inline: False
```
**Symbols:**

```
ffffffff814badc0-ffffffff814badd7: get_adapter_status (STB_LOCAL)
ffffffff814bd1c0-ffffffff814bd1d6: get_adapter_status (STB_LOCAL)
ffffffff814bfda0-ffffffff814bfdf3: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c4ce8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:81
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c55d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:199
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c7990)
Location: drivers/pci/hotplug/pciehp_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca510)
Location: drivers/pci/hotplug/acpiphp_core.c:260
Inline: False
```
**Symbols:**

```
ffffffff814c55d0-ffffffff814c55e7: get_adapter_status (STB_LOCAL)
ffffffff814c7990-ffffffff814c79a6: get_adapter_status (STB_LOCAL)
ffffffff814ca510-ffffffff814ca563: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81505238)
Location: drivers/pci/hotplug/pci_hotplug_core.c:81
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505b60)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:199
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81507f30)
Location: drivers/pci/hotplug/pciehp_core.c:198
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150aac0)
Location: drivers/pci/hotplug/acpiphp_core.c:260
Inline: False
```
**Symbols:**

```
ffffffff81505b60-ffffffff81505b77: get_adapter_status (STB_LOCAL)
ffffffff81507f30-ffffffff81507f46: get_adapter_status (STB_LOCAL)
ffffffff8150aac0-ffffffff8150ab13: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536148)
Location: drivers/pci/hotplug/pci_hotplug_core.c:67
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536b40)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:185
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81538e50)
Location: drivers/pci/hotplug/pciehp_core.c:190
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bc60)
Location: drivers/pci/hotplug/shpchp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8153f730)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff81536b40-ffffffff81536b57: get_adapter_status (STB_LOCAL)
ffffffff81538e50-ffffffff81538e66: get_adapter_status (STB_LOCAL)
ffffffff8153bc60-ffffffff8153bce4: get_adapter_status (STB_LOCAL)
ffffffff8153f730-ffffffff8153f783: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154d878)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e1e0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81550320)
Location: drivers/pci/hotplug/pciehp_core.c:135
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553130)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556b60)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8154e1e0-ffffffff8154e1f8: get_adapter_status (STB_LOCAL)
ffffffff81550320-ffffffff81550368: get_adapter_status (STB_LOCAL)
ffffffff81553130-ffffffff815531ac: get_adapter_status (STB_LOCAL)
ffffffff81556b60-ffffffff81556baf: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157d698)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e040)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815801a0)
Location: drivers/pci/hotplug/pciehp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586ba0)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8157e040-ffffffff8157e058: get_adapter_status (STB_LOCAL)
ffffffff815801a0-ffffffff815801e8: get_adapter_status (STB_LOCAL)
ffffffff81583060-ffffffff815830ad: get_adapter_status (STB_LOCAL)
ffffffff81583559-ffffffff8158358f: get_adapter_status.cold (STB_LOCAL)
ffffffff81586ba0-ffffffff81586bef: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f0f8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159fa80)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1c00)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a8570)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8159fa80-ffffffff8159fa98: get_adapter_status (STB_LOCAL)
ffffffff815a1c00-ffffffff815a1c58: get_adapter_status (STB_LOCAL)
ffffffff815a4a40-ffffffff815a4a8d: get_adapter_status (STB_LOCAL)
ffffffff815a4f39-ffffffff815a4f6f: get_adapter_status.cold (STB_LOCAL)
ffffffff815a8570-ffffffff815a85bf: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647a08)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648400)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164a610)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81651210)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff81648400-ffffffff81648418: get_adapter_status (STB_LOCAL)
ffffffff8164a610-ffffffff8164a668: get_adapter_status (STB_LOCAL)
ffffffff8164d690-ffffffff8164d6dd: get_adapter_status (STB_LOCAL)
ffffffff8164dbc6-ffffffff8164dbfc: get_adapter_status.cold (STB_LOCAL)
ffffffff81651210-ffffffff8165125f: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166cb88)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d4b0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166ee70)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673c40)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8166d4b0-ffffffff8166d4c8: get_adapter_status (STB_LOCAL)
ffffffff8166ee70-ffffffff8166eec8: get_adapter_status (STB_LOCAL)
ffffffff81671850-ffffffff8167189d: get_adapter_status (STB_LOCAL)
ffffffff81bfc41f-ffffffff81bfc455: get_adapter_status.cold (STB_LOCAL)
ffffffff81673c40-ffffffff81673c8f: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f128)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fa40)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816513b0)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81656170)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8164fa40-ffffffff8164fa58: get_adapter_status (STB_LOCAL)
ffffffff816513b0-ffffffff81651408: get_adapter_status (STB_LOCAL)
ffffffff81653d60-ffffffff81653dad: get_adapter_status (STB_LOCAL)
ffffffff81bee30a-ffffffff81bee340: get_adapter_status.cold (STB_LOCAL)
ffffffff81656170-ffffffff816561bf: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c0c48)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c1790)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff816c30f0)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c8160)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff816c1790-ffffffff816c17a8: get_adapter_status (STB_LOCAL)
ffffffff816c30f0-ffffffff816c3148: get_adapter_status (STB_LOCAL)
ffffffff816c5b60-ffffffff816c5bc0: get_adapter_status (STB_LOCAL)
ffffffff81ce91c3-ffffffff81ce920e: get_adapter_status.cold (STB_LOCAL)
ffffffff816c8160-ffffffff816c81ac: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e639c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e6fd0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff817e8b30)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff817ee260)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff817e6fd0-ffffffff817e6ff0: get_adapter_status (STB_LOCAL)
ffffffff817e8b30-ffffffff817e8b88: get_adapter_status (STB_LOCAL)
ffffffff817eb9f0-ffffffff817eba5f: get_adapter_status (STB_LOCAL)
ffffffff81eb025f-ffffffff81eb02aa: get_adapter_status.cold (STB_LOCAL)
ffffffff817ee260-ffffffff817ee2b8: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b1ec)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190bfb0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8190e520)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81916200)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff8190bfb0-ffffffff8190bfd0: get_adapter_status (STB_LOCAL)
ffffffff8190e520-ffffffff8190e578: get_adapter_status (STB_LOCAL)
ffffffff81911f40-ffffffff81911fde: get_adapter_status (STB_LOCAL)
ffffffff8208f9db-ffffffff8208f9f0: get_adapter_status.cold (STB_LOCAL)
ffffffff81916200-ffffffff81916258: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194e86c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f630)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81951ba0)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:223
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819597f0)
Location: drivers/pci/hotplug/acpiphp_core.c:245
Inline: False
```
**Symbols:**

```
ffffffff8194f630-ffffffff8194f650: get_adapter_status (STB_LOCAL)
ffffffff81951ba0-ffffffff81951bf8: get_adapter_status (STB_LOCAL)
ffffffff819555d0-ffffffff8195566e: get_adapter_status (STB_LOCAL)
ffffffff8210fd3b-ffffffff8210fd50: get_adapter_status.cold (STB_LOCAL)
ffffffff819597f0-ffffffff81959848: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81997c9c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998a60)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b000)
Location: drivers/pci/hotplug/pciehp_core.c:139
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:223
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a2d60)
Location: drivers/pci/hotplug/acpiphp_core.c:244
Inline: False
```
**Symbols:**

```
ffffffff81998a60-ffffffff81998a80: get_adapter_status (STB_LOCAL)
ffffffff8199b000-ffffffff8199b058: get_adapter_status (STB_LOCAL)
ffffffff8199ea90-ffffffff8199eb2e: get_adapter_status (STB_LOCAL)
ffffffff821eda63-ffffffff821eda78: get_adapter_status.cold (STB_LOCAL)
ffffffff819a2d60-ffffffff819a2db8: get_adapter_status (STB_LOCAL)
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
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff8000107075dc)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010707f50)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a3c8)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d6c0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff8000107115a8)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffff800010707f50-ffff800010707f88: get_adapter_status (STB_LOCAL)
ffff80001070a3c8-ffff80001070a430: get_adapter_status (STB_LOCAL)
ffff80001070d6c0-ffff80001070d75c: get_adapter_status (STB_LOCAL)
ffff8000107115a8-ffff80001071162c: get_adapter_status (STB_LOCAL)
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
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000087f950)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880800)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
**Symbols:**

```
c000000000880800-c000000000880820: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d50b2)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d5836)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d73b2)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9df2)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
**Symbols:**

```
ffffffe0004d5836-ffffffe0004d586a: get_adapter_status (STB_LOCAL)
ffffffe0004d73b2-ffffffe0004d7412: get_adapter_status (STB_LOCAL)
ffffffe0004d9df2-ffffffe0004d9e74: get_adapter_status (STB_LOCAL)
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
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592908)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593290)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595410)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159bd80)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff81593290-ffffffff815932a8: get_adapter_status (STB_LOCAL)
ffffffff81595410-ffffffff81595468: get_adapter_status (STB_LOCAL)
ffffffff81598250-ffffffff8159829d: get_adapter_status (STB_LOCAL)
ffffffff81598749-ffffffff8159877f: get_adapter_status.cold (STB_LOCAL)
ffffffff8159bd80-ffffffff8159bdcf: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581a98)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81582420)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815845a0)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158af10)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff81582420-ffffffff81582438: get_adapter_status (STB_LOCAL)
ffffffff815845a0-ffffffff815845f8: get_adapter_status (STB_LOCAL)
ffffffff815873e0-ffffffff8158742d: get_adapter_status (STB_LOCAL)
ffffffff815878d9-ffffffff8158790f: get_adapter_status.cold (STB_LOCAL)
ffffffff8158af10-ffffffff8158af5f: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592e48)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815937d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595950)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c2c0)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff815937d0-ffffffff815937e8: get_adapter_status (STB_LOCAL)
ffffffff81595950-ffffffff815959a8: get_adapter_status (STB_LOCAL)
ffffffff81598790-ffffffff815987dd: get_adapter_status (STB_LOCAL)
ffffffff81598c89-ffffffff81598cbf: get_adapter_status.cold (STB_LOCAL)
ffffffff8159c2c0-ffffffff8159c30f: get_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int get_adapter_status(struct hotplug_slot *slot, u8 *value);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad2c8)
Location: drivers/pci/hotplug/pci_hotplug_core.c:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815adc50)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:164
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815afdd0)
Location: drivers/pci/hotplug/pciehp_core.c:138
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:224
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b66f0)
Location: drivers/pci/hotplug/acpiphp_core.c:246
Inline: False
```
**Symbols:**

```
ffffffff815adc50-ffffffff815adc68: get_adapter_status (STB_LOCAL)
ffffffff815afdd0-ffffffff815afe28: get_adapter_status (STB_LOCAL)
ffffffff815b2bd0-ffffffff815b2c1d: get_adapter_status (STB_LOCAL)
ffffffff815b30c9-ffffffff815b30ff: get_adapter_status.cold (STB_LOCAL)
ffffffff815b66f0-ffffffff815b673f: get_adapter_status (STB_LOCAL)
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
