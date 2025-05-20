# Function: <code>pcibios_disable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8175f660)
Location: drivers/pci/pci.c:1558
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8175f660-ffffffff8175f683: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8178bba0)
Location: drivers/pci/pci.c:1583
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8178bba0-ffffffff8178bbc3: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817aab67)
Location: drivers/pci/pci.c:1581
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff817aab20-ffffffff817aab44: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8182205b)
Location: drivers/pci/pci.c:1584
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff81822010-ffffffff81822037: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8186c31b)
Location: drivers/pci/pci.c:1639
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8186c2d0-ffffffff8186c2f6: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8188c3fb)
Location: drivers/pci/pci.c:1812
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8188c3b0-ffffffff8188c3d6: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561b60)
Location: drivers/pci/pci.c:1887
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff818d6cf0-ffffffff818d6d16: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582d00)
Location: drivers/pci/pci.c:1883
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff81909070-ffffffff81909096: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81bb9978)
Location: drivers/pci/pci.c:1953
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
```
**Symbols:**

```
ffffffff81bb9930-ffffffff81bb9956: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81bce288)
Location: drivers/pci/pci.c:2089
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
```
**Symbols:**

```
ffffffff81bce240-ffffffff81bce266: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81bc1c48)
Location: drivers/pci/pci.c:2119
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
```
**Symbols:**

```
ffffffff81bc1c00-ffffffff81bc1c26: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81c92258)
Location: drivers/pci/pci.c:2150
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
```
**Symbols:**

```
ffffffff81c92210-ffffffff81c92236: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81e418d0)
Location: drivers/pci/pci.c:2210
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff81e41870-ffffffff81e418a6: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8201bf30)
Location: drivers/pci/pci.c:2184
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8201bec0-ffffffff8201bef6: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8209c5d0)
Location: drivers/pci/pci.c:2222
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8209c560-ffffffff8209c596: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff82173db0)
Location: drivers/pci/pci.c:2319
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff82173d40-ffffffff82173d76: pcibios_disable_device (STB_GLOBAL)
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
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1883
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffff8000106e6a40-ffff8000106e6a58: pcibios_disable_device (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1883
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
c0881d08-c0881d20: pcibios_disable_device (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006e470)
Location: arch/powerpc/kernel/pci-common.c:1463
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
c00000000006e470-c00000000006e4c0: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1883
Inline: False
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffe0004bd3b2-ffffffe0004bd3cc: pcibios_disable_device (STB_WEAK)
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
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577220)
Location: drivers/pci/pci.c:1883
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff818a8430-ffffffff818a8456: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565980)
Location: drivers/pci/pci.c:1883
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff81862e40-ffffffff81862e66: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576a50)
Location: drivers/pci/pci.c:1883
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff818f9a90-ffffffff818f9ab6: pcibios_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pcibios_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590f30)
Location: drivers/pci/pci.c:1883
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_release_device
Direct callers:
  - drivers/pci/pci.c:do_pci_disable_device
```
**Symbols:**

```
ffffffff8191abf0-ffffffff8191ac16: pcibios_disable_device (STB_GLOBAL)
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
