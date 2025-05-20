# Function: <code>native_read_cr2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064510)
Location: arch/x86/include/asm/special_insns.h:35
Inline: False
```
**Symbols:**

```
ffffffff81064510-ffffffff81064519: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064160)
Location: arch/x86/include/asm/special_insns.h:35
Inline: False
```
**Symbols:**

```
ffffffff81064160-ffffffff81064169: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067650)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81067650-ffffffff81067659: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066910)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81066910-ffffffff81066919: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106aae0)
Location: arch/x86/include/asm/special_insns.h:31
Inline: False
```
**Symbols:**

```
ffffffff8106aae0-ffffffff8106aae9: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d7c0)
Location: arch/x86/include/asm/special_insns.h:31
Inline: False
```
**Symbols:**

```
ffffffff8106d7c0-ffffffff8106d7c9: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073960)
Location: arch/x86/include/asm/special_insns.h:31
Inline: False
```
**Symbols:**

```
ffffffff81073960-ffffffff81073969: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810774d0)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff810774d0-ffffffff810774d4: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078560)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81078560-ffffffff81078564: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f980)
Location: arch/x86/include/asm/special_insns.h:31
Inline: False
```
**Symbols:**

```
ffffffff8107f980-ffffffff8107f984: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae536)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f5b0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: False
```
**Symbols:**

```
ffffffff8107f5b0-ffffffff8107f5b4: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b8536)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
```
In arch/x86/kernel/paravirt.c (ffffffff810806c0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: False
```
**Symbols:**

```
ffffffff810806c0-ffffffff810806c4: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff832985b0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f5e0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: False
```
**Symbols:**

```
ffffffff8108f5e0-ffffffff8108f5e4: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff834465d5)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
```
In arch/x86/kernel/paravirt.c (ffffffff81f17ba0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_read_cr2
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83e5f75c)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
```
In arch/x86/kernel/paravirt.c (ffffffff820bf2d0)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_read_cr2
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff836949ac)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff838c489c)
Location: arch/x86/include/asm/special_insns.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:do_early_exception
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
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077560)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81077560-ffffffff81077564: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81020486)
Location: arch/x86/include/asm/special_insns.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff81025f1b)
Location: arch/x86/include/asm/special_insns.h:30
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828a621c)
Location: arch/x86/include/asm/special_insns.h:30
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8186361e)
Location: arch/x86/include/asm/special_insns.h:30
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077510)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81077510-ffffffff81077514: native_read_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int native_read_cr2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810795b0)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff810795b0-ffffffff810795b4: native_read_cr2 (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
