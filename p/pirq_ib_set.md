# Function: <code>pirq_ib_set</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pirq_ib_set(struct pci_dev *router, struct pci_dev *dev, int pirq, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81c90b50)
Location: arch/x86/pci/irq.c:478
Inline: False
```
**Symbols:**

```
ffffffff81c90b50-ffffffff81c90b76: pirq_ib_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pirq_ib_set(struct pci_dev *router, struct pci_dev *dev, int pirq, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81e400a0)
Location: arch/x86/pci/irq.c:575
Inline: False
```
**Symbols:**

```
ffffffff81e400a0-ffffffff81e400d2: pirq_ib_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pirq_ib_set(struct pci_dev *router, struct pci_dev *dev, int pirq, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8201a150)
Location: arch/x86/pci/irq.c:575
Inline: False
```
**Symbols:**

```
ffffffff8201a150-ffffffff8201a182: pirq_ib_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pirq_ib_set(struct pci_dev *router, struct pci_dev *dev, int pirq, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8209a7d0)
Location: arch/x86/pci/irq.c:575
Inline: False
```
**Symbols:**

```
ffffffff8209a7d0-ffffffff8209a802: pirq_ib_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pirq_ib_set(struct pci_dev *router, struct pci_dev *dev, int pirq, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff82171f00)
Location: arch/x86/pci/irq.c:575
Inline: False
```
**Symbols:**

```
ffffffff82171f00-ffffffff82171f32: pirq_ib_set (STB_LOCAL)
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
