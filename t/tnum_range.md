# Function: <code>tnum_range</code>

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
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9730)
Location: kernel/bpf/tnum.c:20
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811a9730-ffffffff811a9771: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0c20)
Location: kernel/bpf/tnum.c:20
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811c0c20-ffffffff811c0c5d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2120)
Location: kernel/bpf/tnum.c:20
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811d2120-ffffffff811d215d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6880)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811e6880-ffffffff811e68bd: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f2fd0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811f2fd0-ffffffff811f300d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215240)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81215240-ffffffff8121527d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81216ee0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81216ee0-ffffffff81216f1d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a330)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff8121a330-ffffffff8121a36c: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81cb906c-ffffffff81cb908d: tnum_range.cold (STB_LOCAL)
ffffffff81251090-ffffffff812510e1: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81e6a331-ffffffff81e6a352: tnum_range.cold (STB_LOCAL)
ffffffff81298aa0-ffffffff81298b05: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_map_elem_callback_state
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff820613fe-ffffffff8206141f: tnum_range.cold (STB_LOCAL)
ffffffff812f46c0-ffffffff812f4725: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_map_elem_callback_state
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff820e0994-ffffffff820e09b5: tnum_range.cold (STB_LOCAL)
ffffffff81321b70-ffffffff81321bd5: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:coerce_reg_to_size_sx
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff821bd0a6-ffffffff821bd0c7: tnum_range.cold (STB_LOCAL)
ffffffff81344480-ffffffff813444e5: tnum_range (STB_GLOBAL)
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
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276b90)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffff800010276b90-ffff800010276c10: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a90f4)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
c04a90f4-c04a91b4: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f0f0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
c00000000031f0f0-c00000000031f13c: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aee76)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffe0001aee76-ffffffe0001aef4c: tnum_range (STB_GLOBAL)
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
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb5f0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811eb5f0-ffffffff811eb62d: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de380)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811de380-ffffffff811de3bd: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e93c0)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811e93c0-ffffffff811e93fd: tnum_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_range(u64 min, u64 max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f7790)
Location: kernel/bpf/tnum.c:21
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff811f7790-ffffffff811f77cd: tnum_range (STB_GLOBAL)
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
