# Function: <code>bpf_check_uarg_tail_zero</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4350)
Location: kernel/bpf/syscall.c:71
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811b4350-ffffffff811b43c1: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c2370)
Location: kernel/bpf/syscall.c:70
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811c2370-ffffffff811c23e1: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2ef0)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff811d2ef0-ffffffff811d2f63: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811df1f0)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811df1f0-ffffffff811df263: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8120154a)
Location: kernel/bpf/syscall.c:73
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
Direct callers:
  - kernel/bpf/verifier.c:check_btf_line
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811fe660-ffffffff811fe6a5: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200e37)
Location: kernel/bpf/syscall.c:75
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
Direct callers:
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811fd940-ffffffff811fd985: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201759)
Location: kernel/bpf/syscall.c:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
Direct callers:
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811fe500-ffffffff811fe542: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122f270)
Location: kernel/bpf/syscall.c:76
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff8122f270-ffffffff8122f2c6: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81271bf0)
Location: kernel/bpf/syscall.c:80
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff81271bf0-ffffffff81271c73: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c7e40)
Location: kernel/bpf/syscall.c:80
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff812c7e40-ffffffff812c7ec3: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ef300)
Location: kernel/bpf/syscall.c:81
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff812ef300-ffffffff812ef383: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130e0e0)
Location: kernel/bpf/syscall.c:84
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff8130e0e0-ffffffff8130e163: bpf_check_uarg_tail_zero (STB_GLOBAL)
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
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010261160)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffff800010261160-ffff800010261374: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0493fc4)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c0493fc4-c0494098: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000305d80)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
c000000000305d80-c000000000305e98: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019e402)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffe00019e402-ffffffe00019e4aa: bpf_check_uarg_tail_zero (STB_GLOBAL)
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
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7810)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811d7810-ffffffff811d7883: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca5d0)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811ca5d0-ffffffff811ca643: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d55e0)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811d55e0-ffffffff811d5653: bpf_check_uarg_tail_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_check_uarg_tail_zero(void *uaddr, size_t expected_size, size_t actual_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3950)
Location: kernel/bpf/syscall.c:62
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - net/bpf/test_run.c:bpf_ctx_init
```
**Symbols:**

```
ffffffff811e3950-ffffffff811e39c3: bpf_check_uarg_tail_zero (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *uaddr</code> ➡️ <code>bpfptr_t uaddr</code>
</li>
</ul>
</details>
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
