# Function: <code>setup_IO_APIC_irqs</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f73504)
Location: arch/x86/kernel/apic/io_apic.c:1225
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9bd30)
Location: arch/x86/kernel/apic/io_apic.c:1226
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd7279)
Location: arch/x86/kernel/apic/io_apic.c:1225
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7f93)
Location: arch/x86/kernel/apic/io_apic.c:1203
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826be950)
Location: arch/x86/kernel/apic/io_apic.c:1205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826e871e)
Location: arch/x86/kernel/apic/io_apic.c:1206
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8289f273)
Location: arch/x86/kernel/apic/io_apic.c:1206
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b7193)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba668)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_IO_APIC_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdf64a)
Location: arch/x86/kernel/apic/io_apic.c:1196
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff82cdf64a-ffffffff82cdf6db: setup_IO_APIC_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_IO_APIC_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb9ee)
Location: arch/x86/kernel/apic/io_apic.c:1205
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff82fcb9ee-ffffffff82fcba7f: setup_IO_APIC_irqs (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff831d63a2)
Location: arch/x86/kernel/apic/io_apic.c:1205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff832b9029)
Location: arch/x86/kernel/apic/io_apic.c:1205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8346ada6)
Location: arch/x86/kernel/apic/io_apic.c:1206
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff83e90119)
Location: arch/x86/kernel/apic/io_apic.c:1206
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff836b39a9)
Location: arch/x86/kernel/apic/io_apic.c:1207
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff838e42a6)
Location: arch/x86/kernel/apic/io_apic.c:1207
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a8680)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a0753)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bb57f)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bb695)
Location: arch/x86/kernel/apic/io_apic.c:1209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
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
