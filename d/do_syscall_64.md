# Function: <code>do_syscall_64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003b40)
Location: arch/x86/entry/common.c:271
Inline: False
```
**Symbols:**

```
ffffffff81003b40-ffffffff81003bf7: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003b10)
Location: arch/x86/entry/common.c:263
Inline: False
```
**Symbols:**

```
ffffffff81003b10-ffffffff81003bcf: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810039a0)
Location: arch/x86/entry/common.c:267
Inline: False
```
**Symbols:**

```
ffffffff810039a0-ffffffff81003a5f: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003a70)
Location: arch/x86/entry/common.c:269
Inline: False
```
**Symbols:**

```
ffffffff81003a70-ffffffff81003b9d: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004270)
Location: arch/x86/entry/common.c:272
Inline: False
```
**Symbols:**

```
ffffffff81004270-ffffffff81004373: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810042a0)
Location: arch/x86/entry/common.c:272
Inline: False
```
**Symbols:**

```
ffffffff810042a0-ffffffff810043a3: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004470)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff81004470-ffffffff8100459e: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004470)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff81004470-ffffffff810045f5: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81bbc6b0)
Location: arch/x86/entry/common.c:376
Inline: False
```
**Symbols:**

```
ffffffff81bbc6b0-ffffffff81bbc768: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81c34d00)
Location: arch/x86/entry/common.c:39
Inline: False
```
**Symbols:**

```
ffffffff81c34d00-ffffffff81c34d83: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81c27120)
Location: arch/x86/entry/common.c:39
Inline: False
```
**Symbols:**

```
ffffffff81c27120-ffffffff81c271cc: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81d45160)
Location: arch/x86/entry/common.c:73
Inline: False
```
**Symbols:**

```
ffffffff81d45160-ffffffff81d45211: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81f13110)
Location: arch/x86/entry/common.c:73
Inline: False
```
**Symbols:**

```
ffffffff81f13110-ffffffff81f13198: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff820ba140)
Location: arch/x86/entry/common.c:73
Inline: False
```
**Symbols:**

```
ffffffff820ba140-ffffffff820ba1c8: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_syscall_64(struct pt_regs *regs, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff82139950)
Location: arch/x86/entry/common.c:73
Inline: False
```
**Symbols:**

```
ffffffff82139950-ffffffff821399d9: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool do_syscall_64(struct pt_regs *regs, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8221b710)
Location: arch/x86/entry/common.c:76
Inline: False
```
**Symbols:**

```
ffffffff8221b710-ffffffff8221b885: do_syscall_64 (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004470)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff81004470-ffffffff810045f5: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810029d0)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff810029d0-ffffffff81002bca: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004430)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff81004430-ffffffff810045b5: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_syscall_64(long unsigned int nr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004570)
Location: arch/x86/entry/common.c:278
Inline: False
```
**Symbols:**

```
ffffffff81004570-ffffffff810046f5: do_syscall_64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs</code> ➡️ <code>nr, regs</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>nr, regs</code> ➡️ <code>regs, nr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int nr</code> ➡️ <code>int nr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
