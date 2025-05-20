# Function: <code>arch_futex_atomic_op_inuser</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111d4d7)
Location: arch/x86/include/asm/futex.h:45
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112b32a)
Location: arch/x86/include/asm/futex.h:45
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
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
In kernel/futex.c (ffffffff81134f79)
Location: arch/x86/include/asm/futex.h:45
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e0a0)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8113e0a0-ffffffff8113e16c: arch_futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149c30)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81149c30-ffffffff81149cfc: arch_futex_atomic_op_inuser (STB_LOCAL)
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
In kernel/futex.c (ffffffff8115a986)
Location: arch/x86/include/asm/futex.h:56
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff811569b6)
Location: arch/x86/include/asm/futex.h:56
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff81157dd6)
Location: arch/x86/include/asm/futex.h:56
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex.c (ffffffff8117cc56)
Location: arch/x86/include/asm/futex.h:56
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff811b6744)
Location: arch/x86/include/asm/futex.h:48
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff811f7894)
Location: arch/x86/include/asm/futex.h:48
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff8120c2e4)
Location: arch/x86/include/asm/futex.h:48
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
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
In kernel/futex/waitwake.c (ffffffff812235e4)
Location: arch/x86/include/asm/futex.h:48
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bb59c)
Location: arch/arm64/include/asm/futex.h:46
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400488)
Location: arch/arm/include/asm/futex.h:133
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021ca54)
Location: arch/powerpc/include/asm/futex.h:33
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013e70c)
Location: arch/riscv/include/asm/futex.h:39
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
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
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142250)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81142250-ffffffff8114231c: arch_futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811355b0)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff811355b0-ffffffff8113567c: arch_futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140100)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81140100-ffffffff811401cc: arch_futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int *oval, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114cc30)
Location: arch/x86/include/asm/futex.h:45
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8114cc30-ffffffff8114ccfc: arch_futex_atomic_op_inuser (STB_LOCAL)
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
