# Function: <code>__pci_hp_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c460)
Location: drivers/pci/hotplug/pci_hotplug_core.c:423
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8144c460-ffffffff8144c819: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498b70)
Location: drivers/pci/hotplug/pci_hotplug_core.c:421
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81498b70-ffffffff81498f36: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba760)
Location: drivers/pci/hotplug/pci_hotplug_core.c:418
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff814ba760-ffffffff814bab26: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c4f80)
Location: drivers/pci/hotplug/pci_hotplug_core.c:418
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff814c4f80-ffffffff814c5315: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81505510)
Location: drivers/pci/hotplug/pci_hotplug_core.c:418
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81505510-ffffffff815058a5: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81536a8b-ffffffff81536ad5: __pci_hp_register.cold.13 (STB_LOCAL)
ffffffff81536420-ffffffff815367cd: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154e040)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8154e040-ffffffff8154e0db: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157de60)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8157de60-ffffffff8157def3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f8c0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8159f8c0-ffffffff8159f953: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81648250)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81648250-ffffffff816482e3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166d3d0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8166d3d0-ffffffff8166d463: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f710)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8164f710-ffffffff8164f7a3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c1460)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff816c1460-ffffffff816c14f3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6c60)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff817e6c60-ffffffff817e6d1f: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190bbe0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8190bbe0-ffffffff8190bc9f: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194f260)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff8194f260-ffffffff8194f315: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81998690)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81998690-ffffffff81998745: __pci_hp_register (STB_GLOBAL)
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
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707e20)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffff800010707e20-ffff800010707ef4: __pci_hp_register (STB_GLOBAL)
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
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c000000000880680)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
```
**Symbols:**

```
c000000000880680-c00000000088077c: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5758)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
```
**Symbols:**

```
ffffffe0004d5758-ffffffe0004d57f4: __pci_hp_register (STB_GLOBAL)
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
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815930d0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff815930d0-ffffffff81593163: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81582260)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81582260-ffffffff815822f3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593610)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff81593610-ffffffff815936a3: __pci_hp_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pci_hp_register(struct hotplug_slot *slot, struct pci_bus *bus, int devnr, const char *name, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ada90)
Location: drivers/pci/hotplug/pci_hotplug_core.c:404
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
**Symbols:**

```
ffffffff815ada90-ffffffff815adb23: __pci_hp_register (STB_GLOBAL)
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
