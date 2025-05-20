# Function: <code>for_each_companion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8161f7a0)
Location: drivers/usb/core/hcd-pci.c:60
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:resume_common
```
**Symbols:**

```
ffffffff8161f7a0-ffffffff8161f82d: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81680160)
Location: drivers/usb/core/hcd-pci.c:59
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81680160-ffffffff8168020c: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816ade90)
Location: drivers/usb/core/hcd-pci.c:59
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816ade90-ffffffff816adf3c: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816c3020)
Location: drivers/usb/core/hcd-pci.c:59
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816c3020-ffffffff816c30cc: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8172edf0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8172edf0-ffffffff8172ee9e: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8176df20)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8176df20-ffffffff8176dfce: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817925a0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817925a0-ffffffff8179264e: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817d0f40)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817d0f40-ffffffff817d0fe6: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81801e10)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81801e10-ffffffff81801eb6: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff818d2580)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff818d2580-ffffffff818d2626: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff818dc930)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff818dc930-ffffffff818dc9d6: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff818bfca0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff818bfca0-ffffffff818bfd41: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81956310)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81956310-ffffffff819563b1: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81aafee0)
Location: drivers/usb/core/hcd-pci.c:45
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81aafee0-ffffffff81aaff90: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c37fe0)
Location: drivers/usb/core/hcd-pci.c:45
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81c37fe0-ffffffff81c38090: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f3a0)
Location: drivers/usb/core/hcd-pci.c:45
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81c9f3a0-ffffffff81c9f449: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81d53ff0)
Location: drivers/usb/core/hcd-pci.c:45
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81d53ff0-ffffffff81d54099: for_each_companion (STB_LOCAL)
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
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffff800010a36520)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffff800010a36520-ffff800010a36608: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c0b09940)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c0b09940-c0b099f8: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c000000000af46c0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c000000000af46c0-c000000000af4828: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffe0006538c6)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffe0006538c6-ffffffe000653978: for_each_companion (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817ba1f0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817ba1f0-ffffffff817ba296: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817abc20)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817abc20-ffffffff817abcc6: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff817f6c90)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817f6c90-ffffffff817f6d36: for_each_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void for_each_companion(struct pci_dev *pdev, struct usb_hcd *hcd, companion_fn fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81810ed0)
Location: drivers/usb/core/hcd-pci.c:46
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81810ed0-ffffffff81810f76: for_each_companion (STB_LOCAL)
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
