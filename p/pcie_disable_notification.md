# Function: <code>pcie_disable_notification</code>

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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81451858)
Location: drivers/pci/hotplug/pciehp_hpc.c:669
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149e068)
Location: drivers/pci/hotplug/pciehp_hpc.c:673
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bfc98)
Location: drivers/pci/hotplug/pciehp_hpc.c:709
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814ca408)
Location: drivers/pci/hotplug/pciehp_hpc.c:717
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a9b8)
Location: drivers/pci/hotplug/pciehp_hpc.c:714
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b503)
Location: drivers/pci/hotplug/pciehp_hpc.c:698
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551a50)
Location: drivers/pci/hotplug/pciehp_hpc.c:718
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81551a50-ffffffff81551aad: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581990)
Location: drivers/pci/hotplug/pciehp_hpc.c:720
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81581990-ffffffff815819ec: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3490)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff815a3490-ffffffff815a34ec: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c130)
Location: drivers/pci/hotplug/pciehp_hpc.c:784
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff8164c130-ffffffff8164c192: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670480)
Location: drivers/pci/hotplug/pciehp_hpc.c:787
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81670480-ffffffff816704e2: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816528c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:823
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff816528c0-ffffffff81652922: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4650)
Location: drivers/pci/hotplug/pciehp_hpc.c:824
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff816c4650-ffffffff816c46af: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea220)
Location: drivers/pci/hotplug/pciehp_hpc.c:826
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff817ea220-ffffffff817ea2a7: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910310)
Location: drivers/pci/hotplug/pciehp_hpc.c:828
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81910310-ffffffff81910397: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953a30)
Location: drivers/pci/hotplug/pciehp_hpc.c:819
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81953a30-ffffffff81953ab7: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cec0)
Location: drivers/pci/hotplug/pciehp_hpc.c:820
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff8199cec0-ffffffff8199cf47: pcie_disable_notification (STB_LOCAL)
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
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bbd0)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffff80001070bbd0-ffff80001070bc50: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d88e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffe0004d88e0-ffffffe0004d895e: pcie_disable_notification (STB_LOCAL)
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
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596ca0)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81596ca0-ffffffff81596cfc: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81585e30)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff81585e30-ffffffff81585e8c: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815971e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff815971e0-ffffffff8159723c: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pcie_disable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1620)
Location: drivers/pci/hotplug/pciehp_hpc.c:734
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
```
**Symbols:**

```
ffffffff815b1620-ffffffff815b167c: pcie_disable_notification (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
