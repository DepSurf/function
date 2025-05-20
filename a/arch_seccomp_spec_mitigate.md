# Function: <code>arch_seccomp_spec_mitigate</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043940)
Location: arch/x86/kernel/cpu/bugs.c:599
Inline: False
```
**Symbols:**

```
ffffffff81043940-ffffffff8104395f: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810451b0)
Location: arch/x86/kernel/cpu/bugs.c:870
Inline: False
```
**Symbols:**

```
ffffffff810451b0-ffffffff810451f0: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c80)
Location: arch/x86/kernel/cpu/bugs.c:1078
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81047c80-ffffffff81047cc8: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810484d0)
Location: arch/x86/kernel/cpu/bugs.c:1208
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff810484d0-ffffffff81048518: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c0c0)
Location: arch/x86/kernel/cpu/bugs.c:1322
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff8104c0c0-ffffffff8104c141: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b600)
Location: arch/x86/kernel/cpu/bugs.c:1333
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff8104b600-ffffffff8104b664: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d2b0)
Location: arch/x86/kernel/cpu/bugs.c:1333
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff8104d2b0-ffffffff8104d314: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810549e0)
Location: arch/x86/kernel/cpu/bugs.c:1475
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff810549e0-ffffffff81054a44: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060730)
Location: arch/x86/kernel/cpu/bugs.c:1977
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81060730-ffffffff8106078e: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ef90)
Location: arch/x86/kernel/cpu/bugs.c:2028
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff8106ef90-ffffffff8106efee: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070860)
Location: arch/x86/kernel/cpu/bugs.c:2139
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81070860-ffffffff810708be: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078140)
Location: arch/x86/kernel/cpu/bugs.c:2280
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81078140-ffffffff8107819e: arch_seccomp_spec_mitigate (STB_GLOBAL)
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
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209760)
Location: kernel/seccomp.c:295
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffff800010209760-ffff800010209778: arch_seccomp_spec_mitigate (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0448544)
Location: kernel/seccomp.c:295
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
c0448544-c044855c: arch_seccomp_spec_mitigate (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000286910)
Location: kernel/seccomp.c:295
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
c000000000286910-c00000000028691c: arch_seccomp_spec_mitigate (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b7b0)
Location: kernel/seccomp.c:295
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffe00016b7b0-ffffffe00016b7ca: arch_seccomp_spec_mitigate (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048640)
Location: arch/x86/kernel/cpu/bugs.c:1208
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81048640-ffffffff81048688: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810379a0)
Location: arch/x86/kernel/cpu/bugs.c:1208
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff810379a0-ffffffff810379e8: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048480)
Location: arch/x86/kernel/cpu/bugs.c:1208
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81048480-ffffffff810484c8: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049890)
Location: arch/x86/kernel/cpu/bugs.c:1208
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81049890-ffffffff810498d8: arch_seccomp_spec_mitigate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
