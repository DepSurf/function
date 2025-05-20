# Function: <code>cpuhp_smt_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109110b)
Location: kernel/cpu.c:2068
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109949b)
Location: kernel/cpu.c:2090
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dda0)
Location: kernel/cpu.c:2106
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109dda0-ffffffff8109de5e: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a42f0)
Location: kernel/cpu.c:1968
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a42f0-ffffffff810a43ae: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab5a0)
Location: kernel/cpu.c:2099
Inline: False
Direct callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810ab5a0-ffffffff810ab65e: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6e20)
Location: kernel/cpu.c:2110
Inline: False
Direct callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a6e20-ffffffff810a6ede: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7ee0)
Location: kernel/cpu.c:2213
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a7ee0-ffffffff810a7f9e: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9970)
Location: kernel/cpu.c:2244
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810b9970-ffffffff810b9a4c: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810d0400)
Location: kernel/cpu.c:2266
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810d0400-ffffffff810d04dc: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eec70)
Location: kernel/cpu.c:2290
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810eec70-ffffffff810eed68: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fac20)
Location: kernel/cpu.c:2675
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810fac20-ffffffff810fad18: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81104040)
Location: kernel/cpu.c:2727
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff81104040-ffffffff81104138: cpuhp_smt_enable (STB_GLOBAL)
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
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dc10)
Location: kernel/cpu.c:1968
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109dc10-ffffffff8109dcce: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c630)
Location: kernel/cpu.c:1968
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8108c630-ffffffff8108c6ee: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dbc0)
Location: kernel/cpu.c:1968
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109dbc0-ffffffff8109dc7e: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuhp_smt_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5ab0)
Location: kernel/cpu.c:1968
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a5ab0-ffffffff810a5b6e: cpuhp_smt_enable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
