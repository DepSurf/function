# Function: <code>sriov_restore_state</code>

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
In drivers/pci/iov.c (ffffffff814572a8)
Location: drivers/pci/iov.c:507
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff814a3ea8)
Location: drivers/pci/iov.c:503
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff814c5c38)
Location: drivers/pci/iov.c:506
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff814cfcc8)
Location: drivers/pci/iov.c:497
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff8150fee8)
Location: drivers/pci/iov.c:491
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff81544fc6)
Location: drivers/pci/iov.c:519
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff8155c396)
Location: drivers/pci/iov.c:544
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff8158c5a6)
Location: drivers/pci/iov.c:542
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff815ae166)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sriov_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81656120)
Location: drivers/pci/iov.c:724
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff81656120-ffffffff8165623d: sriov_restore_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sriov_restore_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816766c0)
Location: drivers/pci/iov.c:725
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff816766c0-ffffffff816767dd: sriov_restore_state (STB_LOCAL)
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
In drivers/pci/iov.c (ffffffff8165a086)
Location: drivers/pci/iov.c:815
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff816cc3d6)
Location: drivers/pci/iov.c:822
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff817f2b64)
Location: drivers/pci/iov.c:863
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff8191b244)
Location: drivers/pci/iov.c:863
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff8195e854)
Location: drivers/pci/iov.c:863
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff819a7eb4)
Location: drivers/pci/iov.c:865
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffff800010718168)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (c08a284c)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (c000000000888c00)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffe0004e12dc)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff815a1926)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff81590ac6)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff815a1eb6)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
In drivers/pci/iov.c (ffffffff815bc2b6)
Location: drivers/pci/iov.c:708
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
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
