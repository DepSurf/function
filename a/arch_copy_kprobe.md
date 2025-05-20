# Function: <code>arch_copy_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105fd68)
Location: arch/x86/kernel/kprobes/core.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105fb6c)
Location: arch/x86/kernel/kprobes/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062c0c)
Location: arch/x86/kernel/kprobes/core.c:406
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061a20)
Location: arch/x86/kernel/kprobes/core.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81061a20-ffffffff81061b25: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81065a80)
Location: arch/x86/kernel/kprobes/core.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81065a80-ffffffff81065bb5: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810685e0)
Location: arch/x86/kernel/kprobes/core.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810685e0-ffffffff810686fe: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106e440)
Location: arch/x86/kernel/kprobes/core.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff8106e440-ffffffff8106e55e: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072490)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81072490-ffffffff810725ae: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810734c0)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810734c0-ffffffff810735de: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a590)
Location: arch/x86/kernel/kprobes/core.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff8107a590-ffffffff8107a6e1: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a310)
Location: arch/x86/kernel/kprobes/core.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff8107a310-ffffffff8107a47c: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107b520)
Location: arch/x86/kernel/kprobes/core.c:695
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff8107b520-ffffffff8107b657: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810896a0)
Location: arch/x86/kernel/kprobes/core.c:689
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810896a0-ffffffff810897d7: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81099a60)
Location: arch/x86/kernel/kprobes/core.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81099a60-ffffffff81099b5e: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b03a0)
Location: arch/x86/kernel/kprobes/core.c:672
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810b03a0-ffffffff810b049e: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b33c0)
Location: arch/x86/kernel/kprobes/core.c:674
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810b33c0-ffffffff810b34be: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba820)
Location: arch/x86/kernel/kprobes/core.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810ba820-ffffffff810ba91e: arch_copy_kprobe (STB_LOCAL)
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
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810724c0)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810724c0-ffffffff810725de: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062540)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81062540-ffffffff8106265e: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072470)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff81072470-ffffffff8107258e: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810744c0)
Location: arch/x86/kernel/kprobes/core.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
```
**Symbols:**

```
ffffffff810744c0-ffffffff810745de: arch_copy_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
