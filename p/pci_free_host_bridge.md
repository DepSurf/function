# Function: <code>pci_free_host_bridge</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a63cb)
Location: drivers/pci/probe.c:558
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff814a6380-ffffffff814a63a4: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e520e)
Location: drivers/pci/probe.c:558
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_host_bridge_dev
```
**Symbols:**

```
ffffffff814e51c0-ffffffff814e51e4: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815146f0)
Location: drivers/pci/probe.c:582
Inline: False
```
**Symbols:**

```
ffffffff815146f0-ffffffff81514714: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81529e50)
Location: drivers/pci/probe.c:581
Inline: False
```
**Symbols:**

```
ffffffff81529e50-ffffffff81529e74: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815590e0)
Location: drivers/pci/probe.c:637
Inline: False
```
**Symbols:**

```
ffffffff815590e0-ffffffff81559113: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a6b0)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffff8157a6b0-ffffffff8157a6e3: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816204ab)
Location: drivers/pci/probe.c:640
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff8161f680-ffffffff8161f690: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646b40)
Location: drivers/pci/probe.c:646
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81645dc0-ffffffff81645dd0: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816294fa)
Location: drivers/pci/probe.c:647
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81628b40-ffffffff81628b50: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81698eda)
Location: drivers/pci/probe.c:649
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff816984d0-ffffffff816984e0: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817ba379)
Location: drivers/pci/probe.c:648
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff817b97c0-ffffffff817b97d6: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d52b9)
Location: drivers/pci/probe.c:648
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff818d4430-ffffffff818d4446: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918370)
Location: drivers/pci/probe.c:649
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff81917680-ffffffff81917696: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960e10)
Location: drivers/pci/probe.c:660
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
**Symbols:**

```
ffffffff8195f790-ffffffff8195f7a6: pci_free_host_bridge (STB_GLOBAL)
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
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd018)
Location: drivers/pci/probe.c:633
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
**Symbols:**

```
ffff8000106dd018-ffff8000106dd054: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0878b74)
Location: drivers/pci/probe.c:633
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
**Symbols:**

```
c0878b74-c0878ba8: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000855270)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
c000000000855270-c0000000008552cc: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5426)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffe0004b5426-ffffffe0004b5468: pci_free_host_bridge (STB_GLOBAL)
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
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156ebd0)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffff8156ebd0-ffffffff8156ec03: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d330)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffff8155d330-ffffffff8155d363: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e400)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffff8156e400-ffffffff8156e433: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_free_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815888e0)
Location: drivers/pci/probe.c:633
Inline: False
```
**Symbols:**

```
ffffffff815888e0-ffffffff81588913: pci_free_host_bridge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
