# Function: <code>enable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144caf0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:104
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8144f010)
Location: drivers/pci/hotplug/pciehp_core.c:157
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81451c80)
Location: drivers/pci/hotplug/acpiphp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452220)
Location: drivers/pci/hotplug/acpiphp_glue.c:483
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
```
**Symbols:**

```
ffffffff8144caf0-ffffffff8144cb53: enable_slot (STB_LOCAL)
ffffffff8144f010-ffffffff8144f024: enable_slot (STB_LOCAL)
ffffffff81451c80-ffffffff81451cd4: enable_slot (STB_LOCAL)
ffffffff81452220-ffffffff81452507: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499210)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:104
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8149b7b0)
Location: drivers/pci/hotplug/pciehp_core.c:157
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e470)
Location: drivers/pci/hotplug/acpiphp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149e8b0)
Location: drivers/pci/hotplug/acpiphp_glue.c:483
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81499210-ffffffff81499273: enable_slot (STB_LOCAL)
ffffffff8149b7b0-ffffffff8149b7c4: enable_slot (STB_LOCAL)
ffffffff8149e470-ffffffff8149e4c0: enable_slot (STB_LOCAL)
ffffffff8149e8b0-ffffffff8149ebbc: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bae00)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:104
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814bd390)
Location: drivers/pci/hotplug/pciehp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814c00a0)
Location: drivers/pci/hotplug/acpiphp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c04e0)
Location: drivers/pci/hotplug/acpiphp_glue.c:454
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff814bae00-ffffffff814bae63: enable_slot (STB_LOCAL)
ffffffff814bd390-ffffffff814bd3a4: enable_slot (STB_LOCAL)
ffffffff814c00a0-ffffffff814c00f0: enable_slot (STB_LOCAL)
ffffffff814c04e0-ffffffff814c07ec: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5610)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:105
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff814c7b60)
Location: drivers/pci/hotplug/pciehp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca7f0)
Location: drivers/pci/hotplug/acpiphp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cac20)
Location: drivers/pci/hotplug/acpiphp_glue.c:454
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff814c5610-ffffffff814c5675: enable_slot (STB_LOCAL)
ffffffff814c7b60-ffffffff814c7b74: enable_slot (STB_LOCAL)
ffffffff814ca7f0-ffffffff814ca840: enable_slot (STB_LOCAL)
ffffffff814cac20-ffffffff814caf25: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505ba0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:105
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81508100)
Location: drivers/pci/hotplug/pciehp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150adc0)
Location: drivers/pci/hotplug/acpiphp_core.c:133
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150b1f0)
Location: drivers/pci/hotplug/acpiphp_glue.c:454
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81505ba0-ffffffff81505c08: enable_slot (STB_LOCAL)
ffffffff81508100-ffffffff81508114: enable_slot (STB_LOCAL)
ffffffff8150adc0-ffffffff8150ae10: enable_slot (STB_LOCAL)
ffffffff8150b1f0-ffffffff8150b4fd: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:91
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81539040)
Location: drivers/pci/hotplug/pciehp_core.c:151
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bd60)
Location: drivers/pci/hotplug/shpchp_core.c:193
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8153fa30)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815406d0)
Location: drivers/pci/hotplug/acpiphp_glue.c:465
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81536b80-ffffffff81536bc2: enable_slot (STB_LOCAL)
ffffffff81537a09-ffffffff81537a34: enable_slot.cold.13 (STB_LOCAL)
ffffffff81539040-ffffffff81539054: enable_slot (STB_LOCAL)
ffffffff8153bd60-ffffffff8153bdc2: enable_slot (STB_LOCAL)
ffffffff8153fa30-ffffffff8153fa80: enable_slot (STB_LOCAL)
ffffffff815406d0-ffffffff81540b6f: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553210)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556de0)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557930)
Location: drivers/pci/hotplug/acpiphp_glue.c:465
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff8154e220-ffffffff8154e262: enable_slot (STB_LOCAL)
ffffffff8154eea8-ffffffff8154eecf: enable_slot.cold.11 (STB_LOCAL)
ffffffff81553210-ffffffff8155326e: enable_slot (STB_LOCAL)
ffffffff81556de0-ffffffff81556e2c: enable_slot (STB_LOCAL)
ffffffff81557930-ffffffff81557da9: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586e20)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587960)
Location: drivers/pci/hotplug/acpiphp_glue.c:465
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff8157e080-ffffffff8157e0c2: enable_slot (STB_LOCAL)
ffffffff8157ece9-ffffffff8157ed10: enable_slot.cold (STB_LOCAL)
ffffffff815830e0-ffffffff81583108: enable_slot (STB_LOCAL)
ffffffff815835c5-ffffffff815835fb: enable_slot.cold (STB_LOCAL)
ffffffff81586e20-ffffffff81586e6c: enable_slot (STB_LOCAL)
ffffffff81587960-ffffffff81587dc9: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a87f0)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9320)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff8159fac0-ffffffff8159fb02: enable_slot (STB_LOCAL)
ffffffff815a0729-ffffffff815a0750: enable_slot.cold (STB_LOCAL)
ffffffff815a4ac0-ffffffff815a4ae8: enable_slot (STB_LOCAL)
ffffffff815a4fa5-ffffffff815a4fdb: enable_slot.cold (STB_LOCAL)
ffffffff815a87f0-ffffffff815a883c: enable_slot (STB_LOCAL)
ffffffff815a9320-ffffffff815a97d0: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816514a0)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651fd0)
Location: drivers/pci/hotplug/acpiphp_glue.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff81648440-ffffffff81648485: enable_slot (STB_LOCAL)
ffffffff816490d5-ffffffff816490fc: enable_slot.cold (STB_LOCAL)
ffffffff8164d710-ffffffff8164d73a: enable_slot (STB_LOCAL)
ffffffff8164dc32-ffffffff8164dc68: enable_slot.cold (STB_LOCAL)
ffffffff816514a0-ffffffff816514f2: enable_slot (STB_LOCAL)
ffffffff81651fd0-ffffffff81652402: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673ed0)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674990)
Location: drivers/pci/hotplug/acpiphp_glue.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff8166d4f0-ffffffff8166d535: enable_slot (STB_LOCAL)
ffffffff81bfb40f-ffffffff81bfb436: enable_slot.cold (STB_LOCAL)
ffffffff816718d0-ffffffff816718fa: enable_slot (STB_LOCAL)
ffffffff81bfc48b-ffffffff81bfc4c1: enable_slot.cold (STB_LOCAL)
ffffffff81673ed0-ffffffff81673f22: enable_slot (STB_LOCAL)
ffffffff81674990-ffffffff81674dc2: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81656400)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656ec0)
Location: drivers/pci/hotplug/acpiphp_glue.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff8164fa80-ffffffff8164fac5: enable_slot (STB_LOCAL)
ffffffff81bed289-ffffffff81bed2b0: enable_slot.cold (STB_LOCAL)
ffffffff81653de0-ffffffff81653e0a: enable_slot (STB_LOCAL)
ffffffff81bee376-ffffffff81bee3ac: enable_slot.cold (STB_LOCAL)
ffffffff81656400-ffffffff81656452: enable_slot (STB_LOCAL)
ffffffff81656ec0-ffffffff816572fb: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c83e0)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8e40)
Location: drivers/pci/hotplug/acpiphp_glue.c:473
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff816c17d0-ffffffff816c1815: enable_slot (STB_LOCAL)
ffffffff81ce7fb3-ffffffff81ce7fda: enable_slot.cold (STB_LOCAL)
ffffffff816c5c00-ffffffff816c5c40: enable_slot (STB_LOCAL)
ffffffff81ce9259-ffffffff81ce92a4: enable_slot.cold (STB_LOCAL)
ffffffff816c83e0-ffffffff816c842f: enable_slot (STB_LOCAL)
ffffffff816c8e40-ffffffff816c92b7: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff817ee530)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ef090)
Location: drivers/pci/hotplug/acpiphp_glue.c:474
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff817e7010-ffffffff817e7061: enable_slot (STB_LOCAL)
ffffffff81eaf031-ffffffff81eaf058: enable_slot.cold (STB_LOCAL)
ffffffff817ebab0-ffffffff817ebaff: enable_slot (STB_LOCAL)
ffffffff81eb02f5-ffffffff81eb0340: enable_slot.cold (STB_LOCAL)
ffffffff817ee530-ffffffff817ee597: enable_slot (STB_LOCAL)
ffffffff817ef090-ffffffff817ef50a: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190c010)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81916530)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819171b0)
Location: drivers/pci/hotplug/acpiphp_glue.c:482
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff8190c010-ffffffff8190c081: enable_slot (STB_LOCAL)
ffffffff819120a0-ffffffff8191213a: enable_slot (STB_LOCAL)
ffffffff8208fa05-ffffffff8208fa1a: enable_slot.cold (STB_LOCAL)
ffffffff81916530-ffffffff81916597: enable_slot (STB_LOCAL)
ffffffff819171b0-ffffffff81917635: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f690)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:158
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81959b20)
Location: drivers/pci/hotplug/acpiphp_core.c:118
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a7b0)
Location: drivers/pci/hotplug/acpiphp_glue.c:482
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff8194f690-ffffffff8194f701: enable_slot (STB_LOCAL)
ffffffff81955730-ffffffff819557ca: enable_slot (STB_LOCAL)
ffffffff8210fd65-ffffffff8210fd7a: enable_slot.cold (STB_LOCAL)
ffffffff81959b20-ffffffff81959b87: enable_slot (STB_LOCAL)
ffffffff8195a7b0-ffffffff8195ac91: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998ac0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:158
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a3090)
Location: drivers/pci/hotplug/acpiphp_core.c:117
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3db0)
Location: drivers/pci/hotplug/acpiphp_glue.c:482
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
```
**Symbols:**

```
ffffffff81998ac0-ffffffff81998b31: enable_slot (STB_LOCAL)
ffffffff8199ebf0-ffffffff8199ec8a: enable_slot (STB_LOCAL)
ffffffff821eda8d-ffffffff821edaa2: enable_slot.cold (STB_LOCAL)
ffffffff819a3090-ffffffff819a30f7: enable_slot (STB_LOCAL)
ffffffff819a3db0-ffffffff819a424e: enable_slot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010707fc0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d7d8)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff800010711930)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712610)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffff800010707fc0-ffff80001070803c: enable_slot (STB_LOCAL)
ffff80001070d7d8-ffff80001070d84c: enable_slot (STB_LOCAL)
ffff800010711930-ffff8000107119a0: enable_slot (STB_LOCAL)
ffff800010712610-ffff800010712ae4: enable_slot (STB_LOCAL)
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
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880840)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
**Symbols:**

