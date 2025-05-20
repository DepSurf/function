# Function: <code>pci_call_probe</code>

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
In drivers/pci/pci-driver.c (ffffffff8143a831)
Location: drivers/pci/pci-driver.c:323
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff81486751)
Location: drivers/pci/pci-driver.c:323
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff814a7f11)
Location: drivers/pci/pci-driver.c:323
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff814b1eef)
Location: drivers/pci/pci-driver.c:332
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff814f15c8)
Location: drivers/pci/pci-driver.c:332
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff815217c8)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff815375f8)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff81566f41)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff815882a1)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162dfc0)
Location: drivers/pci/pci-driver.c:332
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff8162dfc0-ffffffff8162e0a0: pci_call_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816536c0)
Location: drivers/pci/pci-driver.c:335
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff816536c0-ffffffff816537a6: pci_call_probe (STB_LOCAL)
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
In drivers/pci/pci-driver.c (ffffffff81637051)
Location: drivers/pci/pci-driver.c:335
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff816a72a1)
Location: drivers/pci/pci-driver.c:349
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c8c80)
Location: drivers/pci/pci-driver.c:350
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff817c8c80-ffffffff817c8e06: pci_call_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e6580)
Location: drivers/pci/pci-driver.c:350
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff818e6580-ffffffff818e670b: pci_call_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81929bc0)
Location: drivers/pci/pci-driver.c:350
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff81929bc0-ffffffff81929d4b: pci_call_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_call_probe(struct pci_driver *drv, struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff819723c0)
Location: drivers/pci/pci-driver.c:350
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffffffff819723c0-ffffffff81972552: pci_call_probe (STB_LOCAL)
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
In drivers/pci/pci-driver.c (ffff8000106ec6b0)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (c08879a4)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (c0000000008683a4)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffe0004c1716)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff8157c131)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff8156af01)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff8157bff1)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
In drivers/pci/pci-driver.c (ffffffff815964a1)
Location: drivers/pci/pci-driver.c:331
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
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
