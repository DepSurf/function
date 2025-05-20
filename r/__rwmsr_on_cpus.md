# Function: <code>__rwmsr_on_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b890)
Location: arch/x86/lib/msr-smp.c:97
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
```
**Symbols:**

```
ffffffff8141b890-ffffffff8141b91e: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463a50)
Location: arch/x86/lib/msr-smp.c:97
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff81463a50-ffffffff81463ada: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482cf0)
Location: arch/x86/lib/msr-smp.c:97
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff81482cf0-ffffffff81482d7a: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c440)
Location: arch/x86/lib/msr-smp.c:97
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff8148c440-ffffffff8148c4d1: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c8530)
Location: arch/x86/lib/msr-smp.c:98
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff814c8530-ffffffff814c85c4: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f9330)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff814f9330-ffffffff814f93c4: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150dbd0)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff8150dbd0-ffffffff8150dc64: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c260)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff8153c260-ffffffff8153c2ef: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d070)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff8155d070-ffffffff8155d0ff: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6d11)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160be61)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815ef141)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165c251)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774f50)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5aa0)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
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
In arch/x86/lib/msr-smp.c (ffffffff818e88c0)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
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
In arch/x86/lib/msr-smp.c (ffffffff8192fd60)
Location: arch/x86/lib/msr-smp.c:99
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
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
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555660)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff81555660-ffffffff815556ef: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545930)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff81545930-ffffffff815459bf: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815513a0)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff815513a0-ffffffff8155142f: __rwmsr_on_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rwmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs, void (*msr_func)(void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b1e0)
Location: arch/x86/lib/msr-smp.c:99
Inline: False
Direct callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
**Symbols:**

```
ffffffff8156b1e0-ffffffff8156b286: __rwmsr_on_cpus (STB_LOCAL)
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
