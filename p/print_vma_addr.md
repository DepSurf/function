# Function: <code>print_vma_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1f40)
Location: mm/memory.c:3759
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff811c1f40-ffffffff811c203d: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dda80)
Location: mm/memory.c:3954
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff811dda80-ffffffff811ddb7d: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed8d0)
Location: mm/memory.c:4035
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff811ed8d0-ffffffff811ed9cd: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8880)
Location: mm/memory.c:4325
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff811f8880-ffffffff811f897f: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210a80)
Location: mm/memory.c:4503
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81210a80-ffffffff81210b85: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4551
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81231c43-ffffffff81231ca6: print_vma_addr.cold.105 (STB_LOCAL)
ffffffff812314a0-ffffffff8123155a: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4341
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81245413-ffffffff81245476: print_vma_addr.cold.96 (STB_LOCAL)
ffffffff81244c70-ffffffff81244d2a: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4396
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81257498-ffffffff812574fb: print_vma_addr.cold (STB_LOCAL)
ffffffff81256c30-ffffffff81256ce9: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff812659ea-ffffffff81265a4d: print_vma_addr.cold (STB_LOCAL)
ffffffff812651c0-ffffffff81265279: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4786
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81295d0e-ffffffff81295d71: print_vma_addr.cold (STB_LOCAL)
ffffffff81295590-ffffffff81295649: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5013
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81be7936-ffffffff81be799a: print_vma_addr.cold (STB_LOCAL)
ffffffff812a0430-ffffffff812a053d: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5080
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81bd9797-ffffffff81bd97fb: print_vma_addr.cold (STB_LOCAL)
ffffffff812a5d70-ffffffff812a5e7a: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5226
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81cbc633-ffffffff81cbc697: print_vma_addr.cold (STB_LOCAL)
ffffffff812e7200-ffffffff812e72f4: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:5533
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81e6e285-ffffffff81e6e2e9: print_vma_addr.cold (STB_LOCAL)
ffffffff81348490-ffffffff813485a6: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0940)
Location: mm/memory.c:5613
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff813c0940-ffffffff813c0aa5: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f56c0)
Location: mm/memory.c:5819
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff813f56c0-ffffffff813f582b: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141f3a0)
Location: mm/memory.c:6043
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/cet.c:do_user_cp_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8141f3a0-ffffffff8141f50b: print_vma_addr (STB_GLOBAL)
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
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fbbc8)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_show_signal
```
**Symbols:**

```
ffff8000102fbbc8-ffff8000102fbcc8: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051c278)
Location: mm/memory.c:4421
Inline: False
```
**Symbols:**

```
c051c278-c051c378: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c70e0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:show_signal_msg
```
**Symbols:**

```
c0000000003c70e0-c0000000003c7254: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b1ce)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffe00020b1ce-ffffffe00020b2a6: print_vma_addr (STB_GLOBAL)
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
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8125e03a-ffffffff8125e09d: print_vma_addr.cold (STB_LOCAL)
ffffffff8125d810-ffffffff8125d8c9: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff812504be-ffffffff81250521: print_vma_addr.cold (STB_LOCAL)
ffffffff8124fc60-ffffffff8124fd19: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8125bdda-ffffffff8125be3d: print_vma_addr.cold (STB_LOCAL)
ffffffff8125b5b0-ffffffff8125b669: print_vma_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_vma_addr(char *prefix, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8126b7c3-ffffffff8126b826: print_vma_addr.cold (STB_LOCAL)
ffffffff8126af90-ffffffff8126b049: print_vma_addr (STB_GLOBAL)
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
