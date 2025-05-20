# Function: <code>arch_optimize_kprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810605e0)
Location: arch/x86/kernel/kprobes/opt.c:384
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810605e0-ffffffff810606de: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810603e0)
Location: arch/x86/kernel/kprobes/opt.c:385
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810603e0-ffffffff810604e1: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81063480)
Location: arch/x86/kernel/kprobes/opt.c:385
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81063480-ffffffff81063581: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062450)
Location: arch/x86/kernel/kprobes/opt.c:400
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81062450-ffffffff81062531: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810665a0)
Location: arch/x86/kernel/kprobes/opt.c:431
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810665a0-ffffffff81066681: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81069160)
Location: arch/x86/kernel/kprobes/opt.c:431
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81069160-ffffffff8106923f: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106ef20)
Location: arch/x86/kernel/kprobes/opt.c:436
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8106ef20-ffffffff8106efef: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81073190-ffffffff810731ae: arch_optimize_kprobes.cold (STB_LOCAL)
ffffffff81072fd0-ffffffff810730a1: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073fc0)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81073fc0-ffffffff8107408a: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b0e0)
Location: arch/x86/kernel/kprobes/opt.c:447
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8107b0e0-ffffffff8107b1ab: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107aef0)
Location: arch/x86/kernel/kprobes/opt.c:481
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8107aef0-ffffffff8107afbb: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107c0c0)
Location: arch/x86/kernel/kprobes/opt.c:486
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8107c0c0-ffffffff8107c1a6: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8108a230)
Location: arch/x86/kernel/kprobes/opt.c:486
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8108a230-ffffffff8108a30b: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a730)
Location: arch/x86/kernel/kprobes/opt.c:493
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8109a730-ffffffff8109a82b: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b1140)
Location: arch/x86/kernel/kprobes/opt.c:481
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810b1140-ffffffff810b1234: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b40f0)
Location: arch/x86/kernel/kprobes/opt.c:473
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810b40f0-ffffffff810b41e4: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bb550)
Location: arch/x86/kernel/kprobes/opt.c:473
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810bb550-ffffffff810bb644: arch_optimize_kprobes (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/opt-arm.c (c0ea12b8)
Location: arch/arm/probes/kprobes/opt-arm.c:291
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
c0ea12b8-c0ea1380: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/optprobes.c (c000000000057d40)
Location: arch/powerpc/kernel/optprobes.c:306
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
c000000000057d40-c000000000057e14: arch_optimize_kprobes (STB_GLOBAL)
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
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072fc0)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81072fc0-ffffffff8107308a: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81063040)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81063040-ffffffff8106310a: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072f70)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81072f70-ffffffff8107303a: arch_optimize_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_optimize_kprobes(struct list_head *oplist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074fd0)
Location: arch/x86/kernel/kprobes/opt.c:422
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81074fd0-ffffffff8107509a: arch_optimize_kprobes (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
