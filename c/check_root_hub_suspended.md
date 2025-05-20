# Function: <code>check_root_hub_suspended</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816200d0)
Location: drivers/usb/core/hcd-pci.c:413
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff816200d0-ffffffff81620128: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81680aa0)
Location: drivers/usb/core/hcd-pci.c:421
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81680aa0-ffffffff81680af8: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816ae7d0)
Location: drivers/usb/core/hcd-pci.c:421
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816ae7d0-ffffffff816ae828: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816c3490)
Location: drivers/usb/core/hcd-pci.c:421
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816c3490-ffffffff816c34e8: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8172f270)
Location: drivers/usb/core/hcd-pci.c:408
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff8172f270-ffffffff8172f2c8: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8176e7f0)
Location: drivers/usb/core/hcd-pci.c:408
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff8176e7f0-ffffffff8176e848: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81792e70)
Location: drivers/usb/core/hcd-pci.c:408
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81792e70-ffffffff81792ec8: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817d1320-ffffffff817d135b: check_root_hub_suspended (STB_LOCAL)
ffffffff817d1bb6-ffffffff817d1be4: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff818021f0-ffffffff8180222b: check_root_hub_suspended (STB_LOCAL)
ffffffff81802a86-ffffffff81802ab4: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:395
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff818d2d20-ffffffff818d2d5b: check_root_hub_suspended (STB_LOCAL)
ffffffff818d324b-ffffffff818d3279: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:406
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff818dd150-ffffffff818dd18b: check_root_hub_suspended (STB_LOCAL)
ffffffff81c1eb0f-ffffffff81c1eb3d: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:406
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff818c04c0-ffffffff818c04fb: check_root_hub_suspended (STB_LOCAL)
ffffffff81c109a0-ffffffff81c109ce: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:406
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81956c10-ffffffff81956c4b: check_root_hub_suspended (STB_LOCAL)
ffffffff81d17cd6-ffffffff81d17d04: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:405
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81ab0820-ffffffff81ab0863: check_root_hub_suspended (STB_LOCAL)
ffffffff81ee2b88-ffffffff81ee2bac: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c38a70)
Location: drivers/usb/core/hcd-pci.c:400
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81c38a70-ffffffff81c38acc: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c9fdf0)
Location: drivers/usb/core/hcd-pci.c:400
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81c9fdf0-ffffffff81c9fe4c: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81d54a40)
Location: drivers/usb/core/hcd-pci.c:399
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81d54a40-ffffffff81d54a9c: check_root_hub_suspended (STB_LOCAL)
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
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffff800010a36908)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffff800010a36908-ffff800010a3697c: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c0b09d8c)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
c0b09d8c-c0b09df8: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c000000000af52d0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
c000000000af52d0-c000000000af536c: check_root_hub_suspended (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffe000653e2e)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_suspend
```
**Symbols:**

```
ffffffe000653e2e-ffffffe000653e98: check_root_hub_suspended (STB_LOCAL)
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
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817ba5d0-ffffffff817ba60b: check_root_hub_suspended (STB_LOCAL)
ffffffff817bae66-ffffffff817bae94: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817abff0-ffffffff817ac02b: check_root_hub_suspended (STB_LOCAL)
ffffffff817ac886-ffffffff817ac8b4: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817f7070-ffffffff817f70ab: check_root_hub_suspended (STB_LOCAL)
ffffffff817f7906-ffffffff817f7934: check_root_hub_suspended.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_root_hub_suspended(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:394
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff818112b0-ffffffff818112eb: check_root_hub_suspended (STB_LOCAL)
ffffffff81811b46-ffffffff81811b74: check_root_hub_suspended.cold (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
