# Function: <code>futex_atomic_op_inuser</code>

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
In kernel/futex.c (ffffffff8110103a)
Location: arch/x86/include/asm/futex.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff81107ff6)
Location: arch/x86/include/asm/futex.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff8110f7e6)
Location: arch/x86/include/asm/futex.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81110b42)
Location: arch/x86/include/asm/futex.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111d405)
Location: kernel/futex.c:1581
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
In kernel/futex.c (ffffffff8112b2ff)
Location: kernel/futex.c:1563
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
In kernel/futex.c (ffffffff81134f53)
Location: kernel/futex.c:1631
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114034f)
Location: kernel/futex.c:1645
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114c3bf)
Location: kernel/futex.c:1720
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a930)
Location: kernel/futex.c:1649
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8115a930-ffffffff8115abe7: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156960)
Location: kernel/futex.c:1634
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81156960-ffffffff81156c2c: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157d80)
Location: kernel/futex.c:1637
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81157d80-ffffffff8115803a: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117cc00)
Location: kernel/futex.c:1696
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8117cc00-ffffffff8117ceba: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b66f0)
Location: kernel/futex/waitwake.c:188
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff811b66f0-ffffffff811b697c: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f7840)
Location: kernel/futex/waitwake.c:188
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff811f7840-ffffffff811f7acc: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120c290)
Location: kernel/futex/waitwake.c:188
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff8120c290-ffffffff8120c50e: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff81223590)
Location: kernel/futex/waitwake.c:203
Inline: False
Direct callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff81223590-ffffffff8122380e: futex_atomic_op_inuser (STB_LOCAL)
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
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bb528)
Location: kernel/futex.c:1720
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffff8000101bb528-ffff8000101bbab4: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400420)
Location: kernel/futex.c:1720
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c0400420-c040079c: futex_atomic_op_inuser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_atomic_op_inuser(unsigned int encoded_op, u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c9e0)
Location: kernel/futex.c:1720
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
c00000000021c9e0-c00000000021cdcc: futex_atomic_op_inuser (STB_LOCAL)
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
In kernel/futex.c (ffffffe00013e68c)
Location: kernel/futex.c:1720
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811449df)
Location: kernel/futex.c:1720
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
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
In kernel/futex.c (ffffffff81137cef)
Location: kernel/futex.c:1720
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114288f)
Location: kernel/futex.c:1720
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114ecd3)
Location: kernel/futex.c:1720
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
```
</details>
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
<b>Arch</b>
<ul>
</ul>
