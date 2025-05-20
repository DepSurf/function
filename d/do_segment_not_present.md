# Function: <code>do_segment_not_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102fa90)
Location: arch/x86/kernel/traps.c:306
Inline: False
```
**Symbols:**

```
ffffffff8102fa90-ffffffff8102fab2: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102eb30)
Location: arch/x86/kernel/traps.c:291
Inline: False
```
**Symbols:**

```
ffffffff8102eb30-ffffffff8102eb52: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ea70)
Location: arch/x86/kernel/traps.c:291
Inline: False
```
**Symbols:**

```
ffffffff8102ea70-ffffffff8102ea92: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102cd80)
Location: arch/x86/kernel/traps.c:326
Inline: False
```
**Symbols:**

```
ffffffff8102cd80-ffffffff8102cda2: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102db40)
Location: arch/x86/kernel/traps.c:318
Inline: False
```
**Symbols:**

```
ffffffff8102db40-ffffffff8102db62: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102eb20)
Location: arch/x86/kernel/traps.c:319
Inline: False
```
**Symbols:**

```
ffffffff8102eb20-ffffffff8102eb42: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102fd50)
Location: arch/x86/kernel/traps.c:293
Inline: False
```
**Symbols:**

```
ffffffff8102fd50-ffffffff8102fd78: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031b20)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff81031b20-ffffffff81031b48: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810323e0)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff810323e0-ffffffff81032408: do_segment_not_present (STB_GLOBAL)
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
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032540)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff81032540-ffffffff81032568: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81021ea0)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff81021ea0-ffffffff81021ec8: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810323a0)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff810323a0-ffffffff810323c8: do_segment_not_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_segment_not_present(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810332e0)
Location: arch/x86/kernel/traps.c:294
Inline: False
```
**Symbols:**

```
ffffffff810332e0-ffffffff81033308: do_segment_not_present (STB_GLOBAL)
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
