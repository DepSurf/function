# Function: <code>do_device_not_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f1b0)
Location: arch/x86/kernel/traps.c:750
Inline: True
```
**Symbols:**

```
ffffffff8102f1b0-ffffffff8102f1e5: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e210)
Location: arch/x86/kernel/traps.c:793
Inline: False
```
**Symbols:**

```
ffffffff8102e210-ffffffff8102e230: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e100)
Location: arch/x86/kernel/traps.c:854
Inline: False
```
**Symbols:**

```
ffffffff8102e100-ffffffff8102e173: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c230)
Location: arch/x86/kernel/traps.c:884
Inline: False
```
**Symbols:**

```
ffffffff8102c230-ffffffff8102c28e: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d140)
Location: arch/x86/kernel/traps.c:890
Inline: False
```
**Symbols:**

```
ffffffff8102d140-ffffffff8102d1a9: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e130)
Location: arch/x86/kernel/traps.c:894
Inline: False
```
**Symbols:**

```
ffffffff8102e130-ffffffff8102e192: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f2a0)
Location: arch/x86/kernel/traps.c:881
Inline: False
```
**Symbols:**

```
ffffffff8102f2a0-ffffffff8102f302: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031090)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff81031090-ffffffff810310fc: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031950)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff81031950-ffffffff810319bc: do_device_not_available (STB_GLOBAL)
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
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031ab0)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff81031ab0-ffffffff81031b1c: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810215a0)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff810215a0-ffffffff810215e4: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031910)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff81031910-ffffffff8103197c: do_device_not_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_device_not_available(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810327d0)
Location: arch/x86/kernel/traps.c:878
Inline: False
```
**Symbols:**

```
ffffffff810327d0-ffffffff8103283c: do_device_not_available (STB_GLOBAL)
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
