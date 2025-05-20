# Function: <code>pci_setup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814310f0)
Location: drivers/pci/probe.c:1191
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814310f0-ffffffff81431560: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147c7a0)
Location: drivers/pci/probe.c:1203
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8147c7a0-ffffffff8147cc70: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149dd00)
Location: drivers/pci/probe.c:1324
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8149dd00-ffffffff8149e1d0: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a7ba0)
Location: drivers/pci/probe.c:1396
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a7ba0-ffffffff814a80f8: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e64f0)
Location: drivers/pci/probe.c:1438
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814e64f0-ffffffff814e6a48: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81515980)
Location: drivers/pci/probe.c:1562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81515980-ffffffff81515fa3: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152b100)
Location: drivers/pci/probe.c:1606
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8152b100-ffffffff8152b781: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1707
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8155cbde-ffffffff8155d29a: pci_setup_device.cold (STB_LOCAL)
ffffffff8155a3f0-ffffffff8155a534: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157dc95-ffffffff8157e354: pci_setup_device.cold (STB_LOCAL)
ffffffff8157b480-ffffffff8157b5c4: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1769
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff816233ad-ffffffff81623907: pci_setup_device.cold (STB_LOCAL)
ffffffff81621020-ffffffff81621164: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1772
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81bf7593-ffffffff81bf7611: pci_setup_device.cold (STB_LOCAL)
ffffffff816476c0-ffffffff81647cd1: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1815
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81be935f-ffffffff81be93dd: pci_setup_device.cold (STB_LOCAL)
ffffffff81629fb0-ffffffff8162a6f8: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1844
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81ce378f-ffffffff81ce3d83: pci_setup_device.cold (STB_LOCAL)
ffffffff816999b0-ffffffff81699bdf: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1817
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81eaa2f8-ffffffff81eaa7d6: pci_setup_device.cold (STB_LOCAL)
ffffffff817bafb0-ffffffff817bb1cd: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1823
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8208ef64-ffffffff8208ef79: pci_setup_device.cold (STB_LOCAL)
ffffffff818d6470-ffffffff818d6b5f: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1831
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8210f2ac-ffffffff8210f2c1: pci_setup_device.cold (STB_LOCAL)
ffffffff819196e0-ffffffff81919dd1: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1879
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff821ecf54-ffffffff821ecf69: pci_setup_device.cold (STB_LOCAL)
ffffffff81961a60-ffffffff819621d8: pci_setup_device (STB_GLOBAL)
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
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106de2d0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffff8000106de2d0-ffff8000106de9e8: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0879f34)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c0879f34-c087a6ac: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008569c0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c0000000008569c0-c000000000857298: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b64da)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004b64da-ffffffe0004b6bca: pci_setup_device (STB_GLOBAL)
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
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815721b5-ffffffff81572874: pci_setup_device.cold (STB_LOCAL)
ffffffff8156f9a0-ffffffff8156fae4: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81560915-ffffffff81560fd4: pci_setup_device.cold (STB_LOCAL)
ffffffff8155e100-ffffffff8155e244: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815719e5-ffffffff815720a4: pci_setup_device.cold (STB_LOCAL)
ffffffff8156f1d0-ffffffff8156f314: pci_setup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_setup_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1721
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8158bec5-ffffffff8158c584: pci_setup_device.cold (STB_LOCAL)
ffffffff815896b0-ffffffff815897f4: pci_setup_device (STB_GLOBAL)
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
