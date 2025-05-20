# Function: <code>sriov_enable</code>

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
In drivers/pci/iov.c (ffffffff814562b1)
Location: drivers/pci/iov.c:238
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
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
In drivers/pci/iov.c (ffffffff814a32c3)
Location: drivers/pci/iov.c:238
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
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
In drivers/pci/iov.c (ffffffff814c4f23)
Location: drivers/pci/iov.c:241
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
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
In drivers/pci/iov.c (ffffffff814cf0cd)
Location: drivers/pci/iov.c:234
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
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
In drivers/pci/iov.c (ffffffff8150f2dd)
Location: drivers/pci/iov.c:227
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81544250)
Location: drivers/pci/iov.c:254
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81544250-ffffffff81544670: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155b5f0)
Location: drivers/pci/iov.c:276
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8155b5f0-ffffffff8155ba28: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:274
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8158b910-ffffffff8158bcda: sriov_enable (STB_LOCAL)
ffffffff8158c6f0-ffffffff8158c77a: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff815ad4c0-ffffffff815ad88a: sriov_enable (STB_LOCAL)
ffffffff815ae30f-ffffffff815ae399: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:459
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81656ce0-ffffffff816570a8: sriov_enable (STB_LOCAL)
ffffffff816575fb-ffffffff81657685: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:460
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff816772a0-ffffffff81677668: sriov_enable (STB_LOCAL)
ffffffff81bfdc2c-ffffffff81bfdcb6: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:550
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81659850-ffffffff81659c1b: sriov_enable (STB_LOCAL)
ffffffff81befb35-ffffffff81befbbf: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:557
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff816cbb50-ffffffff816cbf4d: sriov_enable (STB_LOCAL)
ffffffff81ceaf56-ffffffff81ceafe0: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:598
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff817f2220-ffffffff817f2612: sriov_enable (STB_LOCAL)
ffffffff81eb1f9a-ffffffff81eb2006: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191a7d0)
Location: drivers/pci/iov.c:598
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8191a7d0-ffffffff8191ac22: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195de00)
Location: drivers/pci/iov.c:598
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8195de00-ffffffff8195e236: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7460)
Location: drivers/pci/iov.c:597
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff819a7460-ffffffff819a7896: sriov_enable (STB_LOCAL)
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
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff800010717348)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffff800010717348-ffff800010717778: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a1ad0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
c08a1ad0-c08a1ed8: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c000000000887ea0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
c000000000887ea0-c000000000888450: sriov_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e0624)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffe0004e0624-ffffffe0004e09c4: sriov_enable (STB_LOCAL)
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
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff815a0c90-ffffffff815a105a: sriov_enable (STB_LOCAL)
ffffffff815a1acf-ffffffff815a1b59: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8158fe20-ffffffff815901ea: sriov_enable (STB_LOCAL)
ffffffff81590c6f-ffffffff81590cf9: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff815a1210-ffffffff815a15da: sriov_enable (STB_LOCAL)
ffffffff815a205f-ffffffff815a20e9: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sriov_enable(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:440
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff815bb640-ffffffff815bba0a: sriov_enable (STB_LOCAL)
ffffffff815bc45f-ffffffff815bc4e9: sriov_enable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
