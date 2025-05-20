# Function: <code>do_recovery</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_recovery(struct pci_dev *dev, int severity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449f20)
Location: drivers/pci/pcie/aer/aerdrv_core.c:484
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
**Symbols:**

```
ffffffff81449f20-ffffffff8144a15c: do_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_recovery(struct pci_dev *dev, int severity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814961e0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:484
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
```
**Symbols:**

```
ffffffff814961e0-ffffffff81496417: do_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_recovery(struct pci_dev *dev, int severity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7b80)
Location: drivers/pci/pcie/aer/aerdrv_core.c:486
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
```
**Symbols:**

```
ffffffff814b7b80-ffffffff814b7db7: do_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_recovery(struct pci_dev *dev, int severity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2400)
Location: drivers/pci/pcie/aer/aerdrv_core.c:486
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
```
**Symbols:**

```
ffffffff814c2400-ffffffff814c263b: do_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_recovery(struct pci_dev *dev, int severity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502630)
Location: drivers/pci/pcie/aer/aerdrv_core.c:493
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
```
**Symbols:**

```
ffffffff81502630-ffffffff8150286e: do_recovery (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
