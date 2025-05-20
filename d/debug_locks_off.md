# Function: <code>debug_locks_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff813f87b0)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:oops_enter
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff813f87b0-ffffffff813f87e7: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff8143f640)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
**Symbols:**

```
ffffffff8143f640-ffffffff8143f677: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff8145c740)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
**Symbols:**

```
ffffffff8145c740-ffffffff8145c777: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81461970)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81461970-ffffffff814619a7: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff8148d870)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff8148d870-ffffffff8148d8a7: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff814c25f0)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff814c25f0-ffffffff814c2629: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff814d6c90)
Location: lib/debug_locks.c:38
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff814d6c90-ffffffff814d6cd6: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81502ad0)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81502ad0-ffffffff81502b0d: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81520a70)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81520a70-ffffffff81520aad: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81bbfac0)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81bbfac0-ffffffff81bbfafd: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81c38a80)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81c38a80-ffffffff81c38abd: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff815a78e0)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff815a78e0-ffffffff815a791d: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81610820)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81610820-ffffffff81610853: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff816dcd10)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff816dcd10-ffffffff816dcd4f: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff817ccb10)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff817ccb10-ffffffff817ccb4f: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff8180af20)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8180af20-ffffffff8180af5f: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81851700)
Location: lib/debug_locks.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/debug/debug_core.c:kgdb_panic
```
**Symbols:**

```
ffffffff81851700-ffffffff8185173f: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffff800010629fb0)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffff800010629fb0-ffff80001062a00c: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (c07d126c)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
c07d126c-c07d12ec: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (c0000000007cbdb0)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - arch/powerpc/kernel/traps.c:panic_flush_kmsg_end
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
c0000000007cbdb0-c0000000007cbe34: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffe00045aa68)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffe00045aa68-ffffffe00045aaaa: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81519050)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81519050-ffffffff8151908d: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff81509350)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff81509350-ffffffff8150938d: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff815150e0)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff815150e0-ffffffff8151511d: debug_locks_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int debug_locks_off();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/debug_locks.c (ffffffff8152e850)
Location: lib/debug_locks.c:39
Inline: True
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
**Symbols:**

```
ffffffff8152e850-ffffffff8152e88d: debug_locks_off (STB_GLOBAL)
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
