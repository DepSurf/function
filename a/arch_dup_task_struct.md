# Function: <code>arch_dup_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039120)
Location: arch/x86/kernel/process.c:84
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81039120-ffffffff8103914f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038150)
Location: arch/x86/kernel/process.c:88
Inline: False
```
**Symbols:**

```
ffffffff81038150-ffffffff8103817f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81037c20)
Location: arch/x86/kernel/process.c:71
Inline: False
```
**Symbols:**

```
ffffffff81037c20-ffffffff81037c4f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81035d10)
Location: arch/x86/kernel/process.c:80
Inline: False
```
**Symbols:**

```
ffffffff81035d10-ffffffff81035d3f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038030)
Location: arch/x86/kernel/process.c:94
Inline: False
```
**Symbols:**

```
ffffffff81038030-ffffffff8103805f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810391a0)
Location: arch/x86/kernel/process.c:94
Inline: False
```
**Symbols:**

```
ffffffff810391a0-ffffffff810391cf: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103a400)
Location: arch/x86/kernel/process.c:97
Inline: False
```
**Symbols:**

```
ffffffff8103a400-ffffffff8103a42f: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103c9c0)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8103c9c0-ffffffff8103c9e9: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d180)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8103d180-ffffffff8103d1a9: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040020)
Location: arch/x86/kernel/process.c:89
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff81040020-ffffffff8104004b: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103ff60)
Location: arch/x86/kernel/process.c:89
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff8103ff60-ffffffff8103ff8b: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810418f0)
Location: arch/x86/kernel/process.c:84
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff810418f0-ffffffff8104191b: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81047b90)
Location: arch/x86/kernel/process.c:84
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff81047b90-ffffffff81047baf: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81050db0)
Location: arch/x86/kernel/process.c:88
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff81050db0-ffffffff81050dde: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105e350)
Location: arch/x86/kernel/process.c:88
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff8105e350-ffffffff8105e37e: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f990)
Location: arch/x86/kernel/process.c:92
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff8105f990-ffffffff8105f9be: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81066a80)
Location: arch/x86/kernel/process.c:93
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff81066a80-ffffffff81066aae: arch_dup_task_struct (STB_GLOBAL)
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
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff8000100891e0)
Location: arch/arm64/kernel/process.c:337
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffff8000100891e0-ffff800010089258: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03517b8)
Location: kernel/fork.c:846
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c03517b8-c03517dc: arch_dup_task_struct (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000021ee0)
Location: arch/powerpc/kernel/process.c:1541
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c000000000021ee0-c0000000000220ac: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/process.c (ffffffe0000b5a22)
Location: arch/riscv/kernel/process.c:95
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0000b5a22-ffffffe0000b5aac: arch_dup_task_struct (STB_GLOBAL)
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
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d300)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8103d300-ffffffff8103d329: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102c9b0)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8102c9b0-ffffffff8102c9d9: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d140)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8103d140-ffffffff8103d169: arch_dup_task_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_dup_task_struct(struct task_struct *dst, struct task_struct *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e1e0)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8103e1e0-ffffffff8103e209: arch_dup_task_struct (STB_GLOBAL)
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
