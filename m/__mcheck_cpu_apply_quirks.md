# Function: <code>__mcheck_cpu_apply_quirks</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046745)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1475
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104674d)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1534
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810482ed)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047bd4)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1572
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b65c)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1581
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104df8c)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1559
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b67c)
Location: arch/x86/kernel/cpu/mce/core.c:1575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e5d0)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ef70)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff810519e0-ffffffff81051be7: __mcheck_cpu_apply_quirks (STB_LOCAL)
ffffffff81053b63-ffffffff81053b79: __mcheck_cpu_apply_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff81050ca0-ffffffff81050ebe: __mcheck_cpu_apply_quirks (STB_LOCAL)
ffffffff81bd56e7-ffffffff81bd56fd: __mcheck_cpu_apply_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1716
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff81052680-ffffffff81052847: __mcheck_cpu_apply_quirks (STB_LOCAL)
ffffffff81bc7b20-ffffffff81bc7b37: __mcheck_cpu_apply_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1779
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff8105ac40-ffffffff8105ae07: __mcheck_cpu_apply_quirks (STB_LOCAL)
ffffffff81c9b619-ffffffff81c9b630: __mcheck_cpu_apply_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1814
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff81066da0-ffffffff81066f95: __mcheck_cpu_apply_quirks (STB_LOCAL)
ffffffff81e4aa88-ffffffff81e4aaab: __mcheck_cpu_apply_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810762f0)
Location: arch/x86/kernel/cpu/mce/core.c:1814
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff810762f0-ffffffff81076511: __mcheck_cpu_apply_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078470)
Location: arch/x86/kernel/cpu/mce/core.c:1827
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff81078470-ffffffff81078697: __mcheck_cpu_apply_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mcheck_cpu_apply_quirks(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f920)
Location: arch/x86/kernel/cpu/mce/core.c:1858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff8107f920-ffffffff8107fb47: __mcheck_cpu_apply_quirks (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f0d0)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e5ce)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ef20)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050360)
Location: arch/x86/kernel/cpu/mce/core.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
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
