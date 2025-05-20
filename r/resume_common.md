# Function: <code>resume_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8161feb0)
Location: drivers/usb/core/hcd-pci.c:487
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff8161feb0-ffffffff8161ffef: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81680860)
Location: drivers/usb/core/hcd-pci.c:495
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81680860-ffffffff816809bf: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816ae590)
Location: drivers/usb/core/hcd-pci.c:495
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff816ae590-ffffffff816ae6ef: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816c3270)
Location: drivers/usb/core/hcd-pci.c:495
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff816c3270-ffffffff816c33cf: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8172f040)
Location: drivers/usb/core/hcd-pci.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff8172f040-ffffffff8172f1a2: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8176e5e0)
Location: drivers/usb/core/hcd-pci.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff8176e5e0-ffffffff8176e72b: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81792c60)
Location: drivers/usb/core/hcd-pci.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81792c60-ffffffff81792dab: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:468
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff817d1140-ffffffff817d1257: resume_common (STB_LOCAL)
ffffffff817d1b82-ffffffff817d1bb6: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81802010-ffffffff81802127: resume_common (STB_LOCAL)
ffffffff81802a52-ffffffff81802a86: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:468
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff818d2b40-ffffffff818d2c57: resume_common (STB_LOCAL)
ffffffff818d3217-ffffffff818d324b: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:479
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff818dcf70-ffffffff818dd08a: resume_common (STB_LOCAL)
ffffffff81c1eadb-ffffffff81c1eb0f: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:479
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff818c02e0-ffffffff818c03fa: resume_common (STB_LOCAL)
ffffffff81c1096c-ffffffff81c109a0: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:479
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81956a30-ffffffff81956b47: resume_common (STB_LOCAL)
ffffffff81d17ca2-ffffffff81d17cd6: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81ab0620-ffffffff81ab072a: resume_common (STB_LOCAL)
ffffffff81ee2b54-ffffffff81ee2b88: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c387e0)
Location: drivers/usb/core/hcd-pci.c:473
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81c387e0-ffffffff81c3892c: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int resume_common(struct device *dev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c9fb60)
Location: drivers/usb/core/hcd-pci.c:476
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81c9fb60-ffffffff81c9fca5: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int resume_common(struct device *dev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81d547b0)
Location: drivers/usb/core/hcd-pci.c:475
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff81d547b0-ffffffff81d548f2: resume_common (STB_LOCAL)
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
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffff800010a36678)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffff800010a36678-ffff800010a367dc: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c0b09b60)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
c0b09b60-c0b09cb0: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c000000000af4f70)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
c000000000af4f70-c000000000af518c: resume_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffe000654056)
Location: drivers/usb/core/hcd-pci.c:467
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
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
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff817ba3f0-ffffffff817ba507: resume_common (STB_LOCAL)
ffffffff817bae32-ffffffff817bae66: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff817abe10-ffffffff817abf27: resume_common (STB_LOCAL)
ffffffff817ac852-ffffffff817ac886: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff817f6e90-ffffffff817f6fa7: resume_common (STB_LOCAL)
ffffffff817f78d2-ffffffff817f7906: resume_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int resume_common(struct device *dev, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:467
Inline: False
Direct callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:hcd_pci_restore
  - drivers/usb/core/hcd-pci.c:hcd_pci_resume
```
**Symbols:**

```
ffffffff818110d0-ffffffff818111e7: resume_common (STB_LOCAL)
ffffffff81811b12-ffffffff81811b46: resume_common.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pm_message_t msg</code>
</li>
<li>
<b>Param removed. </b>
<code>int event</code>
</li>
</ul>
</details>
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
