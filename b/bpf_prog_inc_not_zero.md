# Function: <code>bpf_prog_inc_not_zero</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81192745)
Location: kernel/bpf/syscall.c:873
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119eb30)
Location: kernel/bpf/syscall.c:1042
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119eb30-ffffffff8119eb93: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3bb0)
Location: kernel/bpf/syscall.c:1143
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
```
**Symbols:**

```
ffffffff811b3bb0-ffffffff811b3c15: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c20b0)
Location: kernel/bpf/syscall.c:1329
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c20b0-ffffffff811c2115: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2830)
Location: kernel/bpf/syscall.c:1466
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d2830-ffffffff811d287c: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e06a0)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e06a0-ffffffff811e06ec: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb4c0)
Location: kernel/bpf/syscall.c:1870
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff811fb4c0-ffffffff811fb500: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa620)
Location: kernel/bpf/syscall.c:1844
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff811fa620-ffffffff811fa660: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb580)
Location: kernel/bpf/syscall.c:1852
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff811fb580-ffffffff811fb5c0: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122ccf0)
Location: kernel/bpf/syscall.c:1946
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff8122ccf0-ffffffff8122cd30: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f050)
Location: kernel/bpf/syscall.c:2192
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff8126f050-ffffffff8126f0a5: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c48b0)
Location: kernel/bpf/syscall.c:2226
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff812c48b0-ffffffff812c4905: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb990)
Location: kernel/bpf/syscall.c:2305
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff812eb990-ffffffff812eb9e5: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309ee0)
Location: kernel/bpf/syscall.c:2345
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81309ee0-ffffffff81309f35: bpf_prog_inc_not_zero (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010264438)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff800010264438-ffff8000102644e8: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c049585c)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
c049585c-c04958c8: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307c20)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c000000000307c20-c000000000307cbc: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f6ea)
Location: kernel/bpf/syscall.c:1487
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe00019f6ea-ffffffe00019f76a: bpf_prog_inc_not_zero (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8cc0)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d8cc0-ffffffff811d8d0c: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cba80)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811cba80-ffffffff811cbacc: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6a90)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d6a90-ffffffff811d6adc: bpf_prog_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_inc_not_zero(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4e00)
Location: kernel/bpf/syscall.c:1487
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e4e00-ffffffff811e4e4c: bpf_prog_inc_not_zero (STB_GLOBAL)
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
