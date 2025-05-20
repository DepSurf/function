# Function: <code>apic_pending_intr_clear</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105c40e)
Location: arch/x86/kernel/apic/apic.c:1415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff81062090)
Location: arch/x86/kernel/apic/apic.c:1421
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff81065740)
Location: arch/x86/kernel/apic/apic.c:1498
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff81065ddd)
Location: arch/x86/kernel/apic/apic.c:1578
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106c808)
Location: arch/x86/kernel/apic/apic.c:1530
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff8106dfb8)
Location: arch/x86/kernel/apic/apic.c:1542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff8106e9ed)
Location: arch/x86/kernel/apic/apic.c:1542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff8107a36d)
Location: arch/x86/kernel/apic/apic.c:1539
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void apic_pending_intr_clear();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1547
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
**Symbols:**

```
ffffffff81089350-ffffffff810894c8: apic_pending_intr_clear (STB_LOCAL)
ffffffff81e4ce38-ffffffff81e4ce51: apic_pending_intr_clear.cold (STB_LOCAL)
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
In arch/x86/kernel/apic/apic.c (ffffffff8109d1dd)
Location: arch/x86/kernel/apic/apic.c:1543
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff810a017d)
Location: arch/x86/kernel/apic/apic.c:1545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff810a77c6)
Location: arch/x86/kernel/apic/apic.c:1505
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff810658cd)
Location: arch/x86/kernel/apic/apic.c:1578
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff81055c4d)
Location: arch/x86/kernel/apic/apic.c:1578
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff81065d7d)
Location: arch/x86/kernel/apic/apic.c:1578
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
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
In arch/x86/kernel/apic/apic.c (ffffffff8106735d)
Location: arch/x86/kernel/apic/apic.c:1578
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
