# Function: <code>__pci_hp_initialize</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154e045)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8154d5e0-ffffffff8154d633: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157de65)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8157d420-ffffffff8157d473: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f8c5)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8159ee80-ffffffff8159eed3: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647790)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:init_slot
```
**Symbols:**

```
ffffffff81647790-ffffffff816477e6: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166c910)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:init_slot
```
**Symbols:**

```
ffffffff8166c910-ffffffff8166c966: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164eeb0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8164eeb0-ffffffff8164ef06: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c0bc0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff816c0bc0-ffffffff816c0c16: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6300)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff817e6300-ffffffff817e6368: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b140)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8190b140-ffffffff8190b1a8: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194e7c0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8194e7c0-ffffffff8194e828: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81997bf0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81997bf0-ffffffff81997c58: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707e54)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffff800010707240-ffff8000107072d4: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000088069c)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
**Symbols:**

```
c00000000087f450-c00000000087f500: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5782)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffe0004d4da6-ffffffe0004d4e1a: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815930d5)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81592690-ffffffff815926e3: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81582265)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81581820-ffffffff81581873: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593615)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81592bd0-ffffffff81592c23: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_initialize(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ada95)
Location: drivers/pci/hotplug/pci_hotplug_core.c:438
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff815ad050-ffffffff815ad0a3: __pci_hp_initialize (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
