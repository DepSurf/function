# Function: <code>quick_pit_calibrate</code>

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
In arch/x86/kernel/tsc.c (ffffffff81037f09)
Location: arch/x86/kernel/tsc.c:579
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
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
In arch/x86/kernel/tsc.c (ffffffff81037211)
Location: arch/x86/kernel/tsc.c:574
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
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
In arch/x86/kernel/tsc.c (ffffffff81036fa1)
Location: arch/x86/kernel/tsc.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
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
In arch/x86/kernel/tsc.c (ffffffff8103507e)
Location: arch/x86/kernel/tsc.c:484
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
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
In arch/x86/kernel/tsc.c (ffffffff810373ce)
Location: arch/x86/kernel/tsc.c:484
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
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
In arch/x86/kernel/tsc.c (ffffffff810383d3)
Location: arch/x86/kernel/tsc.c:499
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
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
In arch/x86/kernel/tsc.c (ffffffff810396af)
Location: arch/x86/kernel/tsc.c:516
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8103bb61)
Location: arch/x86/kernel/tsc.c:519
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8103c411)
Location: arch/x86/kernel/tsc.c:519
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:526
Inline: False
```
**Symbols:**

```
ffffffff8103ebb0-ffffffff8103ed03: quick_pit_calibrate (STB_LOCAL)
ffffffff8103f7bc-ffffffff8103f7fd: quick_pit_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:526
Inline: False
```
**Symbols:**

```
ffffffff8103ec60-ffffffff8103edb3: quick_pit_calibrate (STB_LOCAL)
ffffffff81bd4247-ffffffff81bd4288: quick_pit_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:527
Inline: False
```
**Symbols:**

```
ffffffff81040510-ffffffff81040663: quick_pit_calibrate (STB_LOCAL)
ffffffff81bc6766-ffffffff81bc67a7: quick_pit_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:527
Inline: False
```
**Symbols:**

```
ffffffff81046380-ffffffff810464d3: quick_pit_calibrate (STB_LOCAL)
ffffffff81c999a4-ffffffff81c999e5: quick_pit_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:527
Inline: False
```
**Symbols:**

```
ffffffff8104f2b0-ffffffff8104f409: quick_pit_calibrate (STB_LOCAL)
ffffffff81e495ae-ffffffff81e495fb: quick_pit_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105bf80)
Location: arch/x86/kernel/tsc.c:527
Inline: False
```
**Symbols:**

```
ffffffff8105bf80-ffffffff8105c121: quick_pit_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105da70)
Location: arch/x86/kernel/tsc.c:563
Inline: False
```
**Symbols:**

```
ffffffff8105da70-ffffffff8105dc34: quick_pit_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int quick_pit_calibrate();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81064b30)
Location: arch/x86/kernel/tsc.c:563
Inline: False
```
**Symbols:**

```
ffffffff81064b30-ffffffff81064cf4: quick_pit_calibrate (STB_LOCAL)
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
In arch/x86/kernel/tsc.c (ffffffff8103c571)
Location: arch/x86/kernel/tsc.c:521
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8102ba3f)
Location: arch/x86/kernel/tsc.c:519
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8103c3d1)
Location: arch/x86/kernel/tsc.c:519
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8103d421)
Location: arch/x86/kernel/tsc.c:519
Inline: True
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
