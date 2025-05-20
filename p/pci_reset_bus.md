# Function: <code>pci_reset_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814386b0)
Location: drivers/pci/pci.c:4178
Inline: True
```
**Symbols:**

```
ffffffff814386b0-ffffffff81438721: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484380)
Location: drivers/pci/pci.c:4499
Inline: True
```
**Symbols:**

```
ffffffff81484380-ffffffff814843f1: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5ae0)
Location: drivers/pci/pci.c:4537
Inline: True
```
**Symbols:**

```
ffffffff814a5ae0-ffffffff814a5b51: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af860)
Location: drivers/pci/pci.c:4695
Inline: False
```
**Symbols:**

```
ffffffff814af860-ffffffff814af8db: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eedc0)
Location: drivers/pci/pci.c:4719
Inline: True
```
**Symbols:**

```
ffffffff814eedc0-ffffffff814eee06: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_reset_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ebc0)
Location: drivers/pci/pci.c:4968
Inline: False
```
**Symbols:**

```
ffffffff8151ebc0-ffffffff8151ec3b: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815349a0)
Location: drivers/pci/pci.c:5296
Inline: True
```
**Symbols:**

```
ffffffff815349a0-ffffffff81534c39: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563e80)
Location: drivers/pci/pci.c:5392
Inline: True
```
**Symbols:**

```
ffffffff81563e80-ffffffff815640e7: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585160)
Location: drivers/pci/pci.c:5522
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81585160-ffffffff815853c7: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162be00)
Location: drivers/pci/pci.c:5552
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8162be00-ffffffff8162beba: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651b30)
Location: drivers/pci/pci.c:5620
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff81651b30-ffffffff81651bea: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816345a0)
Location: drivers/pci/pci.c:5669
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff816345a0-ffffffff816346de: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a43d0)
Location: drivers/pci/pci.c:5859
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff816a43d0-ffffffff816a450e: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c67f0)
Location: drivers/pci/pci.c:5955
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_hot_reset
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff817c67f0-ffffffff817c693e: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e3bd0)
Location: drivers/pci/pci.c:5892
Inline: True
```
**Symbols:**

```
ffffffff818e3bd0-ffffffff818e3d27: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819272d0)
Location: drivers/pci/pci.c:6014
Inline: True
```
**Symbols:**

```
ffffffff819272d0-ffffffff8192740c: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196fa70)
Location: drivers/pci/pci.c:6124
Inline: True
```
**Symbols:**

```
ffffffff8196fa70-ffffffff8196fbac: pci_reset_bus (STB_GLOBAL)
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
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9848)
Location: drivers/pci/pci.c:5522
Inline: True
```
**Symbols:**

```
ffff8000106e9848-ffff8000106e9ad4: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08847c0)
Location: drivers/pci/pci.c:5522
Inline: True
```
**Symbols:**

```
c08847c0-c0884a74: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864880)
Location: drivers/pci/pci.c:5522
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000864880-c000000000864b84: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bfb9a)
Location: drivers/pci/pci.c:5522
Inline: True
```
**Symbols:**

```
ffffffe0004bfb9a-ffffffe0004bfdd0: pci_reset_bus (STB_GLOBAL)
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
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579680)
Location: drivers/pci/pci.c:5522
Inline: True
```
**Symbols:**

```
ffffffff81579680-ffffffff815798e7: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567dc0)
Location: drivers/pci/pci.c:5522
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81567dc0-ffffffff81568027: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578eb0)
Location: drivers/pci/pci.c:5522
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81578eb0-ffffffff81579117: pci_reset_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_reset_bus(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593360)
Location: drivers/pci/pci.c:5522
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81593360-ffffffff815935bd: pci_reset_bus (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_bus *bus</code>
</li>
</ul>
</details>
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
