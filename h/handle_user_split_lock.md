# Function: <code>handle_user_split_lock</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e5a0)
Location: arch/x86/kernel/cpu/intel.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff8104e5a0-ffffffff8104e5d1: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104dae0)
Location: arch/x86/kernel/cpu/intel.c:1118
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff8104dae0-ffffffff8104db11: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f6a0)
Location: arch/x86/kernel/cpu/intel.c:1144
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff8104f6a0-ffffffff8104f6d1: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81057850)
Location: arch/x86/kernel/cpu/intel.c:1174
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff81057850-ffffffff81057881: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81063b60)
Location: arch/x86/kernel/cpu/intel.c:1239
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff81063b60-ffffffff81063b9d: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81072c70)
Location: arch/x86/kernel/cpu/intel.c:1424
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff81072c70-ffffffff81072cad: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81074850)
Location: arch/x86/kernel/cpu/intel.c:1424
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff81074850-ffffffff8107488d: handle_user_split_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool handle_user_split_lock(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107bd20)
Location: arch/x86/kernel/cpu/intel.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_alignment_check
```
**Symbols:**

```
ffffffff8107bd20-ffffffff8107bd5d: handle_user_split_lock (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
