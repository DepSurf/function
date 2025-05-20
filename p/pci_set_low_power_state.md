# Function: <code>pci_set_low_power_state</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_set_low_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1357
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff817c1e40-ffffffff817c200d: pci_set_low_power_state (STB_LOCAL)
ffffffff81eab0f2-ffffffff81eab175: pci_set_low_power_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_set_low_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818df370)
Location: drivers/pci/pci.c:1338
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff818df370-ffffffff818df5da: pci_set_low_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_set_low_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819227d0)
Location: drivers/pci/pci.c:1376
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff819227d0-ffffffff81922a3a: pci_set_low_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_set_low_power_state(struct pci_dev *dev, pci_power_t state, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196ad30)
Location: drivers/pci/pci.c:1458
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:__pci_set_power_state
```
**Symbols:**

```
ffffffff8196ad30-ffffffff8196afba: pci_set_low_power_state (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
</ul>
</details>
</li>
</ul>
