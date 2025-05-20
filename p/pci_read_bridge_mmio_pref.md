# Function: <code>pci_read_bridge_mmio_pref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430c1d)
Location: drivers/pci/probe.c:400
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147c39e)
Location: drivers/pci/probe.c:403
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149d8fe)
Location: drivers/pci/probe.c:404
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a773f)
Location: drivers/pci/probe.c:404
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e608f)
Location: drivers/pci/probe.c:404
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8151551c)
Location: drivers/pci/probe.c:414
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152ac3c)
Location: drivers/pci/probe.c:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ca33)
Location: drivers/pci/probe.c:464
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157da9d)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_read_bridge_mmio_pref(struct pci_bus *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622d3e)
Location: drivers/pci/probe.c:460
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff81622d3e-ffffffff81622e6a: pci_read_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_read_bridge_mmio_pref(struct pci_bus *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81bf6f24)
Location: drivers/pci/probe.c:460
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
**Symbols:**

```
ffffffff81bf6f24-ffffffff81bf7050: pci_read_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81be9152)
Location: drivers/pci/probe.c:461
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81ce3582)
Location: drivers/pci/probe.c:462
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff81eaa123)
Location: drivers/pci/probe.c:461
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff818d5f04)
Location: drivers/pci/probe.c:461
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
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
In drivers/pci/probe.c (ffffffff81919144)
Location: drivers/pci/probe.c:461
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_read_bridge_mmio_pref(struct pci_dev *dev, struct resource *res, bool log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8195fa50)
Location: drivers/pci/probe.c:407
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
```
**Symbols:**

```
ffffffff8195fa50-ffffffff8195fbc8: pci_read_bridge_mmio_pref (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106ddf10)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0879b30)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008564b8)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b6198)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571fbd)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156071d)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815717ed)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158bccd)
Location: drivers/pci/probe.c:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
