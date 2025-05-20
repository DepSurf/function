# Function: <code>ioapic_setup_resources</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72eca)
Location: arch/x86/kernel/apic/io_apic.c:2565
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b6cf)
Location: arch/x86/kernel/apic/io_apic.c:2566
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6c18)
Location: arch/x86/kernel/apic/io_apic.c:2567
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7920)
Location: arch/x86/kernel/apic/io_apic.c:2565
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826be2cb)
Location: arch/x86/kernel/apic/io_apic.c:2575
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826e808d)
Location: arch/x86/kernel/apic/io_apic.c:2568
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ebd6)
Location: arch/x86/kernel/apic/io_apic.c:2568
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6acf)
Location: arch/x86/kernel/apic/io_apic.c:2626
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9fa4)
Location: arch/x86/kernel/apic/io_apic.c:2629
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *ioapic_setup_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdeae0)
Location: arch/x86/kernel/apic/io_apic.c:2622
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff82cdeae0-ffffffff82cdeba6: ioapic_setup_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *ioapic_setup_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcac7a)
Location: arch/x86/kernel/apic/io_apic.c:2645
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
**Symbols:**

```
ffffffff82fcac7a-ffffffff82fcad42: ioapic_setup_resources (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5e8e)
Location: arch/x86/kernel/apic/io_apic.c:2647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8af1)
Location: arch/x86/kernel/apic/io_apic.c:2647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a862)
Location: arch/x86/kernel/apic/io_apic.c:2648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f875)
Location: arch/x86/kernel/apic/io_apic.c:2648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff836b3115)
Location: arch/x86/kernel/apic/io_apic.c:2650
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff838e39f5)
Location: arch/x86/kernel/apic/io_apic.c:2646
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7fbc)
Location: arch/x86/kernel/apic/io_apic.c:2635
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a0093)
Location: arch/x86/kernel/apic/io_apic.c:2629
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828baebb)
Location: arch/x86/kernel/apic/io_apic.c:2629
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bafd1)
Location: arch/x86/kernel/apic/io_apic.c:2629
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
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
