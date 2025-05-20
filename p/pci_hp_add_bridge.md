# Function: <code>pci_hp_add_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug-pci.c (ffffffff81453610)
Location: drivers/pci/hotplug-pci.c:7
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff81453610-ffffffff814536bf: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug-pci.c (ffffffff8149feb0)
Location: drivers/pci/hotplug-pci.c:7
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff8149feb0-ffffffff8149ff5f: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug-pci.c (ffffffff814c1a30)
Location: drivers/pci/hotplug-pci.c:7
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814c1a30-ffffffff814c1adf: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug-pci.c (ffffffff814cc010)
Location: drivers/pci/hotplug-pci.c:7
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814cc010-ffffffff814cc0bd: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8b60)
Location: drivers/pci/probe.c:2903
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814e8b60-ffffffff814e8c17: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815181a0)
Location: drivers/pci/probe.c:3120
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff815181a0-ffffffff81518257: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152dc20)
Location: drivers/pci/probe.c:3246
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8152dc20-ffffffff8152dcd7: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155c3a0)
Location: drivers/pci/probe.c:3470
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8155c3a0-ffffffff8155c44c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157d470)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8157d470-ffffffff8157d51c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622a60)
Location: drivers/pci/probe.c:3256
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81622a60-ffffffff81622b0c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81649650)
Location: drivers/pci/probe.c:3264
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81649650-ffffffff816496fc: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162c210)
Location: drivers/pci/probe.c:3308
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8162c210-ffffffff8162c2b7: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169b6e0)
Location: drivers/pci/probe.c:3350
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8169b6e0-ffffffff8169b787: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bceb0)
Location: drivers/pci/probe.c:3321
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff817bceb0-ffffffff817bcf69: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8e50)
Location: drivers/pci/probe.c:3331
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff818d8e50-ffffffff818d8f0b: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c190)
Location: drivers/pci/probe.c:3345
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8191c190-ffffffff8191c24b: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819645c0)
Location: drivers/pci/probe.c:3394
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff819645c0-ffffffff8196467b: pci_hp_add_bridge (STB_GLOBAL)
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
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0c10)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffff8000106e0c10-ffff8000106e0cd0: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087c984)
Location: drivers/pci/probe.c:3204
Inline: False
```
**Symbols:**

```
c087c984-c087ca38: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000859d10)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
**Symbols:**

```
c000000000859d10-c000000000859e10: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b895e)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffe0004b895e-ffffffe0004b89fe: pci_hp_add_bridge (STB_GLOBAL)
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
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571990)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81571990-ffffffff81571a3c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815600f0)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff815600f0-ffffffff8156019c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815711c0)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff815711c0-ffffffff8157126c: pci_hp_add_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_hp_add_bridge(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158b6a0)
Location: drivers/pci/probe.c:3204
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8158b6a0-ffffffff8158b74c: pci_hp_add_bridge (STB_GLOBAL)
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
