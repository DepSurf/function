# Function: <code>would_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212750)
Location: fs/exec.c:1136
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81212750-ffffffff81212779: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123b4c5)
Location: fs/exec.c:1283
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81239230-ffffffff81239259: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124bee0)
Location: fs/exec.c:1297
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8124bee0-ffffffff8124bf93: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81258000)
Location: fs/exec.c:1323
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81258000-ffffffff812580af: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a260)
Location: fs/exec.c:1315
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8127a260-ffffffff8127a30f: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a0de0)
Location: fs/exec.c:1319
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812a0de0-ffffffff812a0e8f: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b5de0)
Location: fs/exec.c:1323
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812b5de0-ffffffff812b5e8f: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d2b80)
Location: fs/exec.c:1324
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812d2b80-ffffffff812d2c23: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4690)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812e4690-ffffffff812e4733: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131b880)
Location: fs/exec.c:1483
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8131b880-ffffffff8131b923: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81326e90)
Location: fs/exec.c:1412
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81326e90-ffffffff81326f8e: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132cf30)
Location: fs/exec.c:1408
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8132cf30-ffffffff8132d044: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137a630)
Location: fs/exec.c:1410
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8137a630-ffffffff8137a744: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fa3a0)
Location: fs/exec.c:1415
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813fa3a0-ffffffff813fa4c0: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81483ea0)
Location: fs/exec.c:1414
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81483ea0-ffffffff81483fc4: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b86e0)
Location: fs/exec.c:1417
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff814b86e0-ffffffff814b8806: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814eabf0)
Location: fs/exec.c:1435
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff814eabf0-ffffffff814ead16: would_dump (STB_GLOBAL)
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
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038cd80)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffff80001038cd80-ffff80001038ce9c: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0573e8c)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
```
**Symbols:**

```
c0573e8c-c0573f7c: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000483a20)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c000000000483a20-c000000000483b80: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025d4f8)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffe00025d4f8-ffffffe00025d5b0: would_dump (STB_GLOBAL)
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
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dcc70)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812dcc70-ffffffff812dcd13: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cd8f0)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812cd8f0-ffffffff812cd993: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812daa80)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812daa80-ffffffff812dab23: would_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void would_dump(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812eb980)
Location: fs/exec.c:1325
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812eb980-ffffffff812eba23: would_dump (STB_GLOBAL)
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
