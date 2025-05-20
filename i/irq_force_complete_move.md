# Function: <code>irq_force_complete_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055b80)
Location: arch/x86/kernel/apic/vector.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81055b80-ffffffff81055c7b: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055d90)
Location: arch/x86/kernel/apic/vector.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81055d90-ffffffff81055eb5: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058b30)
Location: arch/x86/kernel/apic/vector.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81058b30-ffffffff81058c69: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058190)
Location: arch/x86/kernel/apic/vector.c:683
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81058190-ffffffff810582bc: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c690)
Location: arch/x86/kernel/apic/vector.c:920
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8105c690-ffffffff8105c708: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:936
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8105f7da-ffffffff8105f7f0: irq_force_complete_move.cold.25 (STB_LOCAL)
ffffffff8105f6f0-ffffffff8105f75b: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:927
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8106544a-ffffffff81065460: irq_force_complete_move.cold.24 (STB_LOCAL)
ffffffff81065360-ffffffff810653cb: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:924
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81068b66-ffffffff81068b7a: irq_force_complete_move.cold (STB_LOCAL)
ffffffff81068a40-ffffffff81068aab: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810694ec-ffffffff81069500: irq_force_complete_move.cold (STB_LOCAL)
ffffffff810693b0-ffffffff8106941b: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff810704c6-ffffffff810704da: irq_force_complete_move.cold (STB_LOCAL)
ffffffff81070380-ffffffff810703f7: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:987
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81bd70a4-ffffffff81bd70b8: irq_force_complete_move.cold (STB_LOCAL)
ffffffff810718e0-ffffffff81071957: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1020
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81bc925c-ffffffff81bc9270: irq_force_complete_move.cold (STB_LOCAL)
ffffffff810723e0-ffffffff81072457: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1020
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81c9dd48-ffffffff81c9dd5c: irq_force_complete_move.cold (STB_LOCAL)
ffffffff8107e2c0-ffffffff8107e337: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:1020
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81e4d1d3-ffffffff81e4d1e7: irq_force_complete_move.cold (STB_LOCAL)
ffffffff8108d960-ffffffff8108d9e3: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a20a0)
Location: arch/x86/kernel/apic/vector.c:1016
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff810a20a0-ffffffff810a2130: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a5080)
Location: arch/x86/kernel/apic/vector.c:1016
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff810a5080-ffffffff810a5110: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810ac110)
Location: arch/x86/kernel/apic/vector.c:1074
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff810ac110-ffffffff810ac1a0: irq_force_complete_move (STB_GLOBAL)
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
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:593
Inline: True
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
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:593
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:593
Inline: True
```
</details>
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
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81068fdc-ffffffff81068ff0: irq_force_complete_move.cold (STB_LOCAL)
ffffffff81068ea0-ffffffff81068f0b: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8105934c-ffffffff81059360: irq_force_complete_move.cold (STB_LOCAL)
ffffffff81059210-ffffffff8105927b: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8106948c-ffffffff810694a0: irq_force_complete_move.cold (STB_LOCAL)
ffffffff81069350-ffffffff810693bb: irq_force_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void irq_force_complete_move(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:935
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8106ab8a-ffffffff8106ab9e: irq_force_complete_move.cold (STB_LOCAL)
ffffffff8106aa50-ffffffff8106aab9: irq_force_complete_move (STB_GLOBAL)
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
