# Function: <code>native_load_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064730)
Location: arch/x86/include/asm/desc.h:221
Inline: False
```
**Symbols:**

```
ffffffff81064730-ffffffff81064739: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064380)
Location: arch/x86/include/asm/desc.h:221
Inline: False
```
**Symbols:**

```
ffffffff81064380-ffffffff81064389: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067850)
Location: arch/x86/include/asm/desc.h:221
Inline: False
```
**Symbols:**

```
ffffffff81067850-ffffffff81067859: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066ae0)
Location: arch/x86/include/asm/desc.h:241
Inline: False
```
**Symbols:**

```
ffffffff81066ae0-ffffffff81066ae9: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106ac60)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff8106ac60-ffffffff8106ac69: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d920)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff8106d920-ffffffff8106d929: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073ac0)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff81073ac0-ffffffff81073ac9: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077630)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff81077630-ffffffff81077634: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810786a0)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff810786a0-ffffffff810786a4: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fb20)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff8107fb20-ffffffff8107fb24: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000750)
Location: arch/x86/include/asm/desc.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f740)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff8107f740-ffffffff8107f744: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000740)
Location: arch/x86/include/asm/desc.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080840)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81080840-ffffffff81080844: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810008a0)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085e0b)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f760)
Location: arch/x86/include/asm/desc.h:213
Inline: False
```
**Symbols:**

```
ffffffff8108f760-ffffffff8108f764: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000a03)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810961b1)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0470)
Location: arch/x86/include/asm/desc.h:213
Inline: False
```
**Symbols:**

```
ffffffff810a0470-ffffffff810a047a: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000a43)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abe41)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8030)
Location: arch/x86/include/asm/desc.h:213
Inline: False
```
**Symbols:**

```
ffffffff810b8030-ffffffff810b803a: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000b83)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afa01)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb1e0)
Location: arch/x86/include/asm/desc.h:213
Inline: False
```
**Symbols:**

```
ffffffff810bb1e0-ffffffff810bb1ea: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000b93)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6591)
Location: arch/x86/include/asm/desc.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c25f0)
Location: arch/x86/include/asm/desc.h:213
Inline: False
```
**Symbols:**

```
ffffffff810c25f0-ffffffff810c25fa: native_load_idt (STB_LOCAL)
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
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810776a0)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff810776a0-ffffffff810776a4: native_load_idt (STB_LOCAL)
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
In arch/x86/kernel/idt.c (ffffffff810224f2)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810366ae)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105406d)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff818637b8)
Location: arch/x86/include/asm/desc.h:217
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
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077650)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff81077650-ffffffff81077654: native_load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_load_idt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810796f0)
Location: arch/x86/include/asm/desc.h:217
Inline: False
```
**Symbols:**

```
ffffffff810796f0-ffffffff810796f4: native_load_idt (STB_LOCAL)
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
