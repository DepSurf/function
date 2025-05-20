# Function: <code>irq_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056290)
Location: arch/x86/kernel/apic/io_apic.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
```
**Symbols:**

```
ffffffff81056290-ffffffff810562f0: irq_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056500)
Location: arch/x86/kernel/apic/io_apic.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81056500-ffffffff8105655c: irq_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810592b0)
Location: arch/x86/kernel/apic/io_apic.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff810592b0-ffffffff8105930c: irq_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058910)
Location: arch/x86/kernel/apic/io_apic.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81058910-ffffffff8105896d: irq_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cd90)
Location: arch/x86/kernel/apic/io_apic.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8105cd90-ffffffff8105cdea: irq_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8105fd60-ffffffff8105fdac: irq_trigger (STB_LOCAL)
ffffffff81062052-ffffffff81062068: irq_trigger.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff810659d0-ffffffff81065a8a: irq_trigger (STB_LOCAL)
ffffffff81067d32-ffffffff81067d5d: irq_trigger.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81069180-ffffffff8106923a: irq_trigger (STB_LOCAL)
ffffffff8106b4a8-ffffffff8106b4e6: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81069b00-ffffffff81069bba: irq_trigger (STB_LOCAL)
ffffffff8106be4b-ffffffff8106be89: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:830
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81071520-ffffffff810715de: irq_trigger (STB_LOCAL)
ffffffff81073181-ffffffff810731bf: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff810695f0-ffffffff810696aa: irq_trigger (STB_LOCAL)
ffffffff8106b93b-ffffffff8106b979: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81059950-ffffffff81059a0a: irq_trigger (STB_LOCAL)
ffffffff8105bc6b-ffffffff8105bca9: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81069aa0-ffffffff81069b5a: irq_trigger (STB_LOCAL)
ffffffff8106bdeb-ffffffff8106be29: irq_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int irq_trigger(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8106b220-ffffffff8106b2da: irq_trigger (STB_LOCAL)
ffffffff8106d4eb-ffffffff8106d529: irq_trigger.cold (STB_LOCAL)
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
