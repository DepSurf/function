# Function: <code>arch_release_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:138
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8107fdd0-ffffffff8107fddb: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:138
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810845c0-ffffffff810845cb: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081530)
Location: kernel/fork.c:150
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81081530-ffffffff8108153b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087e10)
Location: kernel/fork.c:152
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81087e10-ffffffff81087e1b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b410)
Location: kernel/fork.c:153
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8108b410-ffffffff8108b41b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093310)
Location: kernel/fork.c:154
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81093310-ffffffff8109331b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097410)
Location: kernel/fork.c:156
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81097410-ffffffff8109741b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dab0)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8109dab0-ffffffff8109dabb: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4fb0)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810a4fb0-ffffffff810a4fbb: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a06c0)
Location: kernel/fork.c:166
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810a06c0-ffffffff810a06cb: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1540)
Location: kernel/fork.c:167
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810a1540-ffffffff810a154b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2970)
Location: kernel/fork.c:167
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810b2970-ffffffff810b297b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81050de0)
Location: arch/x86/kernel/process.c:101
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81050de0-ffffffff81050e06: arch_release_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105e390)
Location: arch/x86/kernel/process.c:101
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8105e390-ffffffff8105e3b6: arch_release_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f9d0)
Location: arch/x86/kernel/process.c:105
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8105f9d0-ffffffff8105f9f6: arch_release_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81066ac0)
Location: arch/x86/kernel/process.c:106
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81066ac0-ffffffff81066ae6: arch_release_task_struct (STB_GLOBAL)
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
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff8000100891b0)
Location: arch/arm64/kernel/process.c:332
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffff8000100891b0-ffff8000100891dc: arch_release_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350f48)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c0350f48-c0350f60: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001380c0)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c0000000001380c0-c0000000001380cc: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf300)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffe0000bf300-ffffffe0000bf31a: arch_release_task_struct (STB_WEAK)
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
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810973d0)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810973d0-ffffffff810973db: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085e50)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81085e50-ffffffff81085e5b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097380)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81097380-ffffffff8109738b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_release_task_struct(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109ef80)
Location: kernel/fork.c:165
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8109ef80-ffffffff8109ef8b: arch_release_task_struct (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
