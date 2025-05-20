# Function: <code>ati_ixp4x0_rev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810354ed)
Location: arch/x86/kernel/quirks.c:355
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f6f259)
Location: arch/x86/kernel/early-quirks.c:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810346ed)
Location: arch/x86/kernel/quirks.c:355
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81f979ee)
Location: arch/x86/kernel/early-quirks.c:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103432d)
Location: arch/x86/kernel/quirks.c:355
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff81fd2f00)
Location: arch/x86/kernel/early-quirks.c:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103240a)
Location: arch/x86/kernel/quirks.c:355
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff820b3b69)
Location: arch/x86/kernel/early-quirks.c:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103473a)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826ba3a6)
Location: arch/x86/kernel/early-quirks.c:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103575e)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff826e4010)
Location: arch/x86/kernel/early-quirks.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103693e)
Location: arch/x86/kernel/quirks.c:358
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289aab2)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810389be)
Location: arch/x86/kernel/quirks.c:358
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b280e)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103918e)
Location: arch/x86/kernel/quirks.c:356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b5c60)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
u32 ati_ixp4x0_rev(struct pci_dev *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103bc40)
Location: arch/x86/kernel/quirks.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82cdaf22)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
**Symbols:**

```
ffffffff8103bc40-ffffffff8103bd21: ati_ixp4x0_rev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
u32 ati_ixp4x0_rev(struct pci_dev *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103c3b0)
Location: arch/x86/kernel/quirks.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff82fc7376)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
**Symbols:**

```
ffffffff8103c3b0-ffffffff8103c491: ati_ixp4x0_rev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103dd8c)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff831d1c1e)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81043b02)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff832b40a7)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8104bcf2)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83465879)
Location: arch/x86/kernel/early-quirks.c:148
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81057f22)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83e88e71)
Location: arch/x86/kernel/early-quirks.c:148
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810590c2)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff836ac391)
Location: arch/x86/kernel/early-quirks.c:148
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810602e2)
Location: arch/x86/kernel/quirks.c:357
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff838dcb21)
Location: arch/x86/kernel/early-quirks.c:148
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810392ee)
Location: arch/x86/kernel/quirks.c:356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828a3c6c)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81028bfe)
Location: arch/x86/kernel/quirks.c:356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff8289bdae)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103914e)
Location: arch/x86/kernel/quirks.c:356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6b7c)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8103a14e)
Location: arch/x86/kernel/quirks.c:356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In arch/x86/kernel/early-quirks.c (ffffffff828b6c63)
Location: arch/x86/kernel/early-quirks.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
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
</ul>
