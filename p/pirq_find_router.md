# Function: <code>pirq_find_router</code>

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
In arch/x86/pci/irq.c (ffffffff81fb9b15)
Location: arch/x86/pci/irq.c:819
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff81fe76f8)
Location: arch/x86/pci/irq.c:819
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff82025f33)
Location: arch/x86/pci/irq.c:819
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff8210948d)
Location: arch/x86/pci/irq.c:819
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff82712deb)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff8273d053)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff828f706e)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff82912a8f)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff8291c824)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff82d324eb)
Location: arch/x86/pci/irq.c:820
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff82d324eb-ffffffff82d325d6: pirq_find_router.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff830214da)
Location: arch/x86/pci/irq.c:820
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff830214da-ffffffff830215c5: pirq_find_router.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8322c740)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff83317051)
Location: arch/x86/pci/irq.c:1087
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff834d1d25)
Location: arch/x86/pci/irq.c:1289
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff83f163f2)
Location: arch/x86/pci/irq.c:1289
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8373cb30)
Location: arch/x86/pci/irq.c:1289
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff839714b0)
Location: arch/x86/pci/irq.c:1289
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff82901528)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff828f9875)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff82916b2f)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In arch/x86/pci/irq.c (ffffffff8291d886)
Location: arch/x86/pci/irq.c:820
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
</ul>

## Differences
