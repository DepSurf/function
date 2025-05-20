# Function: <code>ftrace_int3_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105af20)
Location: arch/x86/kernel/ftrace.c:283
Inline: False
```
**Symbols:**

```
ffffffff8105af20-ffffffff8105af8e: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105afd0)
Location: arch/x86/kernel/ftrace.c:286
Inline: False
```
**Symbols:**

```
ffffffff8105afd0-ffffffff8105b03e: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105de10)
Location: arch/x86/kernel/ftrace.c:286
Inline: False
```
**Symbols:**

```
ffffffff8105de10-ffffffff8105de7e: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105d4a0)
Location: arch/x86/kernel/ftrace.c:286
Inline: False
```
**Symbols:**

```
ffffffff8105d4a0-ffffffff8105d4ec: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81061160)
Location: arch/x86/kernel/ftrace.c:287
Inline: False
```
**Symbols:**

```
ffffffff81061160-ffffffff810611b0: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81064280)
Location: arch/x86/kernel/ftrace.c:287
Inline: False
```
**Symbols:**

```
ffffffff81064280-ffffffff810642cd: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81069f20)
Location: arch/x86/kernel/ftrace.c:290
Inline: False
```
**Symbols:**

```
ffffffff81069f20-ffffffff81069f6d: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106d1c0)
Location: arch/x86/kernel/ftrace.c:304
Inline: False
```
**Symbols:**

```
ffffffff8106d1c0-ffffffff8106d28c: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e9b0)
Location: arch/x86/kernel/ftrace.c:304
Inline: True
```
**Symbols:**

```
ffffffff8106e9b0-ffffffff8106ea7c: ftrace_int3_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106d950)
Location: arch/x86/kernel/ftrace.c:304
Inline: True
```
**Symbols:**

```
ffffffff8106d950-ffffffff8106da1c: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105dd70)
Location: arch/x86/kernel/ftrace.c:304
Inline: True
```
**Symbols:**

```
ffffffff8105dd70-ffffffff8105de3c: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106de00)
Location: arch/x86/kernel/ftrace.c:304
Inline: True
```
**Symbols:**

```
ffffffff8106de00-ffffffff8106decc: ftrace_int3_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ftrace_int3_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81070080)
Location: arch/x86/kernel/ftrace.c:304
Inline: True
```
**Symbols:**

```
ffffffff81070080-ffffffff8107014c: ftrace_int3_handler (STB_GLOBAL)
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
