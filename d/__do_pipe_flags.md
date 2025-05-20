# Function: <code>__do_pipe_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81215d50)
Location: fs/pipe.c:766
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe_flags
  - fs/pipe.c:SyS_pipe
```
**Symbols:**

```
ffffffff81215d50-ffffffff81215e2b: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123cbb0)
Location: fs/pipe.c:783
Inline: True
Direct callers:
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8123cbb0-ffffffff8123cc7e: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124f910)
Location: fs/pipe.c:789
Inline: True
Direct callers:
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8124f910-ffffffff8124f9de: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125b860)
Location: fs/pipe.c:788
Inline: True
Direct callers:
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8125b860-ffffffff8125b939: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127dc30)
Location: fs/pipe.c:794
Inline: True
Direct callers:
  - fs/pipe.c:SyS_pipe
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8127dc30-ffffffff8127dd09: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a4bd0)
Location: fs/pipe.c:794
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812a4bd0-ffffffff812a4ca7: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b9ca0)
Location: fs/pipe.c:787
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812b9ca0-ffffffff812b9d77: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d6920)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812d6920-ffffffff812d69f7: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e8490)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812e8490-ffffffff812e8567: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff81320452)
Location: fs/pipe.c:937
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8131eb50-ffffffff8131ebec: __do_pipe_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff8132b9c2)
Location: fs/pipe.c:936
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8132a0a0-ffffffff8132a13c: __do_pipe_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff813319f2)
Location: fs/pipe.c:950
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff81330050-ffffffff813300ec: __do_pipe_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff8137f172)
Location: fs/pipe.c:953
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff8137d810-ffffffff8137d8ac: __do_pipe_flags.part.0 (STB_LOCAL)
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
In fs/pipe.c (ffffffff813ff1c9)
Location: fs/pipe.c:954
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff813fd830-ffffffff813fd8e4: __do_pipe_flags.part.0 (STB_LOCAL)
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
In fs/pipe.c (ffffffff81488f19)
Location: fs/pipe.c:954
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff81487430-ffffffff814874e4: __do_pipe_flags.part.0 (STB_LOCAL)
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
In fs/pipe.c (ffffffff814bde49)
Location: fs/pipe.c:956
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff814bc230-ffffffff814bc2f3: __do_pipe_flags.part.0 (STB_LOCAL)
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
In fs/pipe.c (ffffffff814f02c9)
Location: fs/pipe.c:972
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff814ee760-ffffffff814ee823: __do_pipe_flags.part.0 (STB_LOCAL)
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
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010391338)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffff800010391338-ffff800010391438: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0577d7c)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
c0577d7c-c0577e5c: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000489410)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
c000000000489410-c000000000489578: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe0002609ec)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffe0002609ec-ffffffe000260aae: __do_pipe_flags (STB_LOCAL)
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
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e0a70)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812e0a70-ffffffff812e0b47: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d16b0)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812d16b0-ffffffff812d1787: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812de880)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812de880-ffffffff812de957: __do_pipe_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __do_pipe_flags(int *fd, struct file **files, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ef7f0)
Location: fs/pipe.c:799
Inline: True
Direct callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe_flags
```
**Symbols:**

```
ffffffff812ef7f0-ffffffff812ef8c7: __do_pipe_flags (STB_LOCAL)
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
