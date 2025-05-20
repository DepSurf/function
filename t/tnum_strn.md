# Function: <code>tnum_strn</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a96e0)
Location: kernel/bpf/tnum.c:156
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811a96e0-ffffffff811a9701: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0bf0)
Location: kernel/bpf/tnum.c:166
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811c0bf0-ffffffff811c0c0d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d20f0)
Location: kernel/bpf/tnum.c:166
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811d20f0-ffffffff811d210d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6850)
Location: kernel/bpf/tnum.c:167
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811e6850-ffffffff811e686d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f2fa0)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811f2fa0-ffffffff811f2fbd: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215210)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81215210-ffffffff8121522d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81216eb0)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81216eb0-ffffffff81216ecd: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a300)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff8121a300-ffffffff8121a31d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251060)
Location: kernel/bpf/tnum.c:175
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81251060-ffffffff8125107d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298a50)
Location: kernel/bpf/tnum.c:175
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:__check_buffer_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81298a50-ffffffff81298a7c: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4650)
Location: kernel/bpf/tnum.c:175
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:__check_buffer_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812f4650-ffffffff812f467c: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321b00)
Location: kernel/bpf/tnum.c:175
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:__check_buffer_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81321b00-ffffffff81321b2c: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff81344ab0)
Location: kernel/bpf/log.c:542
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:__check_buffer_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/log.c:print_reg_state
```
**Symbols:**

```
ffffffff81344ab0-ffffffff81344b27: tnum_strn (STB_GLOBAL)
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
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276b08)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffff800010276b08-ffff800010276b5c: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9080)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
c04a9080-c04a90c4: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f090)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
c00000000031f090-c00000000031f0d8: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aee08)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffe0001aee08-ffffffe0001aee52: tnum_strn (STB_GLOBAL)
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
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb5c0)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811eb5c0-ffffffff811eb5dd: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de350)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811de350-ffffffff811de36d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9390)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811e9390-ffffffff811e93ad: tnum_strn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tnum_strn(char *str, size_t size, struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f7760)
Location: kernel/bpf/tnum.c:172
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811f7760-ffffffff811f777d: tnum_strn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
