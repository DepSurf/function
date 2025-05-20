# Function: <code>kernel_fpu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810399d0)
Location: arch/x86/kernel/fpu/core.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff810399d0-ffffffff81039a11: kernel_fpu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038c70)
Location: arch/x86/kernel/fpu/core.c:43
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038c70-ffffffff81038cb1: kernel_fpu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038650)
Location: arch/x86/kernel/fpu/core.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038650-ffffffff81038691: kernel_fpu_disable (STB_LOCAL)
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
In arch/x86/kernel/fpu/core.c (ffffffff81036b27)
Location: arch/x86/kernel/fpu/core.c:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038ba0)
Location: arch/x86/kernel/fpu/core.c:44
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038ba0-ffffffff81038bc2: kernel_fpu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039e40)
Location: arch/x86/kernel/fpu/core.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81039e40-ffffffff81039e62: kernel_fpu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernel_fpu_disable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103b360)
Location: arch/x86/kernel/fpu/core.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103b360-ffffffff8103b382: kernel_fpu_disable (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
