# Function: <code>__cleanup_sighand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e5c0)
Location: kernel/fork.c:1090
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8107e5c0-ffffffff8107e5ea: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810802c0)
Location: kernel/fork.c:1146
Inline: True
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810802c0-ffffffff810802ea: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084c20)
Location: kernel/fork.c:1300
Inline: True
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81084c20-ffffffff81084c4a: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081b00)
Location: kernel/fork.c:1347
Inline: True
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81081b00-ffffffff81081b2b: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810883d0)
Location: kernel/fork.c:1359
Inline: True
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810883d0-ffffffff810883f9: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108c120)
Location: kernel/fork.c:1430
Inline: True
```
**Symbols:**

```
ffffffff8108c120-ffffffff8108c14c: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810939e0)
Location: kernel/fork.c:1487
Inline: True
```
**Symbols:**

```
ffffffff810939e0-ffffffff81093a0c: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810980f0)
Location: kernel/fork.c:1514
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810980f0-ffffffff81098123: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e6c0)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109e6c0-ffffffff8109e6f3: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5d90)
Location: kernel/fork.c:1544
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:unshare_sighand
```
**Symbols:**

```
ffffffff810a5d90-ffffffff810a5de5: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1770)
Location: kernel/fork.c:1541
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:unshare_sighand
```
**Symbols:**

```
ffffffff810a1770-ffffffff810a17c5: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a24f0)
Location: kernel/fork.c:1540
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810a24f0-ffffffff810a2545: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3bf0)
Location: kernel/fork.c:1619
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810b3bf0-ffffffff810b3c45: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9e90)
Location: kernel/fork.c:1664
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810c9e90-ffffffff810c9f02: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e74f0)
Location: kernel/fork.c:1684
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:unshare_sighand
```
**Symbols:**

```
ffffffff810e74f0-ffffffff810e7562: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f3010)
Location: kernel/fork.c:1832
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:unshare_sighand
```
**Symbols:**

```
ffffffff810f3010-ffffffff810f3082: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc3c0)
Location: kernel/fork.c:1829
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:__exit_signal
  - fs/exec.c:unshare_sighand
```
**Symbols:**

```
ffffffff810fc3c0-ffffffff810fc432: __cleanup_sighand (STB_GLOBAL)
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
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3540)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffff8000100f3540-ffff8000100f3598: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03519bc)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
c03519bc-c0351a04: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000139050)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
c000000000139050-c0000000001390cc: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0ac0)
Location: kernel/fork.c:1525
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
Direct callers:
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffe0000c11ee-ffffffe0000c1246: __cleanup_sighand (STB_GLOBAL)
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
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097fe0)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81097fe0-ffffffff81098013: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086a40)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81086a40-ffffffff81086a73: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097f90)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81097f90-ffffffff81097fc3: __cleanup_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __cleanup_sighand(struct sighand_struct *sighand);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fb90)
Location: kernel/fork.c:1525
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109fb90-ffffffff8109fbc3: __cleanup_sighand (STB_GLOBAL)
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
