# Function: <code>try_to_freeze_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810cd8b0)
Location: kernel/power/process.c:27
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:freeze_kernel_threads
```
**Symbols:**

```
ffffffff810cd8b0-ffffffff810cdbd7: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d2380)
Location: kernel/power/process.c:27
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810d2380-ffffffff810d271f: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d8f30)
Location: kernel/power/process.c:27
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810d8f30-ffffffff810d92c6: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d7f30)
Location: kernel/power/process.c:30
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810d7f30-ffffffff810d82b4: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810e0020)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810e0020-ffffffff810e03a8: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810e86f0-ffffffff810e894f: try_to_freeze_tasks (STB_LOCAL)
ffffffff810e8bca-ffffffff810e8ca2: try_to_freeze_tasks.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810f3d00-ffffffff810f3f5f: try_to_freeze_tasks (STB_LOCAL)
ffffffff810f41bb-ffffffff810f429d: try_to_freeze_tasks.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810fc1e0-ffffffff810fc352: try_to_freeze_tasks (STB_LOCAL)
ffffffff810fc5f1-ffffffff810fc7db: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81108600-ffffffff81108772: try_to_freeze_tasks (STB_LOCAL)
ffffffff81108a11-ffffffff81108bfb: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81113200-ffffffff81113372: try_to_freeze_tasks (STB_LOCAL)
ffffffff81113613-ffffffff811137f5: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81110250-ffffffff811103c2: try_to_freeze_tasks (STB_LOCAL)
ffffffff81bde946-ffffffff81bdeb28: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81110c90-ffffffff81110e02: try_to_freeze_tasks (STB_LOCAL)
ffffffff81bd0abf-ffffffff81bd0ca1: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81130770-ffffffff811308e7: try_to_freeze_tasks (STB_LOCAL)
ffffffff81ca97cd-ffffffff81ca99c6: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:28
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81151f70-ffffffff81152157: try_to_freeze_tasks (STB_LOCAL)
ffffffff81e59768-ffffffff81e598e5: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:28
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81180d60-ffffffff8118119c: try_to_freeze_tasks (STB_LOCAL)
ffffffff82058379-ffffffff8205838d: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:28
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81191c50-ffffffff81192091: try_to_freeze_tasks (STB_LOCAL)
ffffffff820d6c89-ffffffff820d6c9d: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:28
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811a0640-ffffffff811a0a81: try_to_freeze_tasks (STB_LOCAL)
ffffffff821b1f1f-ffffffff821b1f33: try_to_freeze_tasks.cold (STB_LOCAL)
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
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffff80001016f9b8)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffff80001016f9b8-ffff80001016fd2c: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c03ba5cc)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c03ba5cc-c03ba9c4: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c0000000001c79a0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c0000000001c79a0-c0000000001c7e80: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffe00010da9e)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffe00010da9e-ffffffe00010dd06: try_to_freeze_tasks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81101740-ffffffff811018b2: try_to_freeze_tasks (STB_LOCAL)
ffffffff81101b51-ffffffff81101d3b: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810f1b00-ffffffff810f1c72: try_to_freeze_tasks (STB_LOCAL)
ffffffff810f1f11-ffffffff810f20fb: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810fead0-ffffffff810fec42: try_to_freeze_tasks (STB_LOCAL)
ffffffff810feee1-ffffffff810ff0cb: try_to_freeze_tasks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int try_to_freeze_tasks(bool user_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:31
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81109d90-ffffffff81109f1e: try_to_freeze_tasks (STB_LOCAL)
ffffffff8110a1e1-ffffffff8110a3d0: try_to_freeze_tasks.cold (STB_LOCAL)
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
