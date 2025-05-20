# Function: <code>__mc_scan_banks</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a498)
Location: arch/x86/kernel/cpu/mce/core.c:1107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d622)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dfc6)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mc_scan_banks(struct mce *m, struct mce *final, long unsigned int *toclear, long unsigned int *valid_banks, int no_way_out, int *worst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052790)
Location: arch/x86/kernel/cpu/mce/core.c:1105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81052790-ffffffff81052a76: __mc_scan_banks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mc_scan_banks(struct mce *m, struct pt_regs *regs, struct mce *final, long unsigned int *toclear, long unsigned int *valid_banks, int no_way_out, int *worst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051a30)
Location: arch/x86/kernel/cpu/mce/core.c:1171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81051a30-ffffffff81051d20: __mc_scan_banks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mc_scan_banks(struct mce *m, struct pt_regs *regs, struct mce *final, long unsigned int *toclear, long unsigned int *valid_banks, int no_way_out, int *worst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053200)
Location: arch/x86/kernel/cpu/mce/core.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81053200-ffffffff810534f0: __mc_scan_banks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mc_scan_banks(struct mce *m, struct pt_regs *regs, struct mce *final, long unsigned int *toclear, long unsigned int *valid_banks, int no_way_out, int *worst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b800)
Location: arch/x86/kernel/cpu/mce/core.c:1203
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff8105b800-ffffffff8105baf0: __mc_scan_banks (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f163c5)
Location: arch/x86/kernel/cpu/mce/core.c:1223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd98d)
Location: arch/x86/kernel/cpu/mce/core.c:1223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213f43a)
Location: arch/x86/kernel/cpu/mce/core.c:1232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8222145a)
Location: arch/x86/kernel/cpu/mce/core.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e126)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d5f6)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104df76)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f3b6)
Location: arch/x86/kernel/cpu/mce/core.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *regs</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, final, toclear, valid_banks, no_way_out, worst</code> ➡️ <code>m, regs, final, toclear, valid_banks, no_way_out, worst</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
