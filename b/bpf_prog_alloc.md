# Function: <code>bpf_prog_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811711e0)
Location: kernel/bpf/core.c:73
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:sk_attach_filter
```
**Symbols:**

```
ffffffff811711e0-ffffffff81171279: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117e7f0)
Location: kernel/bpf/core.c:74
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8117e7f0-ffffffff8117e886: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a400)
Location: kernel/bpf/core.c:74
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8118a400-ffffffff8118a496: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118de20)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8118de20-ffffffff8118decf: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119c230)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8119c230-ffffffff8119c2e6: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1310)
Location: kernel/bpf/core.c:78
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/verifier.c:bpf_check
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811b1310-ffffffff811b13ee: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf990)
Location: kernel/bpf/core.c:81
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/verifier.c:bpf_check
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811bf990-ffffffff811bfa80: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d07b0)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811d07b0-ffffffff811d083b: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dcd40)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811dcd40-ffffffff811dcdcb: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9750)
Location: kernel/bpf/core.c:105
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811f9750-ffffffff811f97db: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f87d0)
Location: kernel/bpf/core.c:107
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811f87d0-ffffffff811f885b: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9610)
Location: kernel/bpf/core.c:115
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811f9610-ffffffff811f9699: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122aca0)
Location: kernel/bpf/core.c:115
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8122aca0-ffffffff8122ad47: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c610)
Location: kernel/bpf/core.c:120
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8126c610-ffffffff8126c6ca: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c16b0)
Location: kernel/bpf/core.c:128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff812c16b0-ffffffff812c1778: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e84e0)
Location: kernel/bpf/core.c:129
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff812e84e0-ffffffff812e85c8: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306850)
Location: kernel/bpf/core.c:133
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81306850-ffffffff81306938: bpf_prog_alloc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025d778)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffff80001025d778-ffff80001025d82c: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490f58)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
c0490f58-c049100c: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000302150)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
c000000000302150-c000000000302228: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019bd4a)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffe00019bd4a-ffffffe00019bdf0: bpf_prog_alloc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5360)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811d5360-ffffffff811d53eb: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8120)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811c8120-ffffffff811c81ab: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3130)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811d3130-ffffffff811d31bb: bpf_prog_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1420)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff811e1420-ffffffff811e14ab: bpf_prog_alloc (STB_GLOBAL)
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
