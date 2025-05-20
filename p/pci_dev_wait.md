# Function: <code>pci_dev_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b700)
Location: drivers/pci/pci.c:4071
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_reset_bridge_secondary_bus
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pcie_flr
```
**Symbols:**

```
ffffffff8151b700-ffffffff8151b7fc: pci_dev_wait.constprop.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531480)
Location: drivers/pci/pci.c:4336
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81531480-ffffffff8153157c: pci_dev_wait.constprop.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4433
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81560d50-ffffffff81560e0b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81564a70-ffffffff81564acf: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81581f40-ffffffff81581ffb: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81585d8b-ffffffff81585dea: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1059
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff816263a0-ffffffff8162645b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff8162cb3a-ffffffff8162cb99: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1193
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff8164c0b0-ffffffff8164c16b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81bf7cc1-ffffffff81bf7d20: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1223
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff8162ec90-ffffffff8162ed4b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81be9b68-ffffffff81be9bc7: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1233
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_reset_bus_function
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff8169e320-ffffffff8169e3db: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81ce44fe-ffffffff81ce455d: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1165
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_reset_bus_function
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff817c0430-ffffffff817c04ca: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81eaaf23-ffffffff81eaafab: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_dev_wait(struct pci_dev *dev, char *reset_type, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818db700)
Location: drivers/pci/pci.c:1149
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff818db700-ffffffff818db81d: pci_dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_dev_wait(struct pci_dev *dev, char *reset_type, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191f120)
Location: drivers/pci/pci.c:1163
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff8191f120-ffffffff8191f2ad: pci_dev_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_dev_wait(struct pci_dev *dev, char *reset_type, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81967260)
Location: drivers/pci/pci.c:1226
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81967260-ffffffff81967417: pci_dev_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e51c0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffff8000106e51c0-ffff8000106e52f4: pci_dev_wait.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c0880e0c)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
c0880e0c-c0880f28: pci_dev_wait.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c00000000085f960)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
c00000000085f960-c00000000085faf8: pci_dev_wait.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc418)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffe0004bc418-ffffffe0004bc510: pci_dev_wait.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81576460-ffffffff8157651b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff8157a2ab-ffffffff8157a30a: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81564bc0-ffffffff81564c7b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff815689eb-ffffffff81568a4a: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81575c90-ffffffff81575d4b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81579adb-ffffffff81579b3a: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4429
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pci.c:pci_af_flr
```
**Symbols:**

```
ffffffff81590260-ffffffff8159031b: pci_dev_wait.constprop.0 (STB_LOCAL)
ffffffff81593f8b-ffffffff81593fea: pci_dev_wait.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
