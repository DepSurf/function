# Function: <code>usb_amd_quirk_pll_check</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817e5ff0)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817e5ff0-ffffffff817e6007: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81816eb0)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81816eb0-ffffffff81816ec7: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818e7f30)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff818e7f30-ffffffff818e7f47: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818f0f10)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff818f0f10-ffffffff818f0f27: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818d4710)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff818d4710-ffffffff818d4727: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff81d1e7cd-ffffffff81d1e7e8: usb_amd_quirk_pll_check.cold (STB_LOCAL)
ffffffff8196fc70-ffffffff8196fc96: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff81eea256-ffffffff81eea271: usb_amd_quirk_pll_check.cold (STB_LOCAL)
ffffffff81aca080-ffffffff81aca0ae: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff820a527c-ffffffff820a5297: usb_amd_quirk_pll_check.cold (STB_LOCAL)
ffffffff81c545a0-ffffffff81c545ce: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:321
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff821267a1-ffffffff821267bc: usb_amd_quirk_pll_check.cold (STB_LOCAL)
ffffffff81cbbb00-ffffffff81cbbb2e: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:323
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
```
**Symbols:**

```
ffffffff82207faa-ffffffff82207fc5: usb_amd_quirk_pll_check.cold (STB_LOCAL)
ffffffff81d70870-ffffffff81d7089e: usb_amd_quirk_pll_check (STB_GLOBAL)
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
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a508f8)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffff800010a508f8-ffff800010a5091c: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b221e8)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
c0b221e8-c0b22210: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b180f0)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
c000000000b180f0-c000000000b18128: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066c81a)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffe00066c81a-ffffffe00066c844: usb_amd_quirk_pll_check (STB_GLOBAL)
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
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817cf290)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817cf290-ffffffff817cf2a7: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817ad1c0)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817ad1c0-ffffffff817ad1d7: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8180bd30)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8180bd30-ffffffff8180bd47: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool usb_amd_quirk_pll_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81825e40)
Location: drivers/usb/host/pci-quirks.c:320
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81825e40-ffffffff81825e57: usb_amd_quirk_pll_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
