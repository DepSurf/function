# Function: <code>copy_strings_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81213130)
Location: fs/exec.c:561
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81213130-ffffffff81213170: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123a8b0)
Location: fs/exec.c:566
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8123a8b0-ffffffff8123a8f0: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124d650)
Location: fs/exec.c:571
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8124d650-ffffffff8124d690: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81259610)
Location: fs/exec.c:597
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81259610-ffffffff81259650: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127b860)
Location: fs/exec.c:597
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8127b860-ffffffff8127b8aa: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a20c0)
Location: fs/exec.c:601
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812a20c0-ffffffff812a210a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6de0)
Location: fs/exec.c:604
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812b6de0-ffffffff812b6e2a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d3b40)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812d3b40-ffffffff812d3b8a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e56d0)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812e56d0-ffffffff812e571a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81327a60)
Location: fs/exec.c:657
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff81327a60-ffffffff81327ae8: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132d850)
Location: fs/exec.c:649
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8132d850-ffffffff8132d8d8: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137b070)
Location: fs/exec.c:649
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8137b070-ffffffff8137b0f8: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fb5d0)
Location: fs/exec.c:654
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff813fb5d0-ffffffff813fb67b: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81485670)
Location: fs/exec.c:650
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff81485670-ffffffff8148571b: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ba6d0)
Location: fs/exec.c:655
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814ba6d0-ffffffff814ba77b: copy_strings_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *argv, struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ecc50)
Location: fs/exec.c:656
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814ecc50-ffffffff814eccfb: copy_strings_kernel (STB_LOCAL)
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
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038db48)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffff80001038db48-ffff80001038dc10: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574c50)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
c0574c50-c0574ca4: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0000000004852e0)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
c0000000004852e0-c00000000048537c: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025ec38)
Location: fs/exec.c:605
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffe00025ddf6-ffffffe00025de42: copy_strings_kernel (STB_GLOBAL)
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
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ddcb0)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812ddcb0-ffffffff812ddcfa: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ce930)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812ce930-ffffffff812ce97a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dbac0)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812dbac0-ffffffff812dbb0a: copy_strings_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * *__argv, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812eca90)
Location: fs/exec.c:605
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812eca90-ffffffff812ecada: copy_strings_kernel (STB_GLOBAL)
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
