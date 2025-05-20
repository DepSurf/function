# Function: <code>next_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430150)
Location: drivers/pci/probe.c:1792
Inline: True
```
**Symbols:**

```
ffffffff81430150-ffffffff814301f8: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147b8b0)
Location: drivers/pci/probe.c:1814
Inline: True
```
**Symbols:**

```
ffffffff8147b8b0-ffffffff8147b958: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149cdc0)
Location: drivers/pci/probe.c:1964
Inline: True
```
**Symbols:**

```
ffffffff8149cdc0-ffffffff8149ce68: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a6cc0)
Location: drivers/pci/probe.c:2090
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff814a6cc0-ffffffff814a6d64: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e5610)
Location: drivers/pci/probe.c:2221
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff814e5610-ffffffff814e56b4: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81514aa0)
Location: drivers/pci/probe.c:2372
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81514aa0-ffffffff81514b44: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152a1c0)
Location: drivers/pci/probe.c:2498
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8152a1c0-ffffffff8152a264: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81559920)
Location: drivers/pci/probe.c:2724
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81559920-ffffffff815599c2: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a990)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8157a990-ffffffff8157aa32: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81620180)
Location: drivers/pci/probe.c:2514
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81620180-ffffffff8162021e: next_fn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646800)
Location: drivers/pci/probe.c:2521
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81646800-ffffffff816468a1: next_fn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81629400)
Location: drivers/pci/probe.c:2565
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81629400-ffffffff816294a1: next_fn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81698de0)
Location: drivers/pci/probe.c:2607
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81698de0-ffffffff81698e81: next_fn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bb9b1)
Location: drivers/pci/probe.c:2603
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d74d1)
Location: drivers/pci/probe.c:2615
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a766)
Location: drivers/pci/probe.c:2629
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81962b66)
Location: drivers/pci/probe.c:2678
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
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
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd3f8)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffff8000106dd3f8-ffff8000106dd4b8: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0878ef4)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
c0878ef4-c0878fd0: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008555a0)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
c0000000008555a0-c0000000008556b4: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5710)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffe0004b5710-ffffffe0004b57a0: next_fn (STB_LOCAL)
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
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156eeb0)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8156eeb0-ffffffff8156ef52: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d610)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8155d610-ffffffff8155d6b2: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e6e0)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8156e6e0-ffffffff8156e782: next_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int next_fn(struct pci_bus *bus, struct pci_dev *dev, unsigned int fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81588bc0)
Location: drivers/pci/probe.c:2462
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81588bc0-ffffffff81588c62: next_fn (STB_LOCAL)
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
