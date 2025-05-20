# Function: <code>hpet_assign_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81058aa0)
Location: arch/x86/kernel/apic/msi.c:346
Inline: False
```
**Symbols:**

```
ffffffff81058aa0-ffffffff81058b2d: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81058de0)
Location: arch/x86/kernel/apic/msi.c:346
Inline: False
```
**Symbols:**

```
ffffffff81058de0-ffffffff81058e75: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105bb70)
Location: arch/x86/kernel/apic/msi.c:346
Inline: False
```
**Symbols:**

```
ffffffff8105bb70-ffffffff8105bc05: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105b2f0)
Location: arch/x86/kernel/apic/msi.c:379
Inline: False
```
**Symbols:**

```
ffffffff8105b2f0-ffffffff8105b37f: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105f800)
Location: arch/x86/kernel/apic/msi.c:375
Inline: False
```
**Symbols:**

```
ffffffff8105f800-ffffffff8105f88f: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81062910)
Location: arch/x86/kernel/apic/msi.c:376
Inline: False
```
**Symbols:**

```
ffffffff81062910-ffffffff8106299f: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_dev *dev, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81068610)
Location: arch/x86/kernel/apic/msi.c:376
Inline: False
```
**Symbols:**

```
ffffffff81068610-ffffffff8106869f: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106be10)
Location: arch/x86/kernel/apic/msi.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8106be10-ffffffff8106bea0: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c9c0)
Location: arch/x86/kernel/apic/msi.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8106c9c0-ffffffff8106ca50: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81073d20)
Location: arch/x86/kernel/apic/msi.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
**Symbols:**

```
ffffffff81073d20-ffffffff81073db0: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82fcf995)
Location: arch/x86/kernel/hpet.c:594
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff831da478)
Location: arch/x86/kernel/hpet.c:594
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff832bd575)
Location: arch/x86/kernel/hpet.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff8346ef52)
Location: arch/x86/kernel/hpet.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff83e95544)
Location: arch/x86/kernel/hpet.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff836b909c)
Location: arch/x86/kernel/hpet.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
In arch/x86/kernel/hpet.c (ffffffff838e997b)
Location: arch/x86/kernel/hpet.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
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
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c4b0)
Location: arch/x86/kernel/apic/msi.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8106c4b0-ffffffff8106c540: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105c7d0)
Location: arch/x86/kernel/apic/msi.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8105c7d0-ffffffff8105c860: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c960)
Location: arch/x86/kernel/apic/msi.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8106c960-ffffffff8106c9f0: hpet_assign_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hpet_assign_irq(struct irq_domain *domain, struct hpet_channel *hc, int dev_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106e060)
Location: arch/x86/kernel/apic/msi.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8106e060-ffffffff8106e0f0: hpet_assign_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hpet_channel *hc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hpet_dev *dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
