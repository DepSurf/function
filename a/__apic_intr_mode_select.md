# Function: <code>__apic_intr_mode_select</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8657)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __apic_intr_mode_select();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdcf43)
Location: arch/x86/kernel/apic/apic.c:1286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff82cdcf43-ffffffff82cdd019: __apic_intr_mode_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __apic_intr_mode_select();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc92d7)
Location: arch/x86/kernel/apic/apic.c:1295
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff82fc92d7-ffffffff82fc93ad: __apic_intr_mode_select (STB_LOCAL)
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
In arch/x86/kernel/apic/apic.c (ffffffff831d43d4)
Location: arch/x86/kernel/apic/apic.c:1295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff832b6f60)
Location: arch/x86/kernel/apic/apic.c:1292
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff83468aa9)
Location: arch/x86/kernel/apic/apic.c:1301
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff83e8d2b5)
Location: arch/x86/kernel/apic/apic.c:1297
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff836b0b45)
Location: arch/x86/kernel/apic/apic.c:1299
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff838e1275)
Location: arch/x86/kernel/apic/apic.c:1264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff828a665e)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff8289e77e)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff828b956e)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
In arch/x86/kernel/apic/apic.c (ffffffff828b966f)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
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
