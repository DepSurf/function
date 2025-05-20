# Function: <code>pci_scan_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81432420)
Location: drivers/pci/probe.c:818
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81432420-ffffffff81432a99: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147dc40)
Location: drivers/pci/probe.c:827
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8147dc40-ffffffff8147e2d9: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149f300)
Location: drivers/pci/probe.c:946
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8149f300-ffffffff8149f999: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a9110)
Location: drivers/pci/probe.c:972
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814a9110-ffffffff814a9741: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8bb3)
Location: drivers/pci/probe.c:1209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff814e8790-ffffffff814e87a5: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815181f0)
Location: drivers/pci/probe.c:1286
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81517d70-ffffffff81517d85: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152dc70)
Location: drivers/pci/probe.c:1286
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8152d7f0-ffffffff8152d805: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155c3f0)
Location: drivers/pci/probe.c:1389
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8155bf70-ffffffff8155bf85: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157d4c0)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8157d040-ffffffff8157d055: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622ab0)
Location: drivers/pci/probe.c:1439
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81622630-ffffffff81622645: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816496a0)
Location: drivers/pci/probe.c:1458
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81649220-ffffffff81649235: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162c260)
Location: drivers/pci/probe.c:1501
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8162bde0-ffffffff8162bdf5: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169b730)
Location: drivers/pci/probe.c:1510
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8169b2b0-ffffffff8169b2c5: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bcf08)
Location: drivers/pci/probe.c:1491
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff817bca80-ffffffff817bcaa4: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8ea8)
Location: drivers/pci/probe.c:1497
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff818d89e0-ffffffff818d8a04: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c1e8)
Location: drivers/pci/probe.c:1500
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8191bd20-ffffffff8191bd44: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964618)
Location: drivers/pci/probe.c:1511
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81964150-ffffffff81964174: pci_scan_bridge (STB_GLOBAL)
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
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0c68)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffff8000106e0720-ffff8000106e0770: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087c9d8)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
```
**Symbols:**

```
c087c4a4-c087c4d4: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000859d90)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
```
**Symbols:**

```
c0000000008596d0-c0000000008596ec: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b89a2)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
```
**Symbols:**

```
ffffffe0004b84e0-ffffffe0004b8524: pci_scan_bridge (STB_GLOBAL)
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
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815719e0)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81571560-ffffffff81571575: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81560140)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8155fcc0-ffffffff8155fcd5: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571210)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81570d90-ffffffff81570da5: pci_scan_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_scan_bridge(struct pci_bus *bus, struct pci_dev *dev, int max, int pass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158b6f0)
Location: drivers/pci/probe.c:1391
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8158b270-ffffffff8158b285: pci_scan_bridge (STB_GLOBAL)
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
