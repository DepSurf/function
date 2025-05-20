# Function: <code>enable_step</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dcb0)
Location: arch/x86/kernel/step.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
```
**Symbols:**

```
ffffffff8103dcb0-ffffffff8103de50: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dad0)
Location: arch/x86/kernel/step.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8103dad0-ffffffff8103dc70: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103d3b0)
Location: arch/x86/kernel/step.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8103d3b0-ffffffff8103d534: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103b400)
Location: arch/x86/kernel/step.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8103b400-ffffffff8103b589: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103de20)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8103de20-ffffffff8103dfab: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103f3c0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8103f3c0-ffffffff8103f55f: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810409c0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff810409c0-ffffffff81040b5f: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043080)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81043080-ffffffff8104323f: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810437e0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff810437e0-ffffffff8104399f: enable_step (STB_LOCAL)
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
In arch/x86/kernel/step.c (ffffffff81047235)
Location: arch/x86/kernel/step.c:198
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
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
In arch/x86/kernel/step.c (ffffffff81046a8e)
Location: arch/x86/kernel/step.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810482c0)
Location: arch/x86/kernel/step.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff810482c0-ffffffff810484b8: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8104ebd0)
Location: arch/x86/kernel/step.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff8104ebd0-ffffffff8104edf2: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81059e00)
Location: arch/x86/kernel/step.c:202
Inline: True
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81059e00-ffffffff8105a042: enable_step (STB_LOCAL)
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
In arch/x86/kernel/step.c (ffffffff81067a3d)
Location: arch/x86/kernel/step.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
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
In arch/x86/kernel/step.c (ffffffff810692ed)
Location: arch/x86/kernel/step.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
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
In arch/x86/kernel/step.c (ffffffff8107075d)
Location: arch/x86/kernel/step.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
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
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043960)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81043960-ffffffff81043b1f: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81032fa0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81032fa0-ffffffff8103314c: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810437a0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff810437a0-ffffffff8104395f: enable_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enable_step(struct task_struct *child, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81044ba0)
Location: arch/x86/kernel/step.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
```
**Symbols:**

```
ffffffff81044ba0-ffffffff81044d5f: enable_step (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
