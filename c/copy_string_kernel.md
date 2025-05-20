# Function: <code>copy_string_kernel</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:603
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8131e796-ffffffff8131e7a2: copy_string_kernel.cold (STB_LOCAL)
ffffffff8131c360-ffffffff8131c57d: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:616
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:do_execveat_common
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81bea64e-ffffffff81bea65a: copy_string_kernel.cold (STB_LOCAL)
ffffffff81327840-ffffffff81327a5a: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:608
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81bdc68a-ffffffff81bdc696: copy_string_kernel.cold (STB_LOCAL)
ffffffff8132d640-ffffffff8132d842: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:608
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81cc3a0e-ffffffff81cc3a1a: copy_string_kernel.cold (STB_LOCAL)
ffffffff8137ae70-ffffffff8137b06f: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:613
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81e76185-ffffffff81e76191: copy_string_kernel.cold (STB_LOCAL)
ffffffff813fb340-ffffffff813fb5c1: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81485400)
Location: fs/exec.c:613
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff81485400-ffffffff81485657: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ba460)
Location: fs/exec.c:618
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff814ba460-ffffffff814ba6b7: copy_string_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_string_kernel(const char *arg, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ec9e0)
Location: fs/exec.c:619
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:copy_strings_kernel
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff814ec9e0-ffffffff814ecc34: copy_string_kernel (STB_GLOBAL)
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
