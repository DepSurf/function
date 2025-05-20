# Function: <code>pci_hp_deregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c820)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8144c820-ffffffff8144ca66: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498f40)
Location: drivers/pci/hotplug/pci_hotplug_core.c:475
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81498f40-ffffffff81499184: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814bab30)
Location: drivers/pci/hotplug/pci_hotplug_core.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff814bab30-ffffffff814bad74: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c5320)
Location: drivers/pci/hotplug/pci_hotplug_core.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff814c5320-ffffffff814c5556: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815058b0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff815058b0-ffffffff81505aec: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:467
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81536ad5-ffffffff81536afc: pci_hp_deregister.cold.14 (STB_LOCAL)
ffffffff815367d0-ffffffff815369f6: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154dd40)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8154dd40-ffffffff8154dd6e: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157db60)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8157db60-ffffffff8157db8e: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f5c0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8159f5c0-ffffffff8159f5ee: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647ef0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81647ef0-ffffffff81647f21: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166d070)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8166d070-ffffffff8166d0a1: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f9c0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8164f9c0-ffffffff8164f9f1: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c1710)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff816c1710-ffffffff816c1741: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6f40)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff817e6f40-ffffffff817e6f77: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190bf00)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8190bf00-ffffffff8190bf37: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194f580)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff8194f580-ffffffff8194f5b7: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff819989b0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff819989b0-ffffffff819989e7: pci_hp_deregister (STB_GLOBAL)
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
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707b10)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffff800010707b10-ffff800010707b4c: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c000000000880240)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
```
**Symbols:**

```
c000000000880240-c000000000880294: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d54d4)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
```
**Symbols:**

```
ffffffe0004d54d4-ffffffe0004d5510: pci_hp_deregister (STB_GLOBAL)
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
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592dd0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81592dd0-ffffffff81592dfe: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581f60)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81581f60-ffffffff81581f8e: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593310)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff81593310-ffffffff8159333e: pci_hp_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_hp_deregister(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad790)
Location: drivers/pci/hotplug/pci_hotplug_core.c:504
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_unregister_hotplug_slot
```
**Symbols:**

```
ffffffff815ad790-ffffffff815ad7be: pci_hp_deregister (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