```
c000000000880840-c0000000008808f8: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d589c)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9ee0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
**Symbols:**

```
ffffffe0004d589c-ffffffe0004d5904: enable_slot (STB_LOCAL)
ffffffe0004d9ee0-ffffffe0004d9f4c: enable_slot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c000)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159caf0)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff815932d0-ffffffff81593312: enable_slot (STB_LOCAL)
ffffffff81593f39-ffffffff81593f60: enable_slot.cold (STB_LOCAL)
ffffffff815982d0-ffffffff815982f8: enable_slot (STB_LOCAL)
ffffffff815987b5-ffffffff815987eb: enable_slot.cold (STB_LOCAL)
ffffffff8159c000-ffffffff8159c04c: enable_slot (STB_LOCAL)
ffffffff8159caf0-ffffffff8159cfa0: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158b190)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bc80)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81582460-ffffffff815824a2: enable_slot (STB_LOCAL)
ffffffff815830c9-ffffffff815830f0: enable_slot.cold (STB_LOCAL)
ffffffff81587460-ffffffff81587488: enable_slot (STB_LOCAL)
ffffffff81587945-ffffffff8158797b: enable_slot.cold (STB_LOCAL)
ffffffff8158b190-ffffffff8158b1dc: enable_slot (STB_LOCAL)
ffffffff8158bc80-ffffffff8158c130: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c540)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d070)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81593810-ffffffff81593852: enable_slot (STB_LOCAL)
ffffffff81594479-ffffffff815944a0: enable_slot.cold (STB_LOCAL)
ffffffff81598810-ffffffff81598838: enable_slot (STB_LOCAL)
ffffffff81598cf5-ffffffff81598d2b: enable_slot.cold (STB_LOCAL)
ffffffff8159c540-ffffffff8159c58c: enable_slot (STB_LOCAL)
ffffffff8159d070-ffffffff8159d520: enable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int enable_slot(struct hotplug_slot *hotplug_slot);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:71
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:159
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b6970)
Location: drivers/pci/hotplug/acpiphp_core.c:119
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b74a0)
Location: drivers/pci/hotplug/acpiphp_glue.c:472
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff815adc90-ffffffff815adcd2: enable_slot (STB_LOCAL)
ffffffff815ae8f9-ffffffff815ae920: enable_slot.cold (STB_LOCAL)
ffffffff815b2c50-ffffffff815b2c78: enable_slot (STB_LOCAL)
ffffffff815b3135-ffffffff815b316b: enable_slot.cold (STB_LOCAL)
ffffffff815b6970-ffffffff815b69bc: enable_slot (STB_LOCAL)
ffffffff815b74a0-ffffffff815b7950: enable_slot (STB_LOCAL)
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
