# Function: <code>get_arg_page</code>

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
In fs/exec.c (ffffffff81212e73)
Location: fs/exec.c:198
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
In fs/exec.c (ffffffff81239c9a)
Location: fs/exec.c:199
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
In fs/exec.c (ffffffff8124c9d3)
Location: fs/exec.c:199
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
In fs/exec.c (ffffffff81258a91)
Location: fs/exec.c:204
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
In fs/exec.c (ffffffff8127ac1a)
Location: fs/exec.c:204
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
In fs/exec.c (ffffffff812a19fa)
Location: fs/exec.c:204
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
In fs/exec.c (ffffffff812b67ba)
Location: fs/exec.c:204
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
In fs/exec.c (ffffffff812d36a6)
Location: fs/exec.c:205
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
In fs/exec.c (ffffffff812e5236)
Location: fs/exec.c:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131bc00)
Location: fs/exec.c:204
Inline: True
Direct callers:
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff8131bc00-ffffffff8131bcb9: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81326d40)
Location: fs/exec.c:209
Inline: True
Direct callers:
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff81326d40-ffffffff81326ddc: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132cde0)
Location: fs/exec.c:201
Inline: True
Direct callers:
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff8132cde0-ffffffff8132ce7c: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137a860)
Location: fs/exec.c:199
Inline: False
Direct callers:
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff8137a860-ffffffff8137a95c: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fa9c0)
Location: fs/exec.c:198
Inline: False
Direct callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff813fa9c0-ffffffff813faadb: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81485140)
Location: fs/exec.c:198
Inline: False
Direct callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff81485140-ffffffff8148529c: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ba0c0)
Location: fs/exec.c:197
Inline: False
Direct callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff814ba0c0-ffffffff814ba307: get_arg_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *get_arg_page(struct linux_binprm *bprm, long unsigned int pos, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ec640)
Location: fs/exec.c:198
Inline: False
Direct callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
**Symbols:**

```
ffffffff814ec640-ffffffff814ec887: get_arg_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c318)
Location: fs/exec.c:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574a98)
Location: fs/exec.c:205
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
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
In fs/exec.c (c000000000484c64)
Location: fs/exec.c:205
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
In fs/exec.c (ffffffe00025dc94)
Location: fs/exec.c:205
Inline: True
Inline callers:
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
In fs/exec.c (ffffffff812dd816)
Location: fs/exec.c:205
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
In fs/exec.c (ffffffff812ce496)
Location: fs/exec.c:205
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
In fs/exec.c (ffffffff812db626)
Location: fs/exec.c:205
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
In fs/exec.c (ffffffff812ec5a6)
Location: fs/exec.c:205
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
