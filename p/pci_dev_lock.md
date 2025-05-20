# Function: <code>pci_dev_lock</code>

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
In drivers/pci/pci.c (ffffffff81434b89)
Location: drivers/pci/pci.c:3636
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff81480764)
Location: drivers/pci/pci.c:3957
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814a1db4)
Location: drivers/pci/pci.c:3995
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814ab9bf)
Location: drivers/pci/pci.c:4082
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
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
In drivers/pci/pci.c (ffffffff814ebb30)
Location: drivers/pci/pci.c:4119
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
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
In drivers/pci/pci.c (ffffffff8151a09a)
Location: drivers/pci/pci.c:4368
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8152fe2a)
Location: drivers/pci/pci.c:4659
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8155f628)
Location: drivers/pci/pci.c:4756
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81580768)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8162c055)
Location: drivers/pci/pci.c:4916
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81651da5)
Location: drivers/pci/pci.c:4984
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81634895)
Location: drivers/pci/pci.c:5033
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4985)
Location: drivers/pci/pci.c:5095
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8169d6f0-ffffffff8169d714: pci_dev_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6de5)
Location: drivers/pci/pci.c:5191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff817bfae0-ffffffff817bfb0d: pci_dev_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4285)
Location: drivers/pci/pci.c:5128
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff818dc050-ffffffff818dc07d: pci_dev_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81922ee8)
Location: drivers/pci/pci.c:5250
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8191f370-ffffffff8191f39d: pci_dev_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_lock(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196b468)
Location: drivers/pci/pci.c:5360
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff819674e0-ffffffff8196750d: pci_dev_lock (STB_GLOBAL)
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
In drivers/pci/pci.c (ffff8000106e3264)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (c087f110)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (c00000000085d154)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffe0004baadc)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff81574c88)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff815633e8)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff815744b8)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
In drivers/pci/pci.c (ffffffff8158e993)
Location: drivers/pci/pci.c:4886
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
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
