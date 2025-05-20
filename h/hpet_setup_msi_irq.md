# Function: <code>hpet_setup_msi_irq</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074cea)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff81075cba)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d080)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
**Symbols:**

```
ffffffff8107d080-ffffffff8107d12b: hpet_setup_msi_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107cfa0)
Location: arch/x86/kernel/hpet.c:635
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
**Symbols:**

```
ffffffff8107cfa0-ffffffff8107d04b: hpet_setup_msi_irq.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff8107e19a)
Location: arch/x86/kernel/hpet.c:635
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff8108cc25)
Location: arch/x86/kernel/hpet.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff8109d85d)
Location: arch/x86/kernel/hpet.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff810b496d)
Location: arch/x86/kernel/hpet.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff810b7a3d)
Location: arch/x86/kernel/hpet.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff810bee7d)
Location: arch/x86/kernel/hpet.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff81074cba)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff81064cea)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff81074c6a)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff81076cca)
Location: arch/x86/kernel/hpet.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
</details>
</li>
</ul>

## Differences
