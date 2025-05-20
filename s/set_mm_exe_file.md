# Function: <code>set_mm_exe_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107de07)
Location: kernel/fork.c:734
Inline: True
```
**Symbols:**

```
ffffffff8107e3a0-ffffffff8107e3d1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fc9c)
Location: kernel/fork.c:769
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff810800a0-ffffffff810800d1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108447a)
Location: kernel/fork.c:923
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff81084a00-ffffffff81084a31: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810813ea)
Location: kernel/fork.c:970
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff810818e0-ffffffff81081912: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087cda)
Location: kernel/fork.c:982
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff810881c0-ffffffff810881f0: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b1ba)
Location: kernel/fork.c:1051
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff8108bf10-ffffffff8108bf40: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81092f54)
Location: kernel/fork.c:1107
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff810937d0-ffffffff81093800: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097094)
Location: kernel/fork.c:1124
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff81097ec0-ffffffff81097ef1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d794)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff8109e580-ffffffff8109e5b1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4954)
Location: kernel/fork.c:1153
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810a5c50-ffffffff810a5c81: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0064)
Location: kernel/fork.c:1150
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810a1630-ffffffff810a1661: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0e24)
Location: kernel/fork.c:1156
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810a23b0-ffffffff810a23e1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2304)
Location: kernel/fork.c:1175
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810b31b0-ffffffff810b321a: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8734)
Location: kernel/fork.c:1247
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810c9390-ffffffff810c9420: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e5909)
Location: kernel/fork.c:1268
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810e68a0-ffffffff810e6930: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f0f79)
Location: kernel/fork.c:1409
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810f2230-ffffffff810f22c6: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fa349)
Location: kernel/fork.c:1406
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810fbe70-ffffffff810fbf06: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1ed8)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffff8000100f33b8-ffff8000100f3418: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350e14)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
c035186c-c03518c4: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000137d24)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
c000000000138e50-c000000000138eb8: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0e4e)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
```
**Symbols:**

```
ffffffe0000c0faa-ffffffe0000c0ff2: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810970b4)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff81097ea0-ffffffff81097ed1: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085b34)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff81086900-ffffffff81086931: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097064)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff81097e50-ffffffff81097e81: set_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109ee64)
Location: kernel/fork.c:1139
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
**Symbols:**

```
ffffffff8109fa50-ffffffff8109fa81: set_mm_exe_file (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
