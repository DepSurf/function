# Function: <code>btf_get_by_fd</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c94c0)
Location: kernel/bpf/btf.c:2283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff811c94c0-ffffffff811c951f: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dcdc0)
Location: kernel/bpf/btf.c:2935
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811dcdc0-ffffffff811dce1f: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2400)
Location: kernel/bpf/btf.c:3425
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f2400-ffffffff811f2469: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811feb10)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811feb10-ffffffff811feb79: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225eb0)
Location: kernel/bpf/btf.c:4628
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81225eb0-ffffffff81225f68: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c910)
Location: kernel/bpf/btf.c:5633
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8122c910-ffffffff8122c9c8: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812316d0)
Location: kernel/bpf/btf.c:5826
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff812316d0-ffffffff81231788: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a680)
Location: kernel/bpf/btf.c:5879
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff8126a680-ffffffff8126a738: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b74b0)
Location: kernel/bpf/btf.c:6612
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff812b74b0-ffffffff812b7567: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81318ae0)
Location: kernel/bpf/btf.c:7103
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff81318ae0-ffffffff81318b97: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348900)
Location: kernel/bpf/btf.c:7202
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff81348900-ffffffff813489ba: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136f030)
Location: kernel/bpf/btf.c:7266
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff8136f030-ffffffff8136f0ea: btf_get_by_fd (STB_GLOBAL)
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
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010285b88)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffff800010285b88-ffff800010285c30: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b6158)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
c04b6158-c04b61dc: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c000000000330a40)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
c000000000330a40-c000000000330b2c: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001bae5c)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffe0001bae5c-ffffffe0001baed4: btf_get_by_fd (STB_GLOBAL)
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
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f7130)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f7130-ffffffff811f7199: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e9e80)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811e9e80-ffffffff811e9ee9: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4f00)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f4f00-ffffffff811f4f69: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct btf *btf_get_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81203420)
Location: kernel/bpf/btf.c:3436
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff81203420-ffffffff81203489: btf_get_by_fd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
