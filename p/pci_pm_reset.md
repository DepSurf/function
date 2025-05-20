# Function: <code>pci_pm_reset</code>

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
In drivers/pci/pci.c (ffffffff81438372)
Location: drivers/pci/pci.c:3481
Inline: True
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
In drivers/pci/pci.c (ffffffff8148400e)
Location: drivers/pci/pci.c:3802
Inline: True
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
In drivers/pci/pci.c (ffffffff814a576e)
Location: drivers/pci/pci.c:3840
Inline: True
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
In drivers/pci/pci.c (ffffffff814af709)
Location: drivers/pci/pci.c:3958
Inline: True
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
In drivers/pci/pci.c (ffffffff814eec29)
Location: drivers/pci/pci.c:3995
Inline: True
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
In drivers/pci/pci.c (ffffffff8151ed33)
Location: drivers/pci/pci.c:4212
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81534cba)
Location: drivers/pci/pci.c:4484
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81564170)
Location: drivers/pci/pci.c:4581
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81585450)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff8162bf2e)
Location: drivers/pci/pci.c:4607
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81651c5e)
Location: drivers/pci/pci.c:4682
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff8163474e)
Location: drivers/pci/pci.c:4731
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_pm_reset(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169f200)
Location: drivers/pci/pci.c:4783
Inline: False
```
**Symbols:**

```
ffffffff8169f200-ffffffff8169f329: pci_pm_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_pm_reset(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0ee0)
Location: drivers/pci/pci.c:4879
Inline: False
```
**Symbols:**

```
ffffffff817c0ee0-ffffffff817c1011: pci_pm_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_pm_reset(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dee00)
Location: drivers/pci/pci.c:4822
Inline: False
```
**Symbols:**

```
ffffffff818dee00-ffffffff818defa9: pci_pm_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_pm_reset(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81922260)
Location: drivers/pci/pci.c:4860
Inline: False
```
**Symbols:**

```
ffffffff81922260-ffffffff81922409: pci_pm_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_pm_reset(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196a7c0)
Location: drivers/pci/pci.c:4970
Inline: False
```
**Symbols:**

```
ffffffff8196a7c0-ffffffff8196a969: pci_pm_reset (STB_LOCAL)
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
In drivers/pci/pci.c (ffff8000106e9b80)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (c0884b18)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (c000000000864c5c)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffe0004bfe48)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81579970)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff815680b0)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff815791a0)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff81593638)
Location: drivers/pci/pci.c:4577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
