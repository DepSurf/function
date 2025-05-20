# Function: <code>__pci_disable_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814474e0)
Location: drivers/pci/pcie/aspm.c:712
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
```
**Symbols:**

```
ffffffff814474e0-ffffffff81447611: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81493670)
Location: drivers/pci/pcie/aspm.c:712
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81493670-ffffffff814937a1: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814b5000)
Location: drivers/pci/pcie/aspm.c:733
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff814b5000-ffffffff814b5131: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814bf890)
Location: drivers/pci/pcie/aspm.c:997
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff814bf890-ffffffff814bf9b4: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff814ffc10)
Location: drivers/pci/pcie/aspm.c:1031
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff814ffc10-ffffffff814ffd34: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815317f0)
Location: drivers/pci/pcie/aspm.c:1056
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff815317f0-ffffffff8153191c: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81548c90)
Location: drivers/pci/pcie/aspm.c:1050
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81548c90-ffffffff81548dbc: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1065
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81578e10-ffffffff81578f47: __pci_disable_link_state (STB_LOCAL)
ffffffff8157a329-ffffffff8157a345: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8159a620-ffffffff8159a7b3: __pci_disable_link_state (STB_LOCAL)
ffffffff8159bd49-ffffffff8159bd65: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1084
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8163a950-ffffffff8163aabc: __pci_disable_link_state (STB_LOCAL)
ffffffff8163b923-ffffffff8163b93f: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1076
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81661140-ffffffff816612ac: __pci_disable_link_state (STB_LOCAL)
ffffffff81bf8ff8-ffffffff81bf9014: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1076
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81643970-ffffffff81643adc: __pci_disable_link_state (STB_LOCAL)
ffffffff81beae31-ffffffff81beae4d: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1076
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff816b4700-ffffffff816b486c: __pci_disable_link_state (STB_LOCAL)
ffffffff81ce5d5c-ffffffff81ce5d78: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1112
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff817d7df0-ffffffff817d7ff9: __pci_disable_link_state (STB_LOCAL)
ffffffff81eac796-ffffffff81eac7b2: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff818f9440)
Location: drivers/pci/pcie/aspm.c:1074
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff818f9440-ffffffff818f962a: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8193c7c0)
Location: drivers/pci/pcie/aspm.c:1038
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8193c7c0-ffffffff8193c9a1: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81984f80)
Location: drivers/pci/pcie/aspm.c:1063
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff81984f80-ffffffff81985161: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010701ed0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffff800010701ed0-ffff8000107020a4: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c0899a80)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
c0899a80-c0899c24: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d0bda)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffe0004d0bda-ffffffe0004d0d84: __pci_disable_link_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8158e4b0-ffffffff8158e643: __pci_disable_link_state (STB_LOCAL)
ffffffff8158fbd9-ffffffff8158fbf5: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8157cff0-ffffffff8157d183: __pci_disable_link_state (STB_LOCAL)
ffffffff8157e719-ffffffff8157e735: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff8158e370-ffffffff8158e503: __pci_disable_link_state (STB_LOCAL)
ffffffff8158fa99-ffffffff8158fab5: __pci_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pci_disable_link_state(struct pci_dev *pdev, int state, bool sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1093
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pci_disable_link_state_locked
```
**Symbols:**

```
ffffffff815a8820-ffffffff815a89b3: __pci_disable_link_state (STB_LOCAL)
ffffffff815a9f49-ffffffff815a9f65: __pci_disable_link_state.cold (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sem</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
