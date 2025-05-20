# Function: <code>smp_callin</code>

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
In arch/x86/kernel/smpboot.c (ffffffff810515c2)
Location: arch/x86/kernel/smpboot.c:149
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81051773)
Location: arch/x86/kernel/smpboot.c:153
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff810540c3)
Location: arch/x86/kernel/smpboot.c:162
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81053a13)
Location: arch/x86/kernel/smpboot.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81057775)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff8105a655)
Location: arch/x86/kernel/smpboot.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff810602d5)
Location: arch/x86/kernel/smpboot.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81063bdc)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff8106428c)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smp_callin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106aca0)
Location: arch/x86/kernel/smpboot.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106aca0-ffffffff8106ad5e: smp_callin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smp_callin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c970)
Location: arch/x86/kernel/smpboot.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106c970-ffffffff8106ca30: smp_callin (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff8106d44e)
Location: arch/x86/kernel/smpboot.c:162
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81078b6c)
Location: arch/x86/kernel/smpboot.c:162
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff8108796c)
Location: arch/x86/kernel/smpboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff8109b0ec)
Location: arch/x86/kernel/smpboot.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smp_callin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smpboot.c (ffffffe00000359c)
Location: arch/riscv/kernel/smpboot.c:136
Inline: False
```
**Symbols:**

```
ffffffe00000359c-ffffffe00000361e: smp_callin (STB_GLOBAL)
```
</details>
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
In arch/x86/kernel/smpboot.c (ffffffff81063d7c)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff81054085)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff8106422c)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/smpboot.c (ffffffff810657f3)
Location: arch/x86/kernel/smpboot.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
<b>Arch</b>
<ul>
</ul>
