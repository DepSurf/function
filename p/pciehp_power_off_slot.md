# Function: <code>pciehp_power_off_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81451160)
Location: drivers/pci/hotplug/pciehp_hpc.c:528
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
**Symbols:**

```
ffffffff81451160-ffffffff814511c5: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d970)
Location: drivers/pci/hotplug/pciehp_hpc.c:528
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8149d970-ffffffff8149d9d5: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf590)
Location: drivers/pci/hotplug/pciehp_hpc.c:551
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814bf590-ffffffff814bf5f5: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9d10)
Location: drivers/pci/hotplug/pciehp_hpc.c:551
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff814c9d10-ffffffff814c9d75: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a2c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:548
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8150a2c0-ffffffff8150a325: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciehp_power_off_slot(struct slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b220)
Location: drivers/pci/hotplug/pciehp_hpc.c:528
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff8153b220-ffffffff8153b288: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815526d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:505
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815526d0-ffffffff81552733: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582590)
Location: drivers/pci/hotplug/pciehp_hpc.c:507
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81582590-ffffffff815825f2: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3f70)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815a3f70-ffffffff815a3fd2: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164cb60)
Location: drivers/pci/hotplug/pciehp_hpc.c:555
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8164cb60-ffffffff8164cbc8: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670eb0)
Location: drivers/pci/hotplug/pciehp_hpc.c:558
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81670eb0-ffffffff81670f18: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816533e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:558
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816533e0-ffffffff81653448: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c5150)
Location: drivers/pci/hotplug/pciehp_hpc.c:558
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816c5150-ffffffff816c51b5: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eae70)
Location: drivers/pci/hotplug/pciehp_hpc.c:560
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff817eae70-ffffffff817eaefd: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819111b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:560
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff819111b0-ffffffff8191123d: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954850)
Location: drivers/pci/hotplug/pciehp_hpc.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81954850-ffffffff819548dd: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199dce0)
Location: drivers/pci/hotplug/pciehp_hpc.c:555
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8199dce0-ffffffff8199dd6d: pciehp_power_off_slot (STB_GLOBAL)
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
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070cb70)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffff80001070cb70-ffff80001070cbf4: pciehp_power_off_slot (STB_GLOBAL)
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
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d93a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffe0004d93a0-ffffffe0004d9420: pciehp_power_off_slot (STB_GLOBAL)
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
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597780)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81597780-ffffffff815977e2: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586910)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81586910-ffffffff81586972: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597cc0)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81597cc0-ffffffff81597d22: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pciehp_power_off_slot(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b2100)
Location: drivers/pci/hotplug/pciehp_hpc.c:519
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815b2100-ffffffff815b2162: pciehp_power_off_slot (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot *slot</code>
</li>
</ul>
</details>
</li>
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
