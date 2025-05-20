# Function: <code>bpf_prog_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811729c0)
Location: kernel/bpf/syscall.c:586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
  - net/core/filter.c:sk_attach_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811729c0-ffffffff81172a25: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181780)
Location: kernel/bpf/syscall.c:707
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81181780-ffffffff81181792: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118d870)
Location: kernel/bpf/syscall.c:804
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8118d870-ffffffff8118d882: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811929be)
Location: kernel/bpf/syscall.c:909
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff81192500-ffffffff81192512: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a0567)
Location: kernel/bpf/syscall.c:1095
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8119fd00-ffffffff8119fd14: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3e6f)
Location: kernel/bpf/syscall.c:1196
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_test_run
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811b6750-ffffffff811b6764: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c4bad)
Location: kernel/bpf/syscall.c:1382
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811c58a0-ffffffff811c58b4: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5737)
Location: kernel/bpf/syscall.c:1519
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d6740-ffffffff811d6754: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e22c7)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e2e30-ffffffff811e2e44: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201425)
Location: kernel/bpf/syscall.c:1918
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:perf_event_set_bpf_prog
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81200c20-ffffffff81200c34: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff128)
Location: kernel/bpf/syscall.c:1892
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:perf_event_set_bpf_prog
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff812000f0-ffffffff81200104: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201c53)
Location: kernel/bpf/syscall.c:1900
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:perf_event_set_bpf_prog
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81200aa0-ffffffff81200ab4: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233a6f)
Location: kernel/bpf/syscall.c:1994
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81232810-ffffffff81232824: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81276b49)
Location: kernel/bpf/syscall.c:2240
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81275c20-ffffffff81275c3e: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ccced)
Location: kernel/bpf/syscall.c:2274
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff812cbd00-ffffffff812cbd1e: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f4859)
Location: kernel/bpf/syscall.c:2353
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_get_prog_attach_type
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff812f3670-ffffffff812f368e: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81313799)
Location: kernel/bpf/syscall.c:2393
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/mprog.c:bpf_mprog_tuple_relative
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81312500-ffffffff8131251e: bpf_prog_get (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010265444)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff800010265e70-ffff800010265ea4: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c049747c)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c0497ef4-c0497f18: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c00000000030a170)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c00000000030ae10-c00000000030ae2c: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0d1c)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffe0001a1610-ffffffe0001a163e: bpf_prog_get (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da8e7)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811db450-ffffffff811db464: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd6a7)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811ce210-ffffffff811ce224: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d86b7)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d9220-ffffffff811d9234: bpf_prog_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e6a3a)
Location: kernel/bpf/syscall.c:1540
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e7630-ffffffff811e7644: bpf_prog_get (STB_GLOBAL)
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
