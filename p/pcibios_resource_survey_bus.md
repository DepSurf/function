# Function: <code>pcibios_resource_survey_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f8b0)
Location: drivers/pci/bus.c:272
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff816f6540-ffffffff816f659a: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8175b1b0)
Location: drivers/pci/bus.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8175b1b0-ffffffff8175b20a: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81787730)
Location: drivers/pci/bus.c:301
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81787730-ffffffff8178778a: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a60e0)
Location: drivers/pci/bus.c:301
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff817a6930-ffffffff817a698a: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4f20)
Location: drivers/pci/bus.c:301
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8181db90-ffffffff8181dbea: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81514400)
Location: drivers/pci/bus.c:300
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81867dc0-ffffffff81867e1d: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529b60)
Location: drivers/pci/bus.c:300
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81887e40-ffffffff81887e9d: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81558d70)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818d27a3-ffffffff818d27ff: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8157a310)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81904b53-ffffffff81904baf: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161f430)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81bb5121-ffffffff81bb517d: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81645c20)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81c33fbf-ffffffff81c3401b: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81628960)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81c26354-ffffffff81c263b0: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816982e0)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81d440da-ffffffff81d44136: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b95c0)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81f10f3b-ffffffff81f10f9f: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d41a0)
Location: drivers/pci/bus.c:303
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff82015d20-ffffffff82015de6: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff819173f0)
Location: drivers/pci/bus.c:324
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff82096100-ffffffff820961c6: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f500)
Location: drivers/pci/bus.c:324
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8216d610-ffffffff8216d6d6: pcibios_resource_survey_bus (STB_GLOBAL)
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
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dcc00)
Location: drivers/pci/bus.c:299
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000106dcc00-ffff8000106dcc18: pcibios_resource_survey_bus (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0878800)
Location: drivers/pci/bus.c:299
Inline: True
```
**Symbols:**

```
c0878800-c0878818: pcibios_resource_survey_bus (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c000000000854d20)
Location: drivers/pci/bus.c:299
Inline: False
```
**Symbols:**

```
c000000000854d20-c000000000854d2c: pcibios_resource_survey_bus (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b5086)
Location: drivers/pci/bus.c:299
Inline: True
```
**Symbols:**

```
ffffffe0004b5086-ffffffe0004b50a0: pcibios_resource_survey_bus (STB_WEAK)
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
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e820)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818a3f83-ffffffff818a3fdf: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8155cf90)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8185f6f3-ffffffff8185f74f: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e060)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818f5573-ffffffff818f55cf: pcibios_resource_survey_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_resource_survey_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81588540)
Location: drivers/pci/bus.c:299
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81916613-ffffffff8191666f: pcibios_resource_survey_bus (STB_GLOBAL)
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
