# Function: <code>native_load_gdt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064720)
Location: arch/x86/include/asm/desc.h:216
Inline: False
```
**Symbols:**

```
ffffffff81064720-ffffffff81064729: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064370)
Location: arch/x86/include/asm/desc.h:216
Inline: False
```
**Symbols:**

```
ffffffff81064370-ffffffff81064379: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067840)
Location: arch/x86/include/asm/desc.h:216
Inline: False
```
**Symbols:**

```
ffffffff81067840-ffffffff81067849: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066ad0)
Location: arch/x86/include/asm/desc.h:236
Inline: False
```
**Symbols:**

```
ffffffff81066ad0-ffffffff81066ad9: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106ac50)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff8106ac50-ffffffff8106ac59: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d910)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff8106d910-ffffffff8106d919: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073ab0)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81073ab0-ffffffff81073ab9: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077620)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81077620-ffffffff81077624: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078690)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81078690-ffffffff81078694: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fb10)
Location: arch/x86/include/asm/desc.h:207
Inline: False
```
**Symbols:**

```
ffffffff8107fb10-ffffffff8107fb14: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000705)
Location: arch/x86/include/asm/desc.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f730)
Location: arch/x86/include/asm/desc.h:207
Inline: False
```
**Symbols:**

```
ffffffff8107f730-ffffffff8107f734: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810006f5)
Location: arch/x86/include/asm/desc.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080830)
Location: arch/x86/include/asm/desc.h:207
Inline: False
```
**Symbols:**

```
ffffffff81080830-ffffffff81080834: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000855)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085e13)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f750)
Location: arch/x86/include/asm/desc.h:208
Inline: False
```
**Symbols:**

```
ffffffff8108f750-ffffffff8108f754: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810009b5)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810961b9)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0460)
Location: arch/x86/include/asm/desc.h:208
Inline: False
```
**Symbols:**

```
ffffffff810a0460-ffffffff810a046a: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810009f5)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abe49)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8010)
Location: arch/x86/include/asm/desc.h:208
Inline: False
```
**Symbols:**

```
ffffffff810b8010-ffffffff810b801a: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000b35)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afa09)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb1c0)
Location: arch/x86/include/asm/desc.h:208
Inline: False
```
**Symbols:**

```
ffffffff810bb1c0-ffffffff810bb1ca: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000b45)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6599)
Location: arch/x86/include/asm/desc.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c25d0)
Location: arch/x86/include/asm/desc.h:208
Inline: False
```
**Symbols:**

```
ffffffff810c25d0-ffffffff810c25da: native_load_gdt (STB_LOCAL)
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
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077690)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81077690-ffffffff81077694: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103668e)
Location: arch/x86/include/asm/desc.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077640)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff81077640-ffffffff81077644: native_load_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_load_gdt(const struct desc_ptr *dtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810796e0)
Location: arch/x86/include/asm/desc.h:212
Inline: False
```
**Symbols:**

```
ffffffff810796e0-ffffffff810796e4: native_load_gdt (STB_LOCAL)
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
