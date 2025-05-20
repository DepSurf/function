# Function: <code>acct_arg_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212faf)
Location: fs/exec.c:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123a211)
Location: fs/exec.c:187
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124cf68)
Location: fs/exec.c:187
Inline: True
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
In fs/exec.c (ffffffff81258f0a)
Location: fs/exec.c:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127b09e)
Location: fs/exec.c:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a1e99)
Location: fs/exec.c:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6c48)
Location: fs/exec.c:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d3921)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e54b1)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131bbb0)
Location: fs/exec.c:192
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8131bbb0-ffffffff8131bbfd: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81326cf0)
Location: fs/exec.c:197
Inline: False
Direct callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81326cf0-ffffffff81326d3d: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132cd90)
Location: fs/exec.c:189
Inline: False
Direct callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8132cd90-ffffffff8132cddd: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137a530)
Location: fs/exec.c:187
Inline: False
Direct callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
**Symbols:**

```
ffffffff8137a530-ffffffff8137a57d: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fa280)
Location: fs/exec.c:186
Inline: False
Direct callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
**Symbols:**

```
ffffffff813fa280-ffffffff813fa2e9: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814846e8)
Location: fs/exec.c:186
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b92c8)
Location: fs/exec.c:185
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ebab8)
Location: fs/exec.c:186
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffff80001038c600)
Location: fs/exec.c:193
Inline: True
```
**Symbols:**

```
ffff80001038c600-ffff80001038c678: acct_arg_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void acct_arg_size(struct linux_binprm *bprm, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c05735d4)
Location: fs/exec.c:193
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:copy_strings
```
**Symbols:**

```
c05735d4-c0573640: acct_arg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000484fb8)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025ecd6)
Location: fs/exec.c:193
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:copy_strings
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dda91)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ce711)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812db8a1)
Location: fs/exec.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ec854)
Location: fs/exec.c:193
Inline: True
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
