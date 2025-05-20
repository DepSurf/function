# Function: <code>kprobe_fault_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105edd0)
Location: arch/x86/kernel/kprobes/core.c:945
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8105edd0-ffffffff8105ef02: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ec00)
Location: arch/x86/kernel/kprobes/core.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8105ec00-ffffffff8105ed3d: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061c10)
Location: arch/x86/kernel/kprobes/core.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81061c10-ffffffff81061d4d: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81060bd0)
Location: arch/x86/kernel/kprobes/core.c:966
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81060bd0-ffffffff81060cef: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81064c20)
Location: arch/x86/kernel/kprobes/core.c:985
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81064c20-ffffffff81064d42: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81067810)
Location: arch/x86/kernel/kprobes/core.c:986
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81067810-ffffffff8106792e: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106d880)
Location: arch/x86/kernel/kprobes/core.c:971
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106d880-ffffffff8106d97c: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107277d-ffffffff81072790: kprobe_fault_handler.cold (STB_LOCAL)
ffffffff810718c0-ffffffff810719c2: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072900)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81072900-ffffffff81072a00: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81079980)
Location: arch/x86/kernel/kprobes/core.c:1007
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_kern_addr_fault
```
**Symbols:**

```
ffffffff81079980-ffffffff81079a80: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810799a0)
Location: arch/x86/kernel/kprobes/core.c:918
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810799a0-ffffffff81079aed: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107acf0)
Location: arch/x86/kernel/kprobes/core.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107acf0-ffffffff8107addd: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81088eb0)
Location: arch/x86/kernel/kprobes/core.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81088eb0-ffffffff81088f44: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81099160)
Location: arch/x86/kernel/kprobes/core.c:1018
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81099160-ffffffff81099200: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810af940)
Location: arch/x86/kernel/kprobes/core.c:991
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810af940-ffffffff810af9e0: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2960)
Location: arch/x86/kernel/kprobes/core.c:979
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810b2960-ffffffff810b2a00: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9dc0)
Location: arch/x86/kernel/kprobes/core.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810b9dc0-ffffffff810b9e60: kprobe_fault_handler (STB_GLOBAL)
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
int kprobe_fault_handler(struct pt_regs *regs, unsigned int fsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da86c0)
Location: arch/arm64/kernel/probes/kprobes.c:292
Inline: False
Direct callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffff800010da86c0-ffff800010da8810: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, unsigned int fsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/core.c (c0ea0818)
Location: arch/arm/probes/kprobes/core.c:329
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
```
**Symbols:**

```
c0ea0818-c0ea0904: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kprobes.c (c000000000056b40)
Location: arch/powerpc/kernel/kprobes.c:519
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
**Symbols:**

```
c000000000056b40-c000000000056ce0: kprobe_fault_handler (STB_GLOBAL)
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
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81071900)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81071900-ffffffff81071a00: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061910)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81061910-ffffffff81061a10: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810718b0)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810718b0-ffffffff810719b0: kprobe_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kprobe_fault_handler(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81073910)
Location: arch/x86/kernel/kprobes/core.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81073910-ffffffff81073a10: kprobe_fault_handler (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int fsr</code>
</li>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int fsr</code>
</li>
<li>
<b>Param removed. </b>
<code>int trapnr</code>
</li>
</ul>
</details>
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
