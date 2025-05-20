# Function: <code>kgdb_handle_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811302e0)
Location: kernel/debug/debug_core.c:691
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811302e0-ffffffff811304b7: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811385f0)
Location: kernel/debug/debug_core.c:691
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811385f0-ffffffff811387c3: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81142380)
Location: kernel/debug/debug_core.c:691
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81142380-ffffffff81142553: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143bc0)
Location: kernel/debug/debug_core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81143bc0-ffffffff81143d7b: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150870)
Location: kernel/debug/debug_core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81150870-ffffffff81150a31: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8115f90b-ffffffff8115f930: kgdb_handle_exception.cold.23 (STB_LOCAL)
ffffffff8115f410-ffffffff8115f5b7: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8116c67b-ffffffff8116c6a0: kgdb_handle_exception.cold.23 (STB_LOCAL)
ffffffff8116c150-ffffffff8116c2f9: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811794b7-ffffffff811794dc: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff81178f60-ffffffff81179106: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81185347-ffffffff8118536c: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff81184db0-ffffffff81184f56: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81198ff0)
Location: kernel/debug/debug_core.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81198ff0-ffffffff811990ec: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811963f0)
Location: kernel/debug/debug_core.c:828
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811963f0-ffffffff811964f4: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811973b0)
Location: kernel/debug/debug_core.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811973b0-ffffffff811974ac: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c0ff0)
Location: kernel/debug/debug_core.c:824
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811c0ff0-ffffffff811c10ff: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f45a0)
Location: kernel/debug/debug_core.c:848
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff811f45a0-ffffffff811f46c4: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123b4c0)
Location: kernel/debug/debug_core.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8123b4c0-ffffffff8123b5e4: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812524d0)
Location: kernel/debug/debug_core.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff812524d0-ffffffff812525f4: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126c320)
Location: kernel/debug/debug_core.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8126c320-ffffffff8126c444: kgdb_handle_exception (STB_GLOBAL)
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
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fa920)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/arm64/kernel/kgdb.c:kgdb_notify
  - arch/arm64/kernel/kgdb.c:kgdb_compiled_brk_fn
  - arch/arm64/kernel/kgdb.c:kgdb_brk_fn
```
**Symbols:**

```
ffff8000101fa920-ffff8000101fab28: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043a9f4)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/arm/kernel/kgdb.c:kgdb_notify
  - arch/arm/kernel/kgdb.c:kgdb_compiled_brk_fn
  - arch/arm/kernel/kgdb.c:kgdb_brk_fn
```
**Symbols:**

```
c043a9f4-c043ac30: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c0000000002723b0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/powerpc/kernel/kgdb.c:kgdb_debugger
  - arch/powerpc/kernel/kgdb.c:kgdb_debugger
```
**Symbols:**

```
c0000000002723b0-c000000000272658: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8117d967-ffffffff8117d98c: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff8117d3d0-ffffffff8117d576: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81170ab7-ffffffff81170adc: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff81170520-ffffffff811706c6: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff8117b737-ffffffff8117b75c: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff8117b1a0-ffffffff8117b346: kgdb_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kgdb_handle_exception(int evector, int signo, int ecode, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:753
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
**Symbols:**

```
ffffffff81189057-ffffffff8118907c: kgdb_handle_exception.cold (STB_LOCAL)
ffffffff81188ac0-ffffffff81188c66: kgdb_handle_exception (STB_GLOBAL)
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
