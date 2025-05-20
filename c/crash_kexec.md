# Function: <code>crash_kexec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110d930)
Location: kernel/kexec_core.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - kernel/panic.c:panic
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8110d930-ffffffff8110da51: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811154b0)
Location: kernel/kexec_core.c:904
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff811154b0-ffffffff811154fb: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111cbd0)
Location: kernel/kexec_core.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8111cbd0-ffffffff8111cc1b: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111e480)
Location: kernel/kexec_core.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8111e480-ffffffff8111e4cc: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81129bd0)
Location: kernel/kexec_core.c:951
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81129bd0-ffffffff81129c21: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81137b20)
Location: kernel/kexec_core.c:955
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81137b20-ffffffff81137b71: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81143340)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81143340-ffffffff81143391: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114e690)
Location: kernel/kexec_core.c:960
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8114e690-ffffffff8114e6d5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115a3a0)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8115a3a0-ffffffff8115a3e5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116b170)
Location: kernel/kexec_core.c:968
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8116b170-ffffffff8116b1b5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811678b0)
Location: kernel/kexec_core.c:967
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811678b0-ffffffff811678f5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81168640)
Location: kernel/kexec_core.c:968
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81168640-ffffffff81168685: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118e380)
Location: kernel/kexec_core.c:969
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8118e380-ffffffff8118e3b4: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bd910)
Location: kernel/kexec_core.c:989
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811bd910-ffffffff811bd958: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811ff940)
Location: kernel/kexec_core.c:978
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811ff940-ffffffff811ff988: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81214db0)
Location: kernel/kexec_core.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81214db0-ffffffff81214df8: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122cd50)
Location: kernel/kexec_core.c:1059
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8122cd50-ffffffff8122cd95: crash_kexec (STB_GLOBAL)
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
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c99a8)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
```
**Symbols:**

```
ffff8000101c99a8-ffff8000101c9a48: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c04109d0)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:die
```
**Symbols:**

```
c04109d0-c0410a44: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0000000002323f0)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
**Symbols:**

```
c0000000002323f0-c000000000232488: crash_kexec (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811529c0)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff811529c0-ffffffff81152a05: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81145ca0)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81145ca0-ffffffff81145ce5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81150870)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81150870-ffffffff811508b5: crash_kexec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crash_kexec(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115d690)
Location: kernel/kexec_core.c:962
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8115d690-ffffffff8115d6d5: crash_kexec (STB_GLOBAL)
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
