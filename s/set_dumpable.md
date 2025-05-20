# Function: <code>set_dumpable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff81212d20)
Location: fs/exec.c:1709
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff81212d20-ffffffff81212d53: set_dumpable.part.34 (STB_LOCAL)
ffffffff81214590-ffffffff812145b8: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8123b4a7)
Location: fs/exec.c:1858
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff81239b50-ffffffff81239b83: set_dumpable.part.36 (STB_LOCAL)
ffffffff8123b320-ffffffff8123b348: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8124e27c)
Location: fs/exec.c:1886
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff8124c890-ffffffff8124c8c3: set_dumpable.part.40 (STB_LOCAL)
ffffffff8124e110-ffffffff8124e138: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8125a0c0)
Location: fs/exec.c:1918
Inline: True
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff8125a0c0-ffffffff8125a0fc: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127c3b0)
Location: fs/exec.c:1922
Inline: True
Direct callers:
  - kernel/sys.c:SyS_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff8127c3b0-ffffffff8127c3ec: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a3460)
Location: fs/exec.c:1957
Inline: True
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812a3460-ffffffff812a349c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b85b0)
Location: fs/exec.c:1957
Inline: True
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812b85b0-ffffffff812b85ec: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812d530b-ffffffff812d531e: set_dumpable.cold (STB_LOCAL)
ffffffff812d5140-ffffffff812d517c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e6cd0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812e6cd0-ffffffff812e6d0c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131e470)
Location: fs/exec.c:2068
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8131e470-ffffffff8131e4ad: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81329a10)
Location: fs/exec.c:2054
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81329a10-ffffffff81329a4d: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132f840)
Location: fs/exec.c:2054
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8132f840-ffffffff8132f87c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137cff0)
Location: fs/exec.c:2056
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8137cff0-ffffffff8137d02c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fcc80)
Location: fs/exec.c:2083
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813fcc80-ffffffff813fcce4: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81486800)
Location: fs/exec.c:2093
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81486800-ffffffff8148684e: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814bb4b0)
Location: fs/exec.c:2100
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814bb4b0-ffffffff814bb502: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814eda20)
Location: fs/exec.c:2121
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814eda20-ffffffff814eda72: set_dumpable (STB_GLOBAL)
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
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038f1a0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffff80001038f1a0-ffff80001038f220: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0576208)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
c0576208-c0576280: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486d00)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
c000000000486d00-c000000000486d94: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025f23c)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffe00025f23c-ffffffe00025f29a: set_dumpable (STB_GLOBAL)
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
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812df2b0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812df2b0-ffffffff812df2ec: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cfef0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812cfef0-ffffffff812cff2c: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd0c0)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812dd0c0-ffffffff812dd0fc: set_dumpable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct *mm, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ee050)
Location: fs/exec.c:1960
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/cred.c:commit_creds
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
```
**Symbols:**

```
ffffffff812ee050-ffffffff812ee08c: set_dumpable (STB_GLOBAL)
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
