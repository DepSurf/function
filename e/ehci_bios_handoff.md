# Function: <code>ehci_bios_handoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81630a53)
Location: drivers/usb/host/pci-quirks.c:678
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816916bc)
Location: drivers/usb/host/pci-quirks.c:678
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816bf76c)
Location: drivers/usb/host/pci-quirks.c:677
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816d415c)
Location: drivers/usb/host/pci-quirks.c:739
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8174084c)
Location: drivers/usb/host/pci-quirks.c:740
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817813c7)
Location: drivers/usb/host/pci-quirks.c:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817a7bed)
Location: drivers/usb/host/pci-quirks.c:843
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817e6da5)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81817c65)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ehci_bios_handoff(struct pci_dev *pdev, void *op_reg_base, u32 cap, u8 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:855
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
**Symbols:**

```
ffffffff818e8720-ffffffff818e885b: ehci_bios_handoff (STB_LOCAL)
ffffffff818e9227-ffffffff818e925b: ehci_bios_handoff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ehci_bios_handoff(struct pci_dev *pdev, void *op_reg_base, u32 cap, u8 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:855
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
**Symbols:**

```
ffffffff818f1700-ffffffff818f183b: ehci_bios_handoff (STB_LOCAL)
ffffffff81c1ffad-ffffffff81c1ffe1: ehci_bios_handoff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ehci_bios_handoff(struct pci_dev *pdev, void *op_reg_base, u32 cap, u8 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:855
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
**Symbols:**

```
ffffffff818d4f00-ffffffff818d503b: ehci_bios_handoff (STB_LOCAL)
ffffffff81c11f96-ffffffff81c11fca: ehci_bios_handoff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ehci_bios_handoff(struct pci_dev *pdev, void *op_reg_base, u32 cap, u8 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:855
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
**Symbols:**

```
ffffffff8196f7e0-ffffffff8196f918: ehci_bios_handoff (STB_LOCAL)
ffffffff81d1e76f-ffffffff81d1e7a3: ehci_bios_handoff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81aca771)
Location: drivers/usb/host/pci-quirks.c:855
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81c54d5f)
Location: drivers/usb/host/pci-quirks.c:855
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc2df)
Location: drivers/usb/host/pci-quirks.c:853
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d7104f)
Location: drivers/usb/host/pci-quirks.c:865
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a513e4)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b23154)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b19cd0)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066d6a4)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817d0045)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817adf75)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8180cae5)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81826bf5)
Location: drivers/usb/host/pci-quirks.c:852
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
