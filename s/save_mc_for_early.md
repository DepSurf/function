# Function: <code>save_mc_for_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int save_mc_for_early(u8 *mc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d6f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
**Symbols:**

```
ffffffff8104d6f0-ffffffff8104d7e3: save_mc_for_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void save_mc_for_early(u8 *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d680)
Location: arch/x86/kernel/cpu/microcode/intel.c:471
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
**Symbols:**

```
ffffffff8104d680-ffffffff8104d77b: save_mc_for_early (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104feb4)
Location: arch/x86/kernel/cpu/microcode/intel.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104ff0b)
Location: arch/x86/kernel/cpu/microcode/intel.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810538d9)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105659e)
Location: arch/x86/kernel/cpu/microcode/intel.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053c2e)
Location: arch/x86/kernel/cpu/microcode/intel.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056dd8)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810576b7)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c977)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b1f7)
Location: arch/x86/kernel/cpu/microcode/intel.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105bba7)
Location: arch/x86/kernel/cpu/microcode/intel.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810651dd)
Location: arch/x86/kernel/cpu/microcode/intel.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071c45)
Location: arch/x86/kernel/cpu/microcode/intel.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810818da)
Location: arch/x86/kernel/cpu/microcode/intel.c:272
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083e13)
Location: arch/x86/kernel/cpu/microcode/intel.c:272
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
</details>
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057237)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047427)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057667)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058b07)
Location: arch/x86/kernel/cpu/microcode/intel.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
