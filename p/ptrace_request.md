# Function: <code>ptrace_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108bc20)
Location: kernel/ptrace.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff8108bc20-ffffffff8108c1f0: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108ec90)
Location: kernel/ptrace.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff8108ec90-ffffffff8108f285: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093c20)
Location: kernel/ptrace.c:870
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff81093c20-ffffffff8109420f: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090d10)
Location: kernel/ptrace.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff81090d10-ffffffff810912de: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097b80)
Location: kernel/ptrace.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff81097b80-ffffffff81098154: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109b490)
Location: kernel/ptrace.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff8109b490-ffffffff8109baac: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a36d0)
Location: kernel/ptrace.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810a36d0-ffffffff810a3cb1: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (0)
Location: kernel/ptrace.c:997
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810a8c38-ffffffff810a8c4b: ptrace_request.cold (STB_LOCAL)
ffffffff810a8390-ffffffff810a8960: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ae9b0)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810ae9b0-ffffffff810aef7a: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b6550)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810b6550-ffffffff810b6b14: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1740)
Location: kernel/ptrace.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810b1740-ffffffff810b1d08: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b2d00)
Location: kernel/ptrace.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810b2d00-ffffffff810b3332: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c4ea0)
Location: kernel/ptrace.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810c4ea0-ffffffff810c54d2: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dc2e0)
Location: kernel/ptrace.c:1030
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810dc2e0-ffffffff810dca2f: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fc450)
Location: kernel/ptrace.c:1030
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810fc450-ffffffff810fcc40: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff811084f0)
Location: kernel/ptrace.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff811084f0-ffffffff81108ca3: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81111e80)
Location: kernel/ptrace.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff81111e80-ffffffff81112633: ptrace_request (STB_GLOBAL)
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
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010108e28)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffff800010108e28-ffff800010109928: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0362a1c)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
c0362a1c-c0363300: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0000000001502b0)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
c0000000001502b0-c000000000150c14: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cc7b4)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/riscv/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffe0000cc7b4-ffffffe0000ccd26: ptrace_request (STB_GLOBAL)
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
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a8d20)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810a8d20-ffffffff810a92ea: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810976f0)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810976f0-ffffffff81097cae: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a8280)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810a8280-ffffffff810a884a: ptrace_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptrace_request(struct task_struct *child, long int request, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b03b0)
Location: kernel/ptrace.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810b03b0-ffffffff810b096f: ptrace_request (STB_GLOBAL)
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
