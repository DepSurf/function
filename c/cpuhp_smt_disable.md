# Function: <code>cpuhp_smt_disable</code>

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
In kernel/cpu.c (ffffffff8109101f)
Location: kernel/cpu.c:2036
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
In kernel/cpu.c (ffffffff810993af)
Location: kernel/cpu.c:2058
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dcf0)
Location: kernel/cpu.c:2074
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109dcf0-ffffffff8109dd9c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4240)
Location: kernel/cpu.c:1936
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a4240-ffffffff810a42ec: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab4f0)
Location: kernel/cpu.c:2067
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810ab4f0-ffffffff810ab59c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6d70)
Location: kernel/cpu.c:2078
Inline: False
Direct callers:
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a6d70-ffffffff810a6e1c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7e30)
Location: kernel/cpu.c:2181
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a7e30-ffffffff810a7edc: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b98c0)
Location: kernel/cpu.c:2212
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810b98c0-ffffffff810b996c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810d0330)
Location: kernel/cpu.c:2234
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810d0330-ffffffff810d03f7: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eeb70)
Location: kernel/cpu.c:2258
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810eeb70-ffffffff810eec51: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fab50)
Location: kernel/cpu.c:2643
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810fab50-ffffffff810fac01: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103f70)
Location: kernel/cpu.c:2689
Inline: False
Direct callers:
  - kernel/cpu.c:control_store
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff81103f70-ffffffff81104028: cpuhp_smt_disable (STB_GLOBAL)
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109db60)
Location: kernel/cpu.c:1936
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109db60-ffffffff8109dc0c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c580)
Location: kernel/cpu.c:1936
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8108c580-ffffffff8108c62c: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109db10)
Location: kernel/cpu.c:1936
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109db10-ffffffff8109dbbc: cpuhp_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5a00)
Location: kernel/cpu.c:1936
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a5a00-ffffffff810a5aac: cpuhp_smt_disable (STB_GLOBAL)
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
