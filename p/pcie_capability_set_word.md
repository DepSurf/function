# Function: <code>pcie_capability_set_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8143251c)
Location: include/linux/pci.h:942
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81437b26)
Location: include/linux/pci.h:942
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/quirks.c (ffffffff81446a04)
Location: include/linux/pci.h:942
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449b37)
Location: include/linux/pci.h:942
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b966)
Location: include/linux/pci.h:942
Inline: True
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
In drivers/pci/probe.c (ffffffff8147dd4d)
Location: include/linux/pci.h:953
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81483746)
Location: include/linux/pci.h:953
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/quirks.c (ffffffff81492bb4)
Location: include/linux/pci.h:953
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81495df7)
Location: include/linux/pci.h:953
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81497bf6)
Location: include/linux/pci.h:953
Inline: True
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
In drivers/pci/probe.c (ffffffff8149f40d)
Location: include/linux/pci.h:983
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814a4ea6)
Location: include/linux/pci.h:983
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/quirks.c (ffffffff814b4544)
Location: include/linux/pci.h:983
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b77a2)
Location: include/linux/pci.h:983
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff814b9536)
Location: include/linux/pci.h:983
Inline: True
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
In drivers/pci/probe.c (ffffffff814a66d1)
Location: include/linux/pci.h:984
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814ad386)
Location: include/linux/pci.h:984
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c207d)
Location: include/linux/pci.h:984
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3d26)
Location: include/linux/pci.h:984
Inline: True
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
In drivers/pci/probe.c (ffffffff814e6cdf)
Location: include/linux/pci.h:1009
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff814ec756)
Location: include/linux/pci.h:1009
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8150229d)
Location: include/linux/pci.h:1009
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81503f66)
Location: include/linux/pci.h:1009
Inline: True
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
In drivers/pci/probe.c (ffffffff815161fc)
Location: include/linux/pci.h:1004
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8151c316)
Location: include/linux/pci.h:1004
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff815338ba)
Location: include/linux/pci.h:1004
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81534dd5)
Location: include/linux/pci.h:1004
Inline: True
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
In drivers/pci/probe.c (ffffffff8152bca2)
Location: include/linux/pci.h:1040
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8152f61f)
Location: include/linux/pci.h:1040
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8154ad7c)
Location: include/linux/pci.h:1040
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c475)
Location: include/linux/pci.h:1040
Inline: True
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
In drivers/pci/probe.c (ffffffff8155a743)
Location: include/linux/pci.h:1101
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8155ed77)
Location: include/linux/pci.h:1101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8157ac4f)
Location: include/linux/pci.h:1101
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c175)
Location: include/linux/pci.h:1101
Inline: True
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
In drivers/pci/probe.c (ffffffff8157b7cc)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8157feb5)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8159c68f)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff8159dbd5)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (ffffffff8161fac1)
Location: include/linux/pci.h:1126
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81625425)
Location: include/linux/pci.h:1126
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8163c0a1)
Location: include/linux/pci.h:1126
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8163db31)
Location: include/linux/pci.h:1126
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816463e5)
Location: include/linux/pci.h:1136
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8164b555)
Location: include/linux/pci.h:1136
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff81663041)
Location: include/linux/pci.h:1136
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff816641c1)
Location: include/linux/pci.h:1136
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81628ff5)
Location: include/linux/pci.h:1143
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8162e135)
Location: include/linux/pci.h:1143
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff81645501)
Location: include/linux/pci.h:1143
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81646631)
Location: include/linux/pci.h:1143
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816989ac)
Location: include/linux/pci.h:1191
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8169cc98)
Location: include/linux/pci.h:1191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/aer.c (ffffffff816b66f7)
Location: include/linux/pci.h:1191
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7f2f)
Location: include/linux/pci.h:1191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817b9f48)
Location: include/linux/pci.h:1216
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff817bebec)
Location: include/linux/pci.h:1216
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/aer.c (ffffffff817da246)
Location: include/linux/pci.h:1216
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc33f)
Location: include/linux/pci.h:1216
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d4dd8)
Location: include/linux/pci.h:1223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff818db0bc)
Location: include/linux/pci.h:1223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/aer.c (ffffffff818fbd16)
Location: include/linux/pci.h:1223
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe24f)
Location: include/linux/pci.h:1223
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918508)
Location: include/linux/pci.h:1257
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81926cc1)
Location: include/linux/pci.h:1257
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f5e6)
Location: include/linux/pci.h:1257
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff819416ff)
Location: include/linux/pci.h:1257
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960a08)
Location: include/linux/pci.h:1285
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8196f461)
Location: include/linux/pci.h:1285
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/aer.c (ffffffff819891bb)
Location: include/linux/pci.h:1285
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a95f)
Location: include/linux/pci.h:1285
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
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
In drivers/pci/probe.c (ffff8000106dec28)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffff8000106e2a88)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffff800010704310)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffff800010705bd0)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (c087a934)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c087e6fc)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (c089b300)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (c089cf08)
Location: include/linux/pci.h:1102
Inline: True
```
```
In drivers/pci/controller/pci-tegra.c (c08aa05c)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_relax_enable
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
In drivers/pci/probe.c (c000000000859380)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c00000000085c474)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
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
In drivers/pci/probe.c (ffffffe0004b6da2)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffe0004ba238)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d2324)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3ab8)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (ffffffff8156fcec)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff815743d5)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8158fd47)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815913d5)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (ffffffff8155e44c)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81562b35)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff8157f05f)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815805a5)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (ffffffff8156f51c)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81573c05)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff815903df)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81591925)
Location: include/linux/pci.h:1102
Inline: True
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
In drivers/pci/probe.c (ffffffff815899fc)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8158e0e5)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
```
In drivers/pci/pcie/aer.c (ffffffff815aa88f)
Location: include/linux/pci.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff815abf15)
Location: include/linux/pci.h:1102
Inline: True
```
</details>
</li>
</ul>

## Differences
