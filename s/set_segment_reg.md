# Function: <code>set_segment_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b8e0)
Location: arch/x86/kernel/ptrace.c:310
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff8103b8e0-ffffffff8103bac6: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c1b9)
Location: arch/x86/kernel/ptrace.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103b800-ffffffff8103b925: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b7b9)
Location: arch/x86/kernel/ptrace.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103b040-ffffffff8103b165: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810397f9)
Location: arch/x86/kernel/ptrace.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81039080-ffffffff810391b1: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c1fd)
Location: arch/x86/kernel/ptrace.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103ba70-ffffffff8103bba5: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d72a)
Location: arch/x86/kernel/ptrace.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103cee0-ffffffff8103d015: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ecba)
Location: arch/x86/kernel/ptrace.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103e410-ffffffff8103e545: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810419e2)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81040bc0-ffffffff81040d13: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042162)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81041350-ffffffff810414a3: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044750)
Location: arch/x86/kernel/ptrace.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81044750-ffffffff81044853: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044220)
Location: arch/x86/kernel/ptrace.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81044220-ffffffff81044323: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045e60)
Location: arch/x86/kernel/ptrace.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81045e60-ffffffff81045f63: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104d70a)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8104c4f0-ffffffff8104c5f3: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810585fa)
Location: arch/x86/kernel/ptrace.c:270
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81057560-ffffffff8105768e: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065e7a)
Location: arch/x86/kernel/ptrace.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81064d10-ffffffff81064e3e: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106776e)
Location: arch/x86/kernel/ptrace.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81066610-ffffffff8106672d: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106ebee)
Location: arch/x86/kernel/ptrace.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8106da90-ffffffff8106dbad: set_segment_reg (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810422e2)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810414d0-ffffffff81041623: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810319a2)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81030ba0-ffffffff81030ced: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042122)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81041310-ffffffff81041463: set_segment_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_segment_reg(struct task_struct *task, long unsigned int offset, u16 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043502)
Location: arch/x86/kernel/ptrace.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810426f0-ffffffff81042843: set_segment_reg (STB_LOCAL)
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
