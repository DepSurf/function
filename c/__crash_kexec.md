# Function: <code>__crash_kexec</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (ffffffff81115370)
Location: kernel/kexec_core.c:881
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81115370-ffffffff81115477: __crash_kexec.part.6 (STB_LOCAL)
ffffffff81115480-ffffffff811154a8: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111ca90)
Location: kernel/kexec_core.c:883
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8111ca90-ffffffff8111cb97: __crash_kexec.part.9 (STB_LOCAL)
ffffffff8111cba0-ffffffff8111cbc8: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111e3e0)
Location: kernel/kexec_core.c:917
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8111e3e0-ffffffff8111e473: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81128e50)
Location: kernel/kexec_core.c:927
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81128e50-ffffffff81128ee3: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81136930)
Location: kernel/kexec_core.c:931
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81136930-ffffffff81136a56: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811424b0)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff811424b0-ffffffff811425ce: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114d8d0)
Location: kernel/kexec_core.c:936
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8114d8d0-ffffffff8114d9ee: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811595e0)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff811595e0-ffffffff811596fe: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81169e60)
Location: kernel/kexec_core.c:944
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81169e60-ffffffff81169f7e: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811665a0)
Location: kernel/kexec_core.c:943
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff811665a0-ffffffff811666be: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167340)
Location: kernel/kexec_core.c:944
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81167340-ffffffff8116745e: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118cbb0)
Location: kernel/kexec_core.c:945
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8118cbb0-ffffffff8118ccce: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bc0f0)
Location: kernel/kexec_core.c:965
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff811bc0f0-ffffffff811bc220: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811fe0c0)
Location: kernel/kexec_core.c:954
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff811fe0c0-ffffffff811fe165: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81213380)
Location: kernel/kexec_core.c:1047
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81213380-ffffffff81213425: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122b2b0)
Location: kernel/kexec_core.c:1035
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8122b2b0-ffffffff8122b355: __crash_kexec (STB_GLOBAL)
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
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c9888)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffff8000101c9888-ffff8000101c99a8: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c04108f8)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
c04108f8-c04109d0: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0000000002322e0)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
c0000000002322e0-c0000000002323ec: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (0)
Location: include/linux/kexec.h:396
Inline: True
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
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81151c00)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81151c00-ffffffff81151d1e: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81144ee0)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff81144ee0-ffffffff81144ffe: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114fab0)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8114fab0-ffffffff8114fbce: __crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115c910)
Location: kernel/kexec_core.c:938
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/kexec_core.c:crash_kexec
```
**Symbols:**

```
ffffffff8115c910-ffffffff8115ca2e: __crash_kexec (STB_GLOBAL)
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
