# Function: <code>native_write_cr2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064520)
Location: arch/x86/include/asm/special_insns.h:42
Inline: False
```
**Symbols:**

```
ffffffff81064520-ffffffff81064529: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064170)
Location: arch/x86/include/asm/special_insns.h:42
Inline: False
```
**Symbols:**

```
ffffffff81064170-ffffffff81064179: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067660)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff81067660-ffffffff81067669: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066920)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff81066920-ffffffff81066929: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106aaf0)
Location: arch/x86/include/asm/special_insns.h:38
Inline: False
```
**Symbols:**

```
ffffffff8106aaf0-ffffffff8106aaf9: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d7d0)
Location: arch/x86/include/asm/special_insns.h:38
Inline: False
```
**Symbols:**

```
ffffffff8106d7d0-ffffffff8106d7d9: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073970)
Location: arch/x86/include/asm/special_insns.h:38
Inline: False
```
**Symbols:**

```
ffffffff81073970-ffffffff81073979: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810774e0)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff810774e0-ffffffff810774e4: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078570)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff81078570-ffffffff81078574: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f990)
Location: arch/x86/include/asm/special_insns.h:38
Inline: False
```
**Symbols:**

```
ffffffff8107f990-ffffffff8107f994: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f5c0)
Location: arch/x86/include/asm/special_insns.h:40
Inline: False
```
```
In arch/x86/kernel/sev-es.c (ffffffff82fd1656)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff8107f5c0-ffffffff8107f5c4: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810806d0)
Location: arch/x86/include/asm/special_insns.h:40
Inline: False
```
```
In arch/x86/kernel/sev.c (ffffffff831dc30b)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff810806d0-ffffffff810806d4: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f5f0)
Location: arch/x86/include/asm/special_insns.h:40
Inline: False
```
```
In arch/x86/kernel/sev.c (ffffffff832bf3c1)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff8108f5f0-ffffffff8108f5f4: native_write_cr2 (STB_LOCAL)
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
In arch/x86/kernel/paravirt.c (ffffffff81f17bb0)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_write_cr2
```
```
In arch/x86/kernel/sev.c (ffffffff834717fe)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
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
In arch/x86/kernel/paravirt.c (ffffffff820bf2f0)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_write_cr2
```
```
In arch/x86/kernel/sev.c (ffffffff83e98a12)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff82140f00)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_write_cr2
```
```
In arch/x86/kernel/sev.c (ffffffff836bc3d5)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff82222e30)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_write_cr2
```
```
In arch/x86/kernel/sev.c (ffffffff838ece45)
Location: arch/x86/include/asm/special_insns.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
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
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077570)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff81077570-ffffffff81077574: native_write_cr2 (STB_LOCAL)
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
In arch/x86/kernel/nmi.c (ffffffff81026096)
Location: arch/x86/include/asm/special_insns.h:37
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818637a2)
Location: arch/x86/include/asm/special_insns.h:37
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077520)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff81077520-ffffffff81077524: native_write_cr2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_write_cr2(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810795c0)
Location: arch/x86/include/asm/special_insns.h:37
Inline: False
```
**Symbols:**

```
ffffffff810795c0-ffffffff810795c4: native_write_cr2 (STB_LOCAL)
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
