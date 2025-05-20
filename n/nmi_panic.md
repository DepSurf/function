# Function: <code>nmi_panic</code>

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
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082ba0)
Location: kernel/panic.c:82
Inline: False
```
**Symbols:**

```
ffffffff81082ba0-ffffffff81082bd9: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087610)
Location: kernel/panic.c:108
Inline: False
```
**Symbols:**

```
ffffffff81087610-ffffffff81087649: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810844a0)
Location: kernel/panic.c:109
Inline: False
```
**Symbols:**

```
ffffffff810844a0-ffffffff810844d9: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108ae80)
Location: kernel/panic.c:112
Inline: False
```
**Symbols:**

```
ffffffff8108ae80-ffffffff8108aeb9: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:113
Inline: False
```
**Symbols:**

```
ffffffff8108ec10-ffffffff8108ec1c: nmi_panic.cold.9 (STB_LOCAL)
ffffffff8108e660-ffffffff8108e693: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:121
Inline: False
```
**Symbols:**

```
ffffffff81096fb0-ffffffff81096fbc: nmi_panic.cold.9 (STB_LOCAL)
ffffffff810968f0-ffffffff81096923: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:123
Inline: False
```
**Symbols:**

```
ffffffff8109b55c-ffffffff8109b568: nmi_panic.cold (STB_LOCAL)
ffffffff8109ae80-ffffffff8109aeb3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffff810a1a88-ffffffff810a1a94: nmi_panic.cold (STB_LOCAL)
ffffffff810a13a0-ffffffff810a13d3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff810a88a1-ffffffff810a88ad: nmi_panic.cold (STB_LOCAL)
ffffffff810a81e0-ffffffff810a8213: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff81bdb459-ffffffff81bdb465: nmi_panic.cold (STB_LOCAL)
ffffffff810a3f30-ffffffff810a3f63: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff81bcd54b-ffffffff81bcd557: nmi_panic.cold (STB_LOCAL)
ffffffff810a4b80-ffffffff810a4bb3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff81ca3d12-ffffffff81ca3d1e: nmi_panic.cold (STB_LOCAL)
ffffffff810b63a0-ffffffff810b63d3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81e534c2)
Location: kernel/panic.c:161
Inline: True
```
**Symbols:**

```
ffffffff81e534c2-ffffffff81e534ce: nmi_panic.cold (STB_LOCAL)
ffffffff810cc910-ffffffff810cc95b: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea6e0)
Location: kernel/panic.c:193
Inline: True
```
**Symbols:**

```
ffffffff810ea6e0-ffffffff810ea733: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f62d0)
Location: kernel/panic.c:193
Inline: True
Direct callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
**Symbols:**

```
ffffffff810f62d0-ffffffff810f6315: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff680)
Location: kernel/panic.c:193
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
**Symbols:**

```
ffffffff810ff680-ffffffff810ff6c2: nmi_panic (STB_GLOBAL)
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
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6498)
Location: kernel/panic.c:124
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_serror_panic
  - arch/arm64/kernel/traps.c:handle_bad_stack
```
**Symbols:**

```
ffff8000100f6498-ffff8000100f652c: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c0354614)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
c0354614-c035468c: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c2b0)
Location: kernel/panic.c:124
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
**Symbols:**

```
c00000000013c2b0-c00000000013c33c: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c21d4)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffe0000c21d4-ffffffe0000c2242: nmi_panic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffff8109b3a8-ffffffff8109b3b4: nmi_panic.cold (STB_LOCAL)
ffffffff8109acc0-ffffffff8109acf3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffff81089ddc-ffffffff81089de8: nmi_panic.cold (STB_LOCAL)
ffffffff81089700-ffffffff81089733: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffff8109b358-ffffffff8109b364: nmi_panic.cold (STB_LOCAL)
ffffffff8109ac70-ffffffff8109aca3: nmi_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void nmi_panic(struct pt_regs *regs, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:124
Inline: False
```
**Symbols:**

```
ffffffff810a2fcf-ffffffff810a2fdb: nmi_panic.cold (STB_LOCAL)
ffffffff810a28e0-ffffffff810a2913: nmi_panic (STB_GLOBAL)
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
