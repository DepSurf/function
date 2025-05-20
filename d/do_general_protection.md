# Function: <code>do_general_protection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f4f0)
Location: arch/x86/kernel/traps.c:441
Inline: False
```
**Symbols:**

```
ffffffff8102f4f0-ffffffff8102f635: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e5f0)
Location: arch/x86/kernel/traps.c:426
Inline: False
```
**Symbols:**

```
ffffffff8102e5f0-ffffffff8102e73e: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e530)
Location: arch/x86/kernel/traps.c:487
Inline: False
```
**Symbols:**

```
ffffffff8102e530-ffffffff8102e67e: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c500)
Location: arch/x86/kernel/traps.c:522
Inline: False
```
**Symbols:**

```
ffffffff8102c500-ffffffff8102c65a: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d6b0)
Location: arch/x86/kernel/traps.c:533
Inline: False
```
**Symbols:**

```
ffffffff8102d6b0-ffffffff8102d82b: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:534
Inline: False
```
**Symbols:**

```
ffffffff8102ef0f-ffffffff8102ef60: do_general_protection.cold.13 (STB_LOCAL)
ffffffff8102e550-ffffffff8102e67f: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f860)
Location: arch/x86/kernel/traps.c:521
Inline: False
```
**Symbols:**

```
ffffffff8102f860-ffffffff8102f9b7: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031650)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81031650-ffffffff810317a3: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031f10)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81031f10-ffffffff81032063: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032070)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81032070-ffffffff810321c3: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81021750)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81021750-ffffffff81021894: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031ed0)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81031ed0-ffffffff81032023: do_general_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_general_protection(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032da0)
Location: arch/x86/kernel/traps.c:518
Inline: False
```
**Symbols:**

```
ffffffff81032da0-ffffffff81032f23: do_general_protection (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
