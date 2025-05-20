# Function: <code>sriov_disable</code>

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
In drivers/pci/iov.c (ffffffff81456ad8)
Location: drivers/pci/iov.c:353
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
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
In drivers/pci/iov.c (ffffffff814a3718)
Location: drivers/pci/iov.c:353
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
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
In drivers/pci/iov.c (ffffffff814c5378)
Location: drivers/pci/iov.c:356
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
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
In drivers/pci/iov.c (ffffffff814cf4f6)
Location: drivers/pci/iov.c:350
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
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
In drivers/pci/iov.c (ffffffff8150f706)
Location: drivers/pci/iov.c:343
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815446b0)
Location: drivers/pci/iov.c:370
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff815446b0-ffffffff81544791: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155ba70)
Location: drivers/pci/iov.c:398
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8155ba70-ffffffff8155bb69: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158bd20)
Location: drivers/pci/iov.c:396
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8158bd20-ffffffff8158be07: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815ad8d0)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff815ad8d0-ffffffff815ad9b7: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816570f0)
Location: drivers/pci/iov.c:578
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff816570f0-ffffffff816571d2: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816776b0)
Location: drivers/pci/iov.c:579
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff816776b0-ffffffff81677792: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81659c60)
Location: drivers/pci/iov.c:669
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff81659c60-ffffffff81659d42: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cbf90)
Location: drivers/pci/iov.c:676
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff816cbf90-ffffffff816cc072: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f2660)
Location: drivers/pci/iov.c:717
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff817f2660-ffffffff817f275a: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191ac90)
Location: drivers/pci/iov.c:717
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8191ac90-ffffffff8191ad8a: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195e2a0)
Location: drivers/pci/iov.c:717
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff8195e2a0-ffffffff8195e39a: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7900)
Location: drivers/pci/iov.c:716
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff819a7900-ffffffff819a79fa: sriov_disable (STB_LOCAL)
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
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff8000107177c0)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffff8000107177c0-ffff8000107178d4: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a1f1c)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
c08a1f1c-c08a2014: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c0000000008884d0)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
c0000000008884d0-c00000000088865c: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e0a10)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffe0004e0a10-ffffffe0004e0b24: sriov_disable (STB_LOCAL)
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
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a10a0)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff815a10a0-ffffffff815a1187: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81590230)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff81590230-ffffffff81590317: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a1620)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff815a1620-ffffffff815a1707: sriov_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sriov_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bba30)
Location: drivers/pci/iov.c:562
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
```
**Symbols:**

```
ffffffff815bba30-ffffffff815bbb17: sriov_disable (STB_LOCAL)
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
