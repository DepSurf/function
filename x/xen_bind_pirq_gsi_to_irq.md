# Function: <code>xen_bind_pirq_gsi_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8cf0)
Location: drivers/xen/events/events_base.c:644
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff814c8cf0-ffffffff814c8f62: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519810)
Location: drivers/xen/events/events_base.c:655
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81519810-ffffffff81519a72: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545ce0)
Location: drivers/xen/events/events_base.c:654
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81545ce0-ffffffff81545f42: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559b20)
Location: drivers/xen/events/events_base.c:646
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81559b20-ffffffff81559d6b: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bdf70)
Location: drivers/xen/events/events_base.c:646
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff815bdf70-ffffffff815be1bb: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:644
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff815f75dc-ffffffff815f75f9: xen_bind_pirq_gsi_to_irq.cold.24 (STB_LOCAL)
ffffffff815f65c0-ffffffff815f67f6: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:644
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81612697-ffffffff816126b4: xen_bind_pirq_gsi_to_irq.cold.23 (STB_LOCAL)
ffffffff81611660-ffffffff8161188e: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:645
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81646497-ffffffff816464b5: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81645430-ffffffff8164563f: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:645
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8166897a-ffffffff81668998: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff816679d0-ffffffff81667bdf: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:659
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81718a9c-ffffffff81718aba: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81717ad0-ffffffff81717d33: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:980
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81c04fad-ffffffff81c04fcb: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81735060-ffffffff817352c4: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1017
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81bf6bf6-ffffffff81bf6c14: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81718670-ffffffff817188d5: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1017
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81cf58a9-ffffffff81cf58c7: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81796180-ffffffff81796411: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1017
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_register_pirq
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81ebd9e8-ffffffff81ebda05: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff818cf010-ffffffff818cf2b9: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a206e0)
Location: drivers/xen/events/events_base.c:1019
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_register_pirq
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81a206e0-ffffffff81a209a8: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69a70)
Location: drivers/xen/events/events_base.c:1012
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_register_pirq
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81a69a70-ffffffff81a69d38: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abbe00)
Location: drivers/xen/events/events_base.c:1017
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_register_pirq
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81abbe00-ffffffff81abc072: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
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
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108318d0)
Location: drivers/xen/events/events_base.c:645
Inline: False
```
**Symbols:**

```
ffff8000108318d0-ffff800010831adc: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:649
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8162e7aa-ffffffff8162e7c8: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff8162d700-ffffffff8162d90f: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:645
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8165c7ba-ffffffff8165c7d8: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff8165b810-ffffffff8165ba1f: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xen_bind_pirq_gsi_to_irq(unsigned int gsi, unsigned int pirq, int shareable, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:645
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81676daa-ffffffff81676dc8: xen_bind_pirq_gsi_to_irq.cold (STB_LOCAL)
ffffffff81675e00-ffffffff8167600f: xen_bind_pirq_gsi_to_irq (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
