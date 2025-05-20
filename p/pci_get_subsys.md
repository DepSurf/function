# Function: <code>pci_get_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143abb0)
Location: drivers/pci/search.c:294
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8143abb0-ffffffff8143ac0a: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486bb9)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff81486ad0-ffffffff81486b2a: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8369)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff814a8280-ffffffff814a82da: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b22f8)
Location: drivers/pci/search.c:302
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff814b2220-ffffffff814b227a: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f19e8)
Location: drivers/pci/search.c:302
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff814f1910-ffffffff814f196a: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521c92)
Location: drivers/pci/search.c:303
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff81521ba0-ffffffff81521bfa: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537ac2)
Location: drivers/pci/search.c:303
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff815379d0-ffffffff81537a2a: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156745b)
Location: drivers/pci/search.c:299
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff81567370-ffffffff815673ce: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815887ab)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff815886c0-ffffffff8158871e: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f45b)
Location: drivers/pci/search.c:304
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8162f2a0-ffffffff8162f2fe: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654aeb)
Location: drivers/pci/search.c:304
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff81654930-ffffffff8165498e: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81637482)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff81637550-ffffffff816375ed: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a76f2)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff816a77c0-ffffffff816a7865: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca121)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff817ca210-ffffffff817ca2c2: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e7bd1)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff818e7cd0-ffffffff818e7d82: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b1f3)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8192b2e0-ffffffff8192b392: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81973a73)
Location: drivers/pci/search.c:301
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81973c30-ffffffff81973ce2: pci_get_subsys (STB_GLOBAL)
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
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ecd50)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffff8000106ecc18-ffff8000106ecc98: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887fcc)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
c0887e7c-c0887f00: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868c10)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
c000000000868a90-c000000000868b18: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1bb8)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffe0004c1aea-ffffffe0004c1b48: pci_get_subsys (STB_GLOBAL)
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
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c63b)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8157c550-ffffffff8157c5ae: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b40b)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8156b320-ffffffff8156b37e: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c4fb)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8157c410-ffffffff8157c46e: pci_get_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_subsys(unsigned int vendor, unsigned int device, unsigned int ss_vendor, unsigned int ss_device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815969ab)
Location: drivers/pci/search.c:298
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff815968c0-ffffffff8159691e: pci_get_subsys (STB_GLOBAL)
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
