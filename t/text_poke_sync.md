# Function: <code>text_poke_sync</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d05e)
Location: arch/x86/kernel/alternative.c:994
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8103d950-ffffffff8103d96e: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d4e8)
Location: arch/x86/kernel/alternative.c:1006
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8103de40-ffffffff8103de5e: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ed18)
Location: arch/x86/kernel/alternative.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8103f860-ffffffff8103f887: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81044a88)
Location: arch/x86/kernel/alternative.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff81045670-ffffffff81045697: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104d0bf)
Location: arch/x86/kernel/alternative.c:1300
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8104e140-ffffffff8104e176: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810594df)
Location: arch/x86/kernel/alternative.c:1770
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8105afe0-ffffffff8105b016: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105aa86)
Location: arch/x86/kernel/alternative.c:1995
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:clear_relocate_add
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff8105c520-ffffffff8105c556: text_poke_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void text_poke_sync();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81061d46)
Location: arch/x86/kernel/alternative.c:2085
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/module.c:clear_relocate_add
  - arch/x86/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffffffff810635e0-ffffffff81063616: text_poke_sync (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
