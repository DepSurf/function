# Function: <code>arch_ftrace_trampoline_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105b650)
Location: arch/x86/kernel/ftrace.c:925
Inline: False
```
**Symbols:**

```
ffffffff8105b650-ffffffff8105b67e: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105b710)
Location: arch/x86/kernel/ftrace.c:931
Inline: False
```
**Symbols:**

```
ffffffff8105b710-ffffffff8105b73f: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105e550)
Location: arch/x86/kernel/ftrace.c:931
Inline: False
```
**Symbols:**

```
ffffffff8105e550-ffffffff8105e57f: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105dbb0)
Location: arch/x86/kernel/ftrace.c:945
Inline: True
```
**Symbols:**

```
ffffffff8105dbb0-ffffffff8105dc11: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81061870)
Location: arch/x86/kernel/ftrace.c:946
Inline: True
```
**Symbols:**

```
ffffffff81061870-ffffffff810618d1: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81064870)
Location: arch/x86/kernel/ftrace.c:946
Inline: True
```
**Symbols:**

```
ffffffff81064870-ffffffff810648d0: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106a500)
Location: arch/x86/kernel/ftrace.c:936
Inline: False
```
**Symbols:**

```
ffffffff8106a500-ffffffff8106a560: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106dda0)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff8106dda0-ffffffff8106ddd1: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106f3b0)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff8106f3b0-ffffffff8106f3e1: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81076550)
Location: arch/x86/kernel/ftrace.c:569
Inline: False
```
**Symbols:**

```
ffffffff81076550-ffffffff81076587: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81076b80)
Location: arch/x86/kernel/ftrace.c:577
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff81076b80-ffffffff81076bb7: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810775e0)
Location: arch/x86/kernel/ftrace.c:577
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff810775e0-ffffffff81077617: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81084de0)
Location: arch/x86/kernel/ftrace.c:577
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff81084de0-ffffffff81084e17: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81094ff0)
Location: arch/x86/kernel/ftrace.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff81094ff0-ffffffff81095039: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810aaac0)
Location: arch/x86/kernel/ftrace.c:576
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff810aaac0-ffffffff810aab09: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810ade70)
Location: arch/x86/kernel/ftrace.c:572
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff810ade70-ffffffff810adeb9: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810b49f0)
Location: arch/x86/kernel/ftrace.c:572
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff810b49f0-ffffffff810b4a39: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2648
Inline: False
```
**Symbols:**

```
ffff8000102131c8-ffff8000102131cc: arch_ftrace_trampoline_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2648
Inline: False
```
**Symbols:**

```
c0451f2c-c0451f3c: arch_ftrace_trampoline_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000293430)
Location: kernel/trace/ftrace.c:2648
Inline: False
```
**Symbols:**

```
c000000000293430-c000000000293434: arch_ftrace_trampoline_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2648
Inline: False
```
**Symbols:**

```
ffffffe00017349a-ffffffe0001734a6: arch_ftrace_trampoline_free (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e350)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff8106e350-ffffffff8106e381: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105e770)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff8105e770-ffffffff8105e7a1: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e800)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff8106e800-ffffffff8106e831: arch_ftrace_trampoline_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_ftrace_trampoline_free(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81070a80)
Location: arch/x86/kernel/ftrace.c:967
Inline: False
```
**Symbols:**

```
ffffffff81070a80-ffffffff81070ab1: arch_ftrace_trampoline_free (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
