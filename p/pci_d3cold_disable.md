# Function: <code>pci_d3cold_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481760)
Location: drivers/pci/pci.c:2329
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81481760-ffffffff81481787: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4690)
Location: drivers/pci/pci.c:2367
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff814a4690-ffffffff814a46b5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae750)
Location: drivers/pci/pci.c:2384
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff814ae750-ffffffff814ae776: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814edb20)
Location: drivers/pci/pci.c:2393
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff814edb20-ffffffff814edb46: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d750)
Location: drivers/pci/pci.c:2468
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff8151d750-ffffffff8151d775: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532e90)
Location: drivers/pci/pci.c:2658
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81532e90-ffffffff81532eb5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562600)
Location: drivers/pci/pci.c:2773
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81562600-ffffffff81562625: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815837a0)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff815837a0-ffffffff815837c5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a300)
Location: drivers/pci/pci.c:2839
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff8162a300-ffffffff8162a325: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650760)
Location: drivers/pci/pci.c:3006
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81650760-ffffffff81650785: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633370)
Location: drivers/pci/pci.c:3036
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81633370-ffffffff81633395: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3510)
Location: drivers/pci/pci.c:3078
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff816a3510-ffffffff816a3535: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5760)
Location: drivers/pci/pci.c:3165
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff817c5760-ffffffff817c5795: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e2870)
Location: drivers/pci/pci.c:3115
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff818e2870-ffffffff818e28a5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925cb0)
Location: drivers/pci/pci.c:3153
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff81925cb0-ffffffff81925ce5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e430)
Location: drivers/pci/pci.c:3266
Inline: True
```
**Symbols:**

```
ffffffff8196e430-ffffffff8196e465: pci_d3cold_disable (STB_GLOBAL)
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
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7780)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffff8000106e7780-ffff8000106e77c8: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882874)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
c0882874-c08828a4: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861f80)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
c000000000861f80-c000000000861fa8: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bde5a)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffe0004bde5a-ffffffe0004bdea0: pci_d3cold_disable (STB_GLOBAL)
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
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577cc0)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81577cc0-ffffffff81577ce5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81566400)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81566400-ffffffff81566425: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815774f0)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff815774f0-ffffffff81577515: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_d3cold_disable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815919b0)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff815919b0-ffffffff815919d5: pci_d3cold_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
