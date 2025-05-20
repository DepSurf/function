# Function: <code>int3_selftest</code>

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
In arch/x86/kernel/alternative.c (ffffffff828aa17a)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
In arch/x86/kernel/alternative.c (ffffffff828ad1dd)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff82cd24ff)
Location: arch/x86/kernel/alternative.c:667
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff82cd24ff-ffffffff82cd2567: int3_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff82fbe346)
Location: arch/x86/kernel/alternative.c:670
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff82fbe346-ffffffff82fbe3ae: int3_selftest (STB_LOCAL)
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
In arch/x86/kernel/alternative.c (ffffffff831c8a79)
Location: arch/x86/kernel/alternative.c:566
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
In arch/x86/kernel/alternative.c (ffffffff832a9cb8)
Location: arch/x86/kernel/alternative.c:566
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff834593bc)
Location: arch/x86/kernel/alternative.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff834593bc-ffffffff8345942c: int3_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff83e78ba0)
Location: arch/x86/kernel/alternative.c:1309
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff83e78ba0-ffffffff83e78c10: int3_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8369b1d0)
Location: arch/x86/kernel/alternative.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff8369b1d0-ffffffff8369b240: int3_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void int3_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff838caed0)
Location: arch/x86/kernel/alternative.c:1610
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff838caed0-ffffffff838caf40: int3_selftest (STB_LOCAL)
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
In arch/x86/kernel/alternative.c (ffffffff8289b1ef)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
In arch/x86/kernel/alternative.c (ffffffff828934ad)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
In arch/x86/kernel/alternative.c (ffffffff828ae1cf)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
In arch/x86/kernel/alternative.c (ffffffff828ae1ed)
Location: arch/x86/kernel/alternative.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
