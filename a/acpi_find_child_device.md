# Function: <code>acpi_find_child_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8147ece0)
Location: drivers/acpi/glue.c:104
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8147ece0-ffffffff8147edc7: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff814cd548)
Location: drivers/acpi/glue.c:104
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814cd548-ffffffff814cd62c: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff814ef489)
Location: drivers/acpi/glue.c:115
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814ef489-ffffffff814ef56d: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff814fc470)
Location: drivers/acpi/glue.c:115
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814fc470-ffffffff814fc563: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8153e290)
Location: drivers/acpi/glue.c:115
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8153e290-ffffffff8153e383: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815741c0)
Location: drivers/acpi/glue.c:115
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815741c0-ffffffff815742bc: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8158bde0)
Location: drivers/acpi/glue.c:115
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8158bde0-ffffffff8158bedc: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815bcbe0)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815bcbe0-ffffffff815bcce3: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815ddea0)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815ddea0-ffffffff815ddfa3: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816887a0)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff816887a0-ffffffff816888a3: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816a6370)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff816a6370-ffffffff816a6473: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff81689000)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff81689000-ffffffff81689103: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816fe440)
Location: drivers/acpi/glue.c:104
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff816fe440-ffffffff816fe543: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8182be90)
Location: drivers/acpi/glue.c:108
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8182be90-ffffffff8182bf62: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8195ee40)
Location: drivers/acpi/glue.c:205
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8195ee40-ffffffff8195eeb5: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819a53d0)
Location: drivers/acpi/glue.c:205
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff819a53d0-ffffffff819a5445: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819edd50)
Location: drivers/acpi/glue.c:205
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff819edd50-ffffffff819eddc5: acpi_find_child_device (STB_GLOBAL)
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
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffff80001076a1c0)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffff80001076a1c0-ffff80001076a308: acpi_find_child_device (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815d0380)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815d0380-ffffffff815d0483: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815b9f40)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
**Symbols:**

```
ffffffff815b9f40-ffffffff815ba043: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815d2180)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815d2180-ffffffff815d2283: acpi_find_child_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_device(struct acpi_device *parent, u64 address, bool check_children);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815ec040)
Location: drivers/acpi/glue.c:114
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815ec040-ffffffff815ec143: acpi_find_child_device (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
