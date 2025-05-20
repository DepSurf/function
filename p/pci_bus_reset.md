# Function: <code>pci_bus_reset</code>

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
In drivers/pci/pci.c (ffffffff81433855)
Location: drivers/pci/pci.c:4138
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_try_reset_bus
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
In drivers/pci/pci.c (ffffffff8148440c)
Location: drivers/pci/pci.c:4459
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
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
In drivers/pci/pci.c (ffffffff814a5b6c)
Location: drivers/pci/pci.c:4497
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
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
In drivers/pci/pci.c (ffffffff814af8ec)
Location: drivers/pci/pci.c:4655
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_reset(struct pci_bus *bus, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eed30)
Location: drivers/pci/pci.c:4679
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
```
**Symbols:**

```
ffffffff814eed30-ffffffff814eed97: pci_bus_reset (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff8151ec45)
Location: drivers/pci/pci.c:4928
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
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
In drivers/pci/pci.c (ffffffff8152e935)
Location: drivers/pci/pci.c:5194
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff8155e0d5)
Location: drivers/pci/pci.c:5292
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff8157f145)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816265e5)
Location: drivers/pci/pci.c:5452
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c2f5)
Location: drivers/pci/pci.c:5520
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff8162eed5)
Location: drivers/pci/pci.c:5569
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff816a43a5)
Location: drivers/pci/pci.c:5759
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff817c67c5)
Location: drivers/pci/pci.c:5855
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff818e3b95)
Location: drivers/pci/pci.c:5792
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_reset(struct pci_bus *bus, bool probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927185)
Location: drivers/pci/pci.c:5914
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff819271c0-ffffffff819272b8: pci_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_reset(struct pci_bus *bus, bool probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f925)
Location: drivers/pci/pci.c:6024
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
```
**Symbols:**

```
ffffffff8196f960-ffffffff8196fa58: pci_bus_reset (STB_LOCAL)
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
In drivers/pci/pci.c (ffff8000106e1ae8)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (c087d778)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (c00000000085b090)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffe0004b96dc)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff81573665)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff81561dc5)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff81572e95)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
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
In drivers/pci/pci.c (ffffffff8158d375)
Location: drivers/pci/pci.c:5422
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_bus_error_reset
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
