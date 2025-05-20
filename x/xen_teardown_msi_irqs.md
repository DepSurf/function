# Function: <code>xen_teardown_msi_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff816f7480)
Location: arch/x86/pci/xen.c:385
Inline: False
```
**Symbols:**

```
ffffffff816f7480-ffffffff816f74d8: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8175c120)
Location: arch/x86/pci/xen.c:388
Inline: False
```
**Symbols:**

```
ffffffff8175c120-ffffffff8175c178: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81788690)
Location: arch/x86/pci/xen.c:379
Inline: False
```
**Symbols:**

```
ffffffff81788690-ffffffff817886e8: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff817a7790)
Location: arch/x86/pci/xen.c:379
Inline: False
```
**Symbols:**

```
ffffffff817a7790-ffffffff817a77e8: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8181e9f0)
Location: arch/x86/pci/xen.c:379
Inline: False
```
**Symbols:**

```
ffffffff8181e9f0-ffffffff8181ea4b: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81868bc0)
Location: arch/x86/pci/xen.c:379
Inline: False
```
**Symbols:**

```
ffffffff81868bc0-ffffffff81868c1b: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81888c40)
Location: arch/x86/pci/xen.c:379
Inline: False
```
**Symbols:**

```
ffffffff81888c40-ffffffff81888c9b: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff818d3580)
Location: arch/x86/pci/xen.c:380
Inline: False
```
**Symbols:**

```
ffffffff818d3580-ffffffff818d35de: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81905900)
Location: arch/x86/pci/xen.c:380
Inline: False
```
**Symbols:**

```
ffffffff81905900-ffffffff8190595e: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bb5eb0)
Location: arch/x86/pci/xen.c:377
Inline: False
```
**Symbols:**

```
ffffffff81bb5eb0-ffffffff81bb5f12: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bcba04)
Location: arch/x86/pci/xen.c:383
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81bcb0d0-ffffffff81bcb138: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bbf074)
Location: arch/x86/pci/xen.c:383
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81bbea10-ffffffff81bbea78: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81c8efe4)
Location: arch/x86/pci/xen.c:383
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81c8e970-ffffffff81c8e9d8: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81e3da40)
Location: arch/x86/pci/xen.c:387
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81e3da40-ffffffff81e3dab0: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff82016ff0)
Location: arch/x86/pci/xen.c:387
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff82016ff0-ffffffff8201706e: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff820973a0)
Location: arch/x86/pci/xen.c:387
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff820973a0-ffffffff82097426: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8216e880)
Location: arch/x86/pci/xen.c:387
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff8216e880-ffffffff8216e906: xen_teardown_msi_irqs (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff818a4cc0)
Location: arch/x86/pci/xen.c:380
Inline: False
```
**Symbols:**

```
ffffffff818a4cc0-ffffffff818a4d1e: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff818f6320)
Location: arch/x86/pci/xen.c:380
Inline: False
```
**Symbols:**

```
ffffffff818f6320-ffffffff818f637e: xen_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81917480)
Location: arch/x86/pci/xen.c:380
Inline: False
```
**Symbols:**

```
ffffffff81917480-ffffffff819174de: xen_teardown_msi_irqs (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
