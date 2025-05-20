# Function: <code>sriov_init</code>

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
In drivers/pci/iov.c (ffffffff81456c07)
Location: drivers/pci/iov.c:379
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/iov.c (ffffffff814a3857)
Location: drivers/pci/iov.c:379
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/iov.c (ffffffff814c54b7)
Location: drivers/pci/iov.c:382
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/iov.c (ffffffff814cf617)
Location: drivers/pci/iov.c:376
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/iov.c (ffffffff8150f827)
Location: drivers/pci/iov.c:369
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/iov.c (ffffffff81544897)
Location: drivers/pci/iov.c:396
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155bc67)
Location: drivers/pci/iov.c:421
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158bef6)
Location: drivers/pci/iov.c:419
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815adaa6)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:601
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81656240-ffffffff816566a5: sriov_init (STB_LOCAL)
ffffffff816575af-ffffffff816575fb: sriov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:602
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff816767e0-ffffffff81676c58: sriov_init (STB_LOCAL)
ffffffff81bfdbe0-ffffffff81bfdc2c: sriov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:692
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81658e00-ffffffff81659264: sriov_init (STB_LOCAL)
ffffffff81befae9-ffffffff81befb35: sriov_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cae60)
Location: drivers/pci/iov.c:699
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff816cae60-ffffffff816cb39e: sriov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f1450)
Location: drivers/pci/iov.c:740
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff817f1450-ffffffff817f19f7: sriov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81919980)
Location: drivers/pci/iov.c:740
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff81919980-ffffffff81919f26: sriov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195cfa0)
Location: drivers/pci/iov.c:740
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff8195cfa0-ffffffff8195d551: sriov_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a65c0)
Location: drivers/pci/iov.c:739
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
ffffffff819a65c0-ffffffff819a6bb3: sriov_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff8000107179e8)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a2120)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sriov_init(struct pci_dev *dev, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c000000000887110)
Location: drivers/pci/iov.c:585
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_init
```
**Symbols:**

```
c000000000887110-c000000000887798: sriov_init (STB_LOCAL)
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
In drivers/pci/iov.c (ffffffe0004e0c46)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a1276)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81590406)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a17f6)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bbbf6)
Location: drivers/pci/iov.c:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
