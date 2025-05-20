# Function: <code>__startup_pirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c84e0)
Location: drivers/xen/events/events_base.c:504
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff814c84e0-ffffffff814c8630: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518fe0)
Location: drivers/xen/events/events_base.c:515
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81518fe0-ffffffff81519130: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815454b0)
Location: drivers/xen/events/events_base.c:514
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff815454b0-ffffffff81545600: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559360)
Location: drivers/xen/events/events_base.c:506
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81559360-ffffffff815594aa: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd780)
Location: drivers/xen/events/events_base.c:506
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff815bd780-ffffffff815bd8d3: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:506
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff815f5e20-ffffffff815f5f5d: __startup_pirq (STB_LOCAL)
ffffffff815f75ac-ffffffff815f75dc: __startup_pirq.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:506
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81610ee0-ffffffff81611018: __startup_pirq (STB_LOCAL)
ffffffff81612665-ffffffff81612697: __startup_pirq.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:507
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81644c60-ffffffff81644d86: __startup_pirq (STB_LOCAL)
ffffffff8164641a-ffffffff8164645e: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:507
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81667210-ffffffff81667336: __startup_pirq (STB_LOCAL)
ffffffff81668936-ffffffff8166897a: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:521
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:restore_pirqs
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81716f90-ffffffff817170cf: __startup_pirq (STB_LOCAL)
ffffffff81718a29-ffffffff81718a5b: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:841
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:restore_pirqs
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff817345e0-ffffffff817347ab: __startup_pirq (STB_LOCAL)
ffffffff81c04f3a-ffffffff81c04f6c: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:872
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81717e60-ffffffff8171802b: __startup_pirq (STB_LOCAL)
ffffffff81bf6bc4-ffffffff81bf6bf6: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:872
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff817957b0-ffffffff81795a18: __startup_pirq (STB_LOCAL)
ffffffff81cf5868-ffffffff81cf58a9: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:872
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff818ce510-ffffffff818ce7a5: __startup_pirq (STB_LOCAL)
ffffffff81ebd9a9-ffffffff81ebd9e8: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1fab0)
Location: drivers/xen/events/events_base.c:874
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81a1fab0-ffffffff81a1fd84: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a68e40)
Location: drivers/xen/events/events_base.c:866
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81a68e40-ffffffff81a69114: __startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int __startup_pirq(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ab9f50)
Location: drivers/xen/events/events_base.c:861
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81ab9f50-ffffffff81aba0d6: __startup_pirq (STB_LOCAL)
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
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830f38)
Location: drivers/xen/events/events_base.c:507
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffff800010830f38-ffff8000108310b0: __startup_pirq (STB_LOCAL)
```
</details>
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
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:511
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_restore_pirqs
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff8162cf40-ffffffff8162d066: __startup_pirq (STB_LOCAL)
ffffffff8162e766-ffffffff8162e7aa: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:507
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff8165b050-ffffffff8165b176: __startup_pirq (STB_LOCAL)
ffffffff8165c776-ffffffff8165c7ba: __startup_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int __startup_pirq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:507
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:startup_pirq
```
**Symbols:**

```
ffffffff81675640-ffffffff81675766: __startup_pirq (STB_LOCAL)
ffffffff81676d66-ffffffff81676daa: __startup_pirq.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int irq</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
