# Function: <code>usb_amd_find_chipset_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8162fbf0)
Location: drivers/usb/host/pci-quirks.c:170
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8162fbf0-ffffffff8162fee1: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81690860)
Location: drivers/usb/host/pci-quirks.c:170
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81690860-ffffffff81690b4f: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816be910)
Location: drivers/usb/host/pci-quirks.c:169
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff816be910-ffffffff816bebff: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816d31f0)
Location: drivers/usb/host/pci-quirks.c:186
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff816d31f0-ffffffff816d350c: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8173f8b0)
Location: drivers/usb/host/pci-quirks.c:187
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8173f8b0-ffffffff8173fbcc: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81781824-ffffffff8178185a: usb_amd_find_chipset_info.cold.7 (STB_LOCAL)
ffffffff81780280-ffffffff81780580: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int usb_amd_find_chipset_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817a8026-ffffffff817a805c: usb_amd_find_chipset_info.cold.7 (STB_LOCAL)
ffffffff817a6a80-ffffffff817a6d96: usb_amd_find_chipset_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff817e5ca0-ffffffff817e5f83: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff817e71a2-ffffffff817e71cc: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81816b60-ffffffff81816e43: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81818062-ffffffff8181808c: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff818e7cf0-ffffffff818e7ec8: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff818e91e4-ffffffff818e920e: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff818f0cd0-ffffffff818f0ea8: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81c1ff6a-ffffffff81c1ff94: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff818d43c0-ffffffff818d46a3: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81c11f53-ffffffff81c11f7d: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff8196f920-ffffffff8196fc0a: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81d1e7a3-ffffffff81d1e7cd: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81ac9cf0-ffffffff81aca007: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81eea22c-ffffffff81eea256: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81c541b0)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81c541b0-ffffffff81c544f6: usb_amd_find_chipset_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbb780)
Location: drivers/usb/host/pci-quirks.c:207
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81cbb780-ffffffff81cbba57: usb_amd_find_chipset_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d704f0)
Location: drivers/usb/host/pci-quirks.c:209
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81d704f0-ffffffff81d707c7: usb_amd_find_chipset_info (STB_LOCAL)
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
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a50400)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffff800010a50400-ffff800010a507e8: usb_amd_find_chipset_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b21e44)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
c0b21e44-c0b22160: usb_amd_find_chipset_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b17c30)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
c000000000b17c30-c000000000b1800c: usb_amd_find_chipset_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066c4bc)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffe00066c4bc-ffffffe00066c798: usb_amd_find_chipset_info (STB_LOCAL)
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
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff817cef40-ffffffff817cf223: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff817d0442-ffffffff817d046c: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff817ace70-ffffffff817ad153: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff817ae372-ffffffff817ae39c: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff8180b9e0-ffffffff8180bcc3: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff8180cee2-ffffffff8180cf0c: usb_amd_find_chipset_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void usb_amd_find_chipset_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:204
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll_check
  - drivers/usb/host/pci-quirks.c:usb_amd_prefetch_quirk
  - drivers/usb/host/pci-quirks.c:usb_amd_hang_symptom_quirk
```
**Symbols:**

```
ffffffff81825af0-ffffffff81825dd3: usb_amd_find_chipset_info (STB_LOCAL)
ffffffff81826ff2-ffffffff8182701c: usb_amd_find_chipset_info.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
