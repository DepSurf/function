# Function: <code>pci_msix_clear_and_set_ctrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pci_msix_clear_and_set_ctrl(struct pci_dev *dev, u16 clear, u16 set);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431055)
Location: drivers/pci/pci.h:164
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81453880)
Location: drivers/pci/pci.h:164
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff81453880-ffffffff81453904: pci_msix_clear_and_set_ctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147cd93)
Location: drivers/pci/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814a1a2d)
Location: drivers/pci/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e2f3)
Location: drivers/pci/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814c367d)
Location: drivers/pci/pci.h:174
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a81d9)
Location: drivers/pci/pci.h:172
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff814ccded)
Location: drivers/pci/pci.h:172
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7219)
Location: drivers/pci/pci.h:173
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8150d32d)
Location: drivers/pci/pci.h:173
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8151691d)
Location: drivers/pci/pci.h:159
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8154221d)
Location: drivers/pci/pci.h:159
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c35d)
Location: drivers/pci/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8155a4cd)
Location: drivers/pci/pci.h:168
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ad18)
Location: drivers/pci/pci.h:173
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8158a5d3)
Location: drivers/pci/pci.h:173
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157bda8)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff815abf53)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81620082)
Location: drivers/pci/pci.h:199
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
```
```
In drivers/pci/msi.c (ffffffff8165434d)
Location: drivers/pci/pci.h:199
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8165da2d)
Location: drivers/pci/msi.c:448
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8163fc0e)
Location: drivers/pci/msi.c:439
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff816b0edd)
Location: drivers/pci/msi.c:427
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi/msi.c (ffffffff817d45a3)
Location: drivers/pci/msi/msi.c:283
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
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
In drivers/pci/msi/msi.c (ffffffff818f6399)
Location: drivers/pci/msi/msi.c:541
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
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
In drivers/pci/msi/msi.c (ffffffff819397f9)
Location: drivers/pci/msi/msi.c:541
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
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
In drivers/pci/msi/msi.c (ffffffff81982659)
Location: drivers/pci/msi/msi.c:543
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df378)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffff8000107159c8)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b038)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (c08a0368)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857bb0)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (c000000000885a40)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b73ce)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffe0004df102)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815702c8)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8159f723)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ea28)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8158e8b3)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156faf8)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff8159fca3)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589fd8)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/msi.c (ffffffff815ba0d3)
Location: drivers/pci/pci.h:198
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
