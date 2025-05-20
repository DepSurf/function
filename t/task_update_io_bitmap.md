# Function: <code>task_update_io_bitmap</code>

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
void task_update_io_bitmap(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81036f70)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81036f70-ffffffff81036fa1: task_update_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void task_update_io_bitmap(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81038030)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81038030-ffffffff81038061: task_update_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void task_update_io_bitmap(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81039b70)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81039b70-ffffffff81039ba1: task_update_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void task_update_io_bitmap(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103f520)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff8103f520-ffffffff8103f551: task_update_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046d02)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81046bb0-ffffffff81046c11: task_update_io_bitmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81050e32)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81050cc0-ffffffff81050d21: task_update_io_bitmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81051b62)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff810519f0-ffffffff81051a51: task_update_io_bitmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81058d82)
Location: arch/x86/kernel/ioport.c:36
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
**Symbols:**

```
ffffffff81058c10-ffffffff81058c71: task_update_io_bitmap.part.0 (STB_LOCAL)
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
</ul>
