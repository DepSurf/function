# Function: <code>io_apic_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055f40)
Location: arch/x86/kernel/apic/io_apic.c:455
Inline: False
```
**Symbols:**

```
ffffffff81055f40-ffffffff81055f7d: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810561a0)
Location: arch/x86/kernel/apic/io_apic.c:455
Inline: False
```
**Symbols:**

```
ffffffff810561a0-ffffffff810561dd: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058f50)
Location: arch/x86/kernel/apic/io_apic.c:454
Inline: False
```
**Symbols:**

```
ffffffff81058f50-ffffffff81058f8d: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810585a0)
Location: arch/x86/kernel/apic/io_apic.c:454
Inline: False
```
**Symbols:**

```
ffffffff810585a0-ffffffff810585dd: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cab0)
Location: arch/x86/kernel/apic/io_apic.c:455
Inline: False
```
**Symbols:**

```
ffffffff8105cab0-ffffffff8105caed: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fb20)
Location: arch/x86/kernel/apic/io_apic.c:456
Inline: False
```
**Symbols:**

```
ffffffff8105fb20-ffffffff8105fb5d: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065790)
Location: arch/x86/kernel/apic/io_apic.c:456
Inline: False
```
**Symbols:**

```
ffffffff81065790-ffffffff810657cd: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81068ea0)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff81068ea0-ffffffff81068edd: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069820)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff81069820-ffffffff8106985d: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071369)
Location: arch/x86/kernel/apic/io_apic.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81070840-ffffffff8107087a: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072776)
Location: arch/x86/kernel/apic/io_apic.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81071c60-ffffffff81071c9a: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073246)
Location: arch/x86/kernel/apic/io_apic.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81072770-ffffffff810727aa: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f615)
Location: arch/x86/kernel/apic/io_apic.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff8107e6f0-ffffffff8107e747: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108f185)
Location: arch/x86/kernel/apic/io_apic.c:432
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff8108dde0-ffffffff8108de41: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3a05)
Location: arch/x86/kernel/apic/io_apic.c:432
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff810a2540-ffffffff810a25a1: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6ab7)
Location: arch/x86/kernel/apic/io_apic.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff810a5530-ffffffff810a5594: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810adb17)
Location: arch/x86/kernel/apic/io_apic.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff810ac5b0-ffffffff810ac614: io_apic_sync (STB_LOCAL)
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
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069310)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff81069310-ffffffff8106934d: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059670)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff81059670-ffffffff810596ad: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810697c0)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff810697c0-ffffffff810697fd: io_apic_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_apic_sync(struct irq_pin_list *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106aec0)
Location: arch/x86/kernel/apic/io_apic.c:457
Inline: False
```
**Symbols:**

```
ffffffff8106aec0-ffffffff8106aefd: io_apic_sync (STB_LOCAL)
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
