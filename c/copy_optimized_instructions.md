# Function: <code>copy_optimized_instructions</code>

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
In arch/x86/kernel/kprobes/opt.c (ffffffff8106046a)
Location: arch/x86/kernel/kprobes/opt.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8106020d)
Location: arch/x86/kernel/kprobes/opt.c:175
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810632ad)
Location: arch/x86/kernel/kprobes/opt.c:175
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81061e00)
Location: arch/x86/kernel/kprobes/opt.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81061e00-ffffffff81061ece: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81065e60)
Location: arch/x86/kernel/kprobes/opt.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81065e60-ffffffff81065f3c: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81068a20)
Location: arch/x86/kernel/kprobes/opt.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81068a20-ffffffff81068afc: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106e7e0)
Location: arch/x86/kernel/kprobes/opt.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8106e7e0-ffffffff8106e8be: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072840)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81072840-ffffffff81072923: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073830)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81073830-ffffffff81073913: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107a960)
Location: arch/x86/kernel/kprobes/opt.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8107a960-ffffffff8107aa43: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107a6e0)
Location: arch/x86/kernel/kprobes/opt.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8107a6e0-ffffffff8107a7d2: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b8e0)
Location: arch/x86/kernel/kprobes/opt.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8107b8e0-ffffffff8107b9d2: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81089a50)
Location: arch/x86/kernel/kprobes/opt.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81089a50-ffffffff81089b42: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a0c0)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8109a0c0-ffffffff8109a1d9: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b0a40)
Location: arch/x86/kernel/kprobes/opt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810b0a40-ffffffff810b0b59: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b37e0)
Location: arch/x86/kernel/kprobes/opt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810b37e0-ffffffff810b38f9: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bac40)
Location: arch/x86/kernel/kprobes/opt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810bac40-ffffffff810bad59: copy_optimized_instructions (STB_LOCAL)
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
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072830)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81072830-ffffffff81072913: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810628b0)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810628b0-ffffffff81062993: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810727e0)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810727e0-ffffffff810728c3: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_optimized_instructions(u8 *dest, u8 *src, u8 *real);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074830)
Location: arch/x86/kernel/kprobes/opt.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81074830-ffffffff81074913: copy_optimized_instructions (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *real</code>
</li>
</ul>
</details>
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
