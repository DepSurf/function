# Function: <code>broadcast_error_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pci_ers_result_t broadcast_error_message(struct pci_dev *dev, enum pci_channel_state state, char *error_mesg, int (*cb)(struct pci_dev *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449e30)
Location: drivers/pci/pcie/aer/aerdrv_core.c:358
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
**Symbols:**

```
ffffffff81449e30-ffffffff81449f18: broadcast_error_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pci_ers_result_t broadcast_error_message(struct pci_dev *dev, enum pci_channel_state state, char *error_mesg, int (*cb)(struct pci_dev *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814960f0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:358
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
**Symbols:**

```
ffffffff814960f0-ffffffff814961d6: broadcast_error_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pci_ers_result_t broadcast_error_message(struct pci_dev *dev, enum pci_channel_state state, char *error_mesg, int (*cb)(struct pci_dev *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7a90)
Location: drivers/pci/pcie/aer/aerdrv_core.c:360
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
**Symbols:**

```
ffffffff814b7a90-ffffffff814b7b76: broadcast_error_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pci_ers_result_t broadcast_error_message(struct pci_dev *dev, enum pci_channel_state state, char *error_mesg, int (*cb)(struct pci_dev *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2310)
Location: drivers/pci/pcie/aer/aerdrv_core.c:360
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
**Symbols:**

```
ffffffff814c2310-ffffffff814c23f8: broadcast_error_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pci_ers_result_t broadcast_error_message(struct pci_dev *dev, enum pci_channel_state state, char *error_mesg, int (*cb)(struct pci_dev *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502530)
Location: drivers/pci/pcie/aer/aerdrv_core.c:360
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
**Symbols:**

```
ffffffff81502530-ffffffff8150262d: broadcast_error_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81530e50)
Location: drivers/pci/pcie/err.c:230
Inline: True
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery
```
**Symbols:**

```
ffffffff81530e50-ffffffff81530f31: broadcast_error_message.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
