# Function: <code>ohci_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81642c30)
Location: drivers/usb/host/ohci-hcd.c:1001
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81642c30-ffffffff81642e21: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816a3710)
Location: drivers/usb/host/ohci-hcd.c:1000
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff816a3710-ffffffff816a390c: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816d1810)
Location: drivers/usb/host/ohci-hcd.c:1000
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff816d1810-ffffffff816d1a0c: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e5e60)
Location: drivers/usb/host/ohci-hcd.c:1001
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff816e5e60-ffffffff816e606a: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81752690)
Location: drivers/usb/host/ohci-hcd.c:1005
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81752690-ffffffff8175289a: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81792db0)
Location: drivers/usb/host/ohci-hcd.c:1006
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81792db0-ffffffff81792fb6: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b9380)
Location: drivers/usb/host/ohci-hcd.c:1006
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff817b9380-ffffffff817b9586: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff817f9b69-ffffffff817f9b8a: ohci_restart.cold (STB_LOCAL)
ffffffff817f7e90-ffffffff817f807f: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff8182a9a3-ffffffff8182a9c4: ohci_restart.cold (STB_LOCAL)
ffffffff81828cf0-ffffffff81828edf: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff818fc802-ffffffff818fc823: ohci_restart.cold (STB_LOCAL)
ffffffff818fb800-ffffffff818fb9e4: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1032
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81c205c8-ffffffff81c205e9: ohci_restart.cold (STB_LOCAL)
ffffffff81904360-ffffffff81904544: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1032
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81c12631-ffffffff81c12652: ohci_restart.cold (STB_LOCAL)
ffffffff818e7ad0-ffffffff818e7cd5: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1032
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81d1f0d6-ffffffff81d1f0f6: ohci_restart.cold (STB_LOCAL)
ffffffff81983eb0-ffffffff819840c4: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1030
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81eeabf6-ffffffff81eeac16: ohci_restart.cold (STB_LOCAL)
ffffffff81adf400-ffffffff81adf607: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6a990)
Location: drivers/usb/host/ohci-hcd.c:1030
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81c6a990-ffffffff81c6abcc: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd1d80)
Location: drivers/usb/host/ohci-hcd.c:1030
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81cd1d80-ffffffff81cd1fbc: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d86d40)
Location: drivers/usb/host/ohci-hcd.c:1030
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81d86d40-ffffffff81d86f7c: ohci_restart (STB_GLOBAL)
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
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a64dd8)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffff800010a64dd8-ffff800010a65034: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b35f24)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
c0b35f24-c0b36140: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b34350)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
c000000000b34350-c000000000b34648: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe00067f26a)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffe00067f26a-ffffffe00067f49e: ohci_restart (STB_GLOBAL)
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
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff817e2d83-ffffffff817e2da4: ohci_restart.cold (STB_LOCAL)
ffffffff817e10d0-ffffffff817e12bf: ohci_restart (STB_GLOBAL)
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
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff8181f823-ffffffff8181f844: ohci_restart.cold (STB_LOCAL)
ffffffff8181db70-ffffffff8181dd5f: ohci_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ohci_restart(struct ohci_hcd *ohci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-hcd.c:1028
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
```
**Symbols:**

```
ffffffff81839796-ffffffff818397b6: ohci_restart.cold (STB_LOCAL)
ffffffff81837880-ffffffff81837a57: ohci_restart (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
