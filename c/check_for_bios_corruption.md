# Function: <code>check_for_bios_corruption</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/check.c (ffffffff81065350)
Location: arch/x86/kernel/check.c:119
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff81065350-ffffffff8106544d: check_for_bios_corruption.part.1 (STB_LOCAL)
ffffffff810654a0-ffffffff810654bb: check_for_bios_corruption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/check.c (ffffffff810650d0)
Location: arch/x86/kernel/check.c:119
Inline: True
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff810650d0-ffffffff810651cb: check_for_bios_corruption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/check.c (ffffffff81068600)
Location: arch/x86/kernel/check.c:119
Inline: True
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff81068600-ffffffff810686fb: check_for_bios_corruption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/check.c (ffffffff81067920)
Location: arch/x86/kernel/check.c:119
Inline: True
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff81067920-ffffffff81067a15: check_for_bios_corruption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/check.c (ffffffff8106bbb0)
Location: arch/x86/kernel/check.c:120
Inline: True
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff8106bbb0-ffffffff8106bca5: check_for_bios_corruption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/check.c (0)
Location: arch/x86/kernel/check.c:120
Inline: True
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff8106eb25-ffffffff8106eb70: check_for_bios_corruption.cold.2 (STB_LOCAL)
ffffffff8106ea00-ffffffff8106eab8: check_for_bios_corruption (STB_GLOBAL)
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
In arch/x86/kernel/check.c (ffffffff81074a25)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810785f5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff81079645)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/check.c (0)
Location: arch/x86/kernel/check.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff81080980-ffffffff81080a35: check_for_bios_corruption (STB_LOCAL)
ffffffff81080aba-ffffffff81080afd: check_for_bios_corruption.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_for_bios_corruption();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/check.c (0)
Location: arch/x86/kernel/check.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:check_corruption
```
**Symbols:**

```
ffffffff810804a0-ffffffff81080555: check_for_bios_corruption (STB_LOCAL)
ffffffff81bd824b-ffffffff81bd828e: check_for_bios_corruption.cold (STB_LOCAL)
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
In arch/x86/kernel/check.c (ffffffff81081375)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff81090325)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810a12d5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810b92a5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810bc475)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810c35f5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff81078645)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff81067e35)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff810785f5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
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
In arch/x86/kernel/check.c (ffffffff8107a6f5)
Location: arch/x86/kernel/check.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
