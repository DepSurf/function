# Function: <code>get_random_u32</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a8520)
Location: drivers/char/random.c:2130
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slub.c:new_slab
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff815a8520-ffffffff815a85f4: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160ee30)
Location: drivers/char/random.c:2129
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slub.c:new_slab
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8160ee30-ffffffff8160ef02: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81648930)
Location: drivers/char/random.c:2237
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slub.c:new_slab
  - lib/rhashtable.c:bucket_table_alloc
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81648930-ffffffff81648a02: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666b50)
Location: drivers/char/random.c:2262
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:new_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81666b50-ffffffff81666c22: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c8f0)
Location: drivers/char/random.c:2343
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8169c8f0-ffffffff8169c990: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf660)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816bf660-ffffffff816bf700: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81772550)
Location: drivers/char/random.c:2215
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - lib/nodemask.c:node_random
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
ffffffff81772550-ffffffff817725fc: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d5c0)
Location: drivers/char/random.c:2214
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - lib/nodemask.c:node_random
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
ffffffff8178d5c0-ffffffff8178d66c: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770570)
Location: drivers/char/random.c:2190
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - lib/nodemask.c:node_random
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
ffffffff81770570-ffffffff8177061d: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f6000)
Location: drivers/char/random.c:2215
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - lib/nodemask.c:node_random
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
ffffffff817f6000-ffffffff817f60c6: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81935310)
Location: drivers/char/random.c:510
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
  - mm/slub.c:allocate_slab
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/migrate.c:next_demotion_node
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/fat/inode.c:fat_fill_inode
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - lib/nodemask.c:node_random
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81935310-ffffffff8193543f: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93a00)
Location: drivers/char/random.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - mm/shmem.c:shmem_get_inode
  - mm/kfence/core.c:kfence_init
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/fat/inode.c:fat_fill_inode
  - drivers/char/random.c:__get_random_u32_below
  - drivers/char/random.c:__get_random_u32_below
  - net/core/sock.c:sk_setsockopt
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/output_core.c:ipv6_select_ident
```
**Symbols:**

```
ffffffff81a93a00-ffffffff81a93b31: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf4f0)
Location: drivers/char/random.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - mm/shmem.c:shmem_get_inode
  - mm/kfence/core.c:kfence_init
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/fat/inode.c:fat_fill_inode
  - drivers/char/random.c:__get_random_u32_below
  - drivers/char/random.c:__get_random_u32_below
  - net/core/sock.c:sk_setsockopt
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/output_core.c:ipv6_select_ident
```
**Symbols:**

```
ffffffff81adf4f0-ffffffff81adf621: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32910)
Location: drivers/char/random.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
  - mm/shmem.c:__shmem_get_inode
  - mm/kfence/core.c:kfence_init
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/fat/inode.c:fat_fill_inode
  - drivers/char/random.c:__get_random_u32_below
  - drivers/char/random.c:__get_random_u32_below
  - net/core/sock.c:sk_setsockopt
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/unix/af_unix.c:unix_autobind
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/output_core.c:ipv6_select_ident
```
**Symbols:**

```
ffffffff81b32910-ffffffff81b32a41: get_random_u32 (STB_GLOBAL)
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
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0270)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:arch_align_stack
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffff8000108b0270-ffff8000108b0378: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa738)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/arm/kernel/process.c:arch_setup_additional_pages
  - arch/arm/kernel/signal.c:get_signal_page
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/util.c:arch_pick_mmap_layout
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/random.c:randomize_page
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
c09aa738-c09aa7c4: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000948260)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:arch_align_stack
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
c000000000948260-c00000000094835c: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe0005623f4)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
```
**Symbols:**

```
ffffffe0005623f4-ffffffe00056249a: get_random_u32 (STB_GLOBAL)
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
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816850b0)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816850b0-ffffffff81685150: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662d50)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81662d50-ffffffff81662df0: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b34a0)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816b34a0-ffffffff816b3540: get_random_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 get_random_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cda20)
Location: drivers/char/random.c:2404
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/slub.c:allocate_slab
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/route.c:rt_genid_init
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816cda20-ffffffff816cdac0: get_random_u32 (STB_GLOBAL)
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
