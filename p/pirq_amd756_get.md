# Function: <code>pirq_amd756_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff816f9180)
Location: arch/x86/pci/irq.c:485
Inline: False
```
**Symbols:**

```
ffffffff816f9180-ffffffff816f91e1: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8175de90)
Location: arch/x86/pci/irq.c:485
Inline: False
```
**Symbols:**

```
ffffffff8175de90-ffffffff8175def1: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8178a3c0)
Location: arch/x86/pci/irq.c:485
Inline: False
```
**Symbols:**

```
ffffffff8178a3c0-ffffffff8178a421: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff817a94f0)
Location: arch/x86/pci/irq.c:485
Inline: False
```
**Symbols:**

```
ffffffff817a94f0-ffffffff817a9551: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818209a0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff818209a0-ffffffff81820a01: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8186ac40)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff8186ac40-ffffffff8186aca3: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8188ad10)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff8188ad10-ffffffff8188ad73: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff818d5650-ffffffff818d56ad: pirq_amd756_get (STB_LOCAL)
ffffffff818d63b6-ffffffff818d63bd: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff819079d0-ffffffff81907a2d: pirq_amd756_get (STB_LOCAL)
ffffffff81908736-ffffffff8190873d: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff81bb87d0-ffffffff81bb8823: pirq_amd756_get (STB_LOCAL)
ffffffff81bb90c9-ffffffff81bb9130: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff81bcd3e0-ffffffff81bcd433: pirq_amd756_get (STB_LOCAL)
ffffffff81c347e8-ffffffff81c3484f: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff81bc0e10-ffffffff81bc0e63: pirq_amd756_get (STB_LOCAL)
ffffffff81c26bc1-ffffffff81c26c28: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:737
Inline: False
```
**Symbols:**

```
ffffffff81c90850-ffffffff81c908a3: pirq_amd756_get (STB_LOCAL)
ffffffff81d449cb-ffffffff81d44a32: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:911
Inline: False
```
**Symbols:**

```
ffffffff81e3fa40-ffffffff81e3fa97: pirq_amd756_get (STB_LOCAL)
ffffffff81f11902-ffffffff81f1197b: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff820199f0)
Location: arch/x86/pci/irq.c:911
Inline: False
```
**Symbols:**

```
ffffffff820199f0-ffffffff82019aa8: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8209a070)
Location: arch/x86/pci/irq.c:911
Inline: False
```
**Symbols:**

```
ffffffff8209a070-ffffffff8209a128: pirq_amd756_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff821717a0)
Location: arch/x86/pci/irq.c:911
Inline: False
```
**Symbols:**

```
ffffffff821717a0-ffffffff82171858: pirq_amd756_get (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff818a6d90-ffffffff818a6ded: pirq_amd756_get (STB_LOCAL)
ffffffff818a7af6-ffffffff818a7afd: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff818618b0-ffffffff8186190d: pirq_amd756_get (STB_LOCAL)
ffffffff81862616-ffffffff8186261d: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff818f83f0-ffffffff818f844d: pirq_amd756_get (STB_LOCAL)
ffffffff818f9156-ffffffff818f915d: pirq_amd756_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pirq_amd756_get(struct pci_dev *router, struct pci_dev *dev, int pirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:486
Inline: False
```
**Symbols:**

```
ffffffff819194f0-ffffffff8191954d: pirq_amd756_get (STB_LOCAL)
ffffffff8191a256-ffffffff8191a25d: pirq_amd756_get.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
