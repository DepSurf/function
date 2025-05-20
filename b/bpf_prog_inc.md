# Function: <code>bpf_prog_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180ca4)
Location: kernel/bpf/syscall.c:683
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81181760-ffffffff81181775: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118c9e4)
Location: kernel/bpf/syscall.c:779
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8118c950-ffffffff8118c965: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119193b)
Location: kernel/bpf/syscall.c:866
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811918a0-ffffffff811918b5: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f17e)
Location: kernel/bpf/syscall.c:1035
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff8119e870-ffffffff8119e885: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3ca1)
Location: kernel/bpf/syscall.c:1136
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811b3670-ffffffff811b3685: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c21a1)
Location: kernel/bpf/syscall.c:1322
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811c1d50-ffffffff811c1d65: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2901)
Location: kernel/bpf/syscall.c:1459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811d23a0-ffffffff811d23b5: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ded51)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811de940-ffffffff811de955: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc92f)
Location: kernel/bpf/syscall.c:1863
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811fb3f0-ffffffff811fb403: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbc82)
Location: kernel/bpf/syscall.c:1837
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
```
**Symbols:**

```
ffffffff811fa550-ffffffff811fa563: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc9a2)
Location: kernel/bpf/syscall.c:1845
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
```
**Symbols:**

```
ffffffff811fb490-ffffffff811fb4a3: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233442)
Location: kernel/bpf/syscall.c:1939
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
```
**Symbols:**

```
ffffffff8122cbd0-ffffffff8122cbe3: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812766f1)
Location: kernel/bpf/syscall.c:2185
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8126eef0-ffffffff8126ef0b: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cc871)
Location: kernel/bpf/syscall.c:2219
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812c4700-ffffffff812c471b: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f4211)
Location: kernel/bpf/syscall.c:2298
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812eb700-ffffffff812eb71b: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81313170)
Location: kernel/bpf/syscall.c:2338
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_event_alloc
  - net/core/dev.c:dev_xdp_install
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff81309c50-ffffffff81309c6b: bpf_prog_inc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010260018)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffff80001025ff40-ffff80001025ff70: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0493530)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
c0493394-c04933b4: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000305058)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
c000000000304c60-c000000000304c78: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019de08)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffe00019d7e0-ffffffe00019d81c: bpf_prog_inc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7371)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811d6f60-ffffffff811d6f75: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca131)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811c9d20-ffffffff811c9d35: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5141)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811d4d30-ffffffff811d4d45: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_inc(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3471)
Location: kernel/bpf/syscall.c:1480
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff811e3060-ffffffff811e3075: bpf_prog_inc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct bpf_prog *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
