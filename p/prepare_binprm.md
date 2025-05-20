# Function: <code>prepare_binprm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812129c0)
Location: fs/exec.c:1352
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812129c0-ffffffff81212b47: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812397a0)
Location: fs/exec.c:1504
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812397a0-ffffffff81239989: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c4e0)
Location: fs/exec.c:1530
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8124c4e0-ffffffff8124c6c9: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812585f0)
Location: fs/exec.c:1562
Inline: True
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812585f0-ffffffff812587dd: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a3e0)
Location: fs/exec.c:1564
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff8127a3e0-ffffffff8127a5a4: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a0f60)
Location: fs/exec.c:1578
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812a0f60-ffffffff812a1120: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b5f60)
Location: fs/exec.c:1582
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812b5f60-ffffffff812b6120: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d2cf0)
Location: fs/exec.c:1583
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812d2cf0-ffffffff812d2e99: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4800)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812e4800-ffffffff812e49a9: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131c99c)
Location: fs/exec.c:1682
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81327b2c)
Location: fs/exec.c:1649
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132da5c)
Location: fs/exec.c:1649
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137b23c)
Location: fs/exec.c:1651
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fa00a)
Location: fs/exec.c:1656
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
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
In fs/exec.c (ffffffff81483b4a)
Location: fs/exec.c:1660
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
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
In fs/exec.c (ffffffff814b838a)
Location: fs/exec.c:1663
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
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
In fs/exec.c (ffffffff814ea89a)
Location: fs/exec.c:1708
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
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
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c0c8)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffff80001038c0c8-ffff80001038c25c: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574048)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
c0574048-c0574200: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000483ca0)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
c000000000483ca0-c000000000483e90: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025d66e)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffe00025d66e-ffffffe00025d7b6: prepare_binprm (STB_GLOBAL)
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
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dcde0)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812dcde0-ffffffff812dcf89: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cda60)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812cda60-ffffffff812cdc09: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dabf0)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812dabf0-ffffffff812dad99: prepare_binprm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prepare_binprm(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ebaf0)
Location: fs/exec.c:1584
Inline: False
Direct callers:
  - fs/binfmt_script.c:load_script
```
**Symbols:**

```
ffffffff812ebaf0-ffffffff812ebc99: prepare_binprm (STB_GLOBAL)
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
