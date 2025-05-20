# Function: <code>generic_identify</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff81040b5f)
Location: arch/x86/kernel/cpu/common.c:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff810409c1)
Location: arch/x86/kernel/cpu/common.c:906
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81040405)
Location: arch/x86/kernel/cpu/common.c:910
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8103e39a)
Location: arch/x86/kernel/cpu/common.c:971
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81040f1c)
Location: arch/x86/kernel/cpu/common.c:1083
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81042882)
Location: arch/x86/kernel/cpu/common.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81043ea4)
Location: arch/x86/kernel/cpu/common.c:1197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81046411)
Location: arch/x86/kernel/cpu/common.c:1298
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81046b71)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void generic_identify(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a900)
Location: arch/x86/kernel/cpu/common.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8104a900-ffffffff8104ab25: generic_identify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void generic_identify(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049db0)
Location: arch/x86/kernel/cpu/common.c:1422
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81049db0-ffffffff81049fd5: generic_identify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generic_identify(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b660)
Location: arch/x86/kernel/cpu/common.c:1423
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8104b660-ffffffff8104b885: generic_identify (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff81052894)
Location: arch/x86/kernel/cpu/common.c:1460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8105e329)
Location: arch/x86/kernel/cpu/common.c:1693
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8106c8ef)
Location: arch/x86/kernel/cpu/common.c:1719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8106e2cc)
Location: arch/x86/kernel/cpu/common.c:1726
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8107558d)
Location: arch/x86/kernel/cpu/common.c:1772
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81046cf1)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81035d2d)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81046b31)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff81047f31)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
</ul>
