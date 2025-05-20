# Function: <code>bpf_prog_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172f60)
Location: kernel/bpf/syscall.c:546
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_ioctl
  - net/core/filter.c:__bpf_prog_release
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81172f60-ffffffff81172f82: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180ce0)
Location: kernel/bpf/syscall.c:636
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_release
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__bpf_prog_release
```
**Symbols:**

```
ffffffff81180ce0-ffffffff81180d09: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118ca20)
Location: kernel/bpf/syscall.c:699
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_release
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__bpf_prog_release
  - net/core/lwt_bpf.c:bpf_lwt_prog_destroy
```
**Symbols:**

```
ffffffff8118ca20-ffffffff8118ca49: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81193475)
Location: kernel/bpf/syscall.c:787
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - net/core/dev.c:free_netdev
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_lwt_prog_destroy
```
**Symbols:**

```
ffffffff81191b70-ffffffff81191b85: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a03b8)
Location: kernel/bpf/syscall.c:948
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/sockmap.c:sock_map_prog
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:smap_gc_work
  - kernel/bpf/sockmap.c:smap_gc_work
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_detach_all
  - net/core/dev.c:free_netdev
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_lwt_prog_destroy
```
**Symbols:**

```
ffffffff8119eaf0-ffffffff8119eb05: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b61df)
Location: kernel/bpf/syscall.c:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/sockmap.c:sock_map_release
  - kernel/bpf/sockmap.c:sock_map_release
  - kernel/bpf/sockmap.c:sock_map_release
  - kernel/bpf/sockmap.c:sock_map_prog
  - kernel/bpf/sockmap.c:smap_gc_work
  - kernel/bpf/sockmap.c:smap_gc_work
  - kernel/bpf/sockmap.c:smap_gc_work
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
**Symbols:**

```
ffffffff811b3b30-ffffffff811b3b45: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c438e)
Location: kernel/bpf/syscall.c:1233
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811c2020-ffffffff811c2035: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d578b)
Location: kernel/bpf/syscall.c:1340
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811d27a0-ffffffff811d27b5: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2244)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811e0610-ffffffff811e0625: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201b77)
Location: kernel/bpf/syscall.c:1748
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_free_event
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
```
**Symbols:**

```
ffffffff81200ba0-ffffffff81200bb0: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201132)
Location: kernel/bpf/syscall.c:1722
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
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
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff81200060-ffffffff81200070: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201a53)
Location: kernel/bpf/syscall.c:1725
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
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
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:perf_event_set_bpf_prog
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff81200a10-ffffffff81200a20: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233aba)
Location: kernel/bpf/syscall.c:1813
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
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
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff81232780-ffffffff81232790: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812779b1)
Location: kernel/bpf/syscall.c:2057
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
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
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff81275b60-ffffffff81275b76: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cdd41)
Location: kernel/bpf/syscall.c:2080
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
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
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff812c6870-ffffffff812c6886: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f52ce)
Location: kernel/bpf/syscall.c:2159
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
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
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/tun.c:tun_xdp
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_get_prog_attach_type
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff812edb70-ffffffff812edb86: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813140c5)
Location: kernel/bpf/syscall.c:2199
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
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
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/core.c:bpf_prog_free
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:bpf_iter_link_replace
  - kernel/bpf/bpf_iter.c:iter_release
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/mprog.c:bpf_mprog_detach
  - kernel/bpf/mprog.c:bpf_mprog_attach
  - kernel/bpf/mprog.c:bpf_mprog_attach
  - kernel/bpf/mprog.c:bpf_mprog_tuple_relative
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_uninstall
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - drivers/net/netkit.c:netkit_uninit
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
  - drivers/net/netkit.c:netkit_prog_attach
  - drivers/net/tun.c:tun_xdp
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
  - net/ipv6/seg6_local.c:destroy_attr_bpf
```
**Symbols:**

```
ffffffff8130c720-ffffffff8130c736: bpf_prog_put (STB_GLOBAL)
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
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010265c80)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffff800010264378-ffff8000102643a8: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0497890)
Location: kernel/bpf/syscall.c:1361
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_lwt_prog_destroy
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
c04957c4-c04957e4: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c00000000030aba8)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
c000000000307b40-c000000000307b58: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0cd2)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffe00019f60c-ffffffe00019f652: bpf_prog_put (STB_GLOBAL)
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
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da864)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811d8c30-ffffffff811d8c45: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd624)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811cb9f0-ffffffff811cba05: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8634)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811d6a00-ffffffff811d6a15: bpf_prog_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_put(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e69b7)
Location: kernel/bpf/syscall.c:1361
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
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/bpf/arraymap.c:prog_fd_array_put_ptr
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_free_event
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/xdp.c:xdp_attachment_setup
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
```
**Symbols:**

```
ffffffff811e4d70-ffffffff811e4d85: bpf_prog_put (STB_GLOBAL)
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
