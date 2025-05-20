# Function: <code>__pci_bus_assign_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814403c0)
Location: drivers/pci/setup-bus.c:1385
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814403c0-ffffffff814405de: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148c290)
Location: drivers/pci/setup-bus.c:1389
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8148c290-ffffffff8148c4bb: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ada80)
Location: drivers/pci/setup-bus.c:1390
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814ada80-ffffffff814adcab: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b7e20)
Location: drivers/pci/setup-bus.c:1381
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814b7e20-ffffffff814b8049: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f7f70)
Location: drivers/pci/setup-bus.c:1381
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814f7f70-ffffffff814f8199: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81528ae0)
Location: drivers/pci/setup-bus.c:1376
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81528ae0-ffffffff81528cfe: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153e980)
Location: drivers/pci/setup-bus.c:1378
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8153e980-ffffffff8153eb9e: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8156eadb-ffffffff8156eae8: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff8156de00-ffffffff8156dff5: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8158faae-ffffffff8158fabb: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff8158ede0-ffffffff8158efd5: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1378
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff816375e7-ffffffff816375f4: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff816368c0-ffffffff81636a45: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1379
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81bf8a50-ffffffff81bf8a5d: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff8165b980-ffffffff8165bb05: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1379
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81bea8aa-ffffffff81bea8b7: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff8163dec0-ffffffff8163e0a2: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1379
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81ce572c-ffffffff81ce5739: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff816aea00-ffffffff816aec01: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1379
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81eac1fc-ffffffff81eac209: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff817d1e70-ffffffff817d2086: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f2300)
Location: drivers/pci/setup-bus.c:1379
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff818f2300-ffffffff818f2504: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81935710)
Location: drivers/pci/setup-bus.c:1372
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81935710-ffffffff8193592b: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197e4b0)
Location: drivers/pci/setup-bus.c:1382
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8197e4b0-ffffffff8197e6dd: __pci_bus_assign_resources (STB_GLOBAL)
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
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f40c0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffff8000106f40c0-ffff8000106f4300: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088eb64)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c088eb64-c088ed90: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000872720)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c000000000872720-c0000000008729e0: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c72c4)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffe0004c72c4-ffffffe0004c7482: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81583932-ffffffff8158393f: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff81582c60-ffffffff81582e55: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8157270e-ffffffff8157271b: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff81571a40-ffffffff81571c35: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff815837fe-ffffffff8158380b: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff81582b30-ffffffff81582d25: __pci_bus_assign_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __pci_bus_assign_resources(const struct pci_bus *bus, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1341
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8159dcae-ffffffff8159dcbb: __pci_bus_assign_resources.cold (STB_LOCAL)
ffffffff8159cfe0-ffffffff8159d1d5: __pci_bus_assign_resources (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
