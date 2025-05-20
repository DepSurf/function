# Function: <code>unshare_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080960)
Location: kernel/fork.c:2091
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81080960-ffffffff81080a04: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810827a0)
Location: kernel/fork.c:2154
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810827a0-ffffffff8108284d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087200)
Location: kernel/fork.c:2316
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81087200-ffffffff810872ad: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084080)
Location: kernel/fork.c:2446
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81084080-ffffffff8108412a: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108a970)
Location: kernel/fork.c:2455
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8108a970-ffffffff8108aa1a: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108e1d0)
Location: kernel/fork.c:2535
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8108e1d0-ffffffff8108e27d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096460)
Location: kernel/fork.c:2643
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81096460-ffffffff8109650d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a9a0)
Location: kernel/fork.c:2934
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8109a9a0-ffffffff8109aa4e: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0f60)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810a0f60-ffffffff810a100e: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7dc0)
Location: kernel/fork.c:3076
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810a7dc0-ffffffff810a7e7b: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3b40)
Location: kernel/fork.c:3056
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810a3b40-ffffffff810a3bf5: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4790)
Location: kernel/fork.c:3094
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810a4790-ffffffff810a4845: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5fb0)
Location: kernel/fork.c:3187
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810b5fb0-ffffffff810b6065: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cc4d0)
Location: kernel/fork.c:3261
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810cc4d0-ffffffff810cc58d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9bb0)
Location: kernel/fork.c:3297
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810e9bb0-ffffffff810e9c6d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f57b0)
Location: kernel/fork.c:3533
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810f57b0-ffffffff810f586d: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unshare_files();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810feb60)
Location: kernel/fork.c:3523
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810feb60-ffffffff810fec1d: unshare_files (STB_GLOBAL)
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
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f5938)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff8000100f5938-ffff8000100f5a1c: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03540a4)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c03540a4-c0354174: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013bae0)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c00000000013bae0-c00000000013bbe4: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1c72)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe0000c1c72-ffffffe0000c1d2c: unshare_files (STB_GLOBAL)
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
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a880)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8109a880-ffffffff8109a92e: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810892c0)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810892c0-ffffffff8108936e: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a830)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8109a830-ffffffff8109a8de: unshare_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unshare_files(struct files_struct **displaced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a24b0)
Location: kernel/fork.c:2951
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff810a24b0-ffffffff810a255c: unshare_files (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct files_struct **displaced</code>
</li>
</ul>
</details>
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
