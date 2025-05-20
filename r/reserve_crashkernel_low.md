# Function: <code>reserve_crashkernel_low</code>

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
In arch/x86/kernel/setup.c (ffffffff81f66835)
Location: arch/x86/kernel/setup.c:500
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81f8e686)
Location: arch/x86/kernel/setup.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81fc9a1e)
Location: arch/x86/kernel/setup.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff820aa162)
Location: arch/x86/kernel/setup.c:484
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826b0c36)
Location: arch/x86/kernel/setup.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826da2f6)
Location: arch/x86/kernel/setup.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828906db)
Location: arch/x86/kernel/setup.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828a72c6)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff828aa2fe)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reserve_crashkernel_low();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82ccf51d)
Location: arch/x86/kernel/setup.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82ccf51d-ffffffff82ccf66b: reserve_crashkernel_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reserve_crashkernel_low();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82fbb39b)
Location: arch/x86/kernel/setup.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82fbb39b-ffffffff82fbb4c0: reserve_crashkernel_low (STB_LOCAL)
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
In arch/x86/kernel/setup.c (ffffffff831c5bb4)
Location: arch/x86/kernel/setup.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff832a6b24)
Location: arch/x86/kernel/setup.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff83455db5)
Location: arch/x86/kernel/setup.c:434
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff83e73e82)
Location: arch/x86/kernel/setup.c:509
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff83695952)
Location: arch/x86/kernel/setup.c:503
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In kernel/crash_core.c (ffffffff8390690a)
Location: kernel/crash_core.c:363
Inline: True
Inline callers:
  - kernel/crash_core.c:reserve_crashkernel_generic
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
In arch/x86/kernel/setup.c (ffffffff8289830e)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff8289061e)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff828ab2fe)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
In arch/x86/kernel/setup.c (ffffffff828ab30e)
Location: arch/x86/kernel/setup.c:477
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
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
