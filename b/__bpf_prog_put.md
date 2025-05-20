# Function: <code>__bpf_prog_put</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191a90)
Location: kernel/bpf/syscall.c:776
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff81191a90-ffffffff81191b65: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119ea00)
Location: kernel/bpf/syscall.c:937
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff8119ea00-ffffffff8119eae3: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3ae0)
Location: kernel/bpf/syscall.c:1036
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811b3ae0-ffffffff811b3b2c: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1fa0)
Location: kernel/bpf/syscall.c:1219
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811c1fa0-ffffffff811c2014: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2710)
Location: kernel/bpf/syscall.c:1325
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811d2710-ffffffff811d279b: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e05c0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811e05c0-ffffffff811e0610: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffd40)
Location: kernel/bpf/syscall.c:1737
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811ffd40-ffffffff811ffdf7: __bpf_prog_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff060)
Location: kernel/bpf/syscall.c:1711
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811ff060-ffffffff811ff0f0: __bpf_prog_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffaf0)
Location: kernel/bpf/syscall.c:1714
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811ffaf0-ffffffff811ffb80: __bpf_prog_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81231790)
Location: kernel/bpf/syscall.c:1796
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff81231790-ffffffff81231827: __bpf_prog_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81274a10)
Location: kernel/bpf/syscall.c:2040
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff81274a10-ffffffff81274ac1: __bpf_prog_put.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6790)
Location: kernel/bpf/syscall.c:2066
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff812c6790-ffffffff812c6851: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812edaa0)
Location: kernel/bpf/syscall.c:2145
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff812edaa0-ffffffff812edb59: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c650)
Location: kernel/bpf/syscall.c:2185
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_detach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff8130c650-ffffffff8130c709: __bpf_prog_put (STB_LOCAL)
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
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102642f0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffff8000102642f0-ffff800010264378: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495748)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
c0495748-c04957c4: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307aa0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
c000000000307aa0-c000000000307b40: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0cd2)
Location: kernel/bpf/syscall.c:1351
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffe00019f5ba-ffffffe00019f60c: __bpf_prog_put.part.0 (STB_LOCAL)
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
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8be0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811d8be0-ffffffff811d8c30: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb9a0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811cb9a0-ffffffff811cb9f0: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d69b0)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811d69b0-ffffffff811d6a00: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4d20)
Location: kernel/bpf/syscall.c:1351
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_release
```
**Symbols:**

```
ffffffff811e4d20-ffffffff811e4d70: __bpf_prog_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
