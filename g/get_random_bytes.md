# Function: <code>get_random_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815139d0)
Location: drivers/char/random.c:1253
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:print_oops_end_marker
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_inherit_context
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_seed_full_state
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:random_int_secret_init
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/neighbour.c:neigh_hash_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/route.c:find_exception
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:__ipv6_regen_rndid
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff815139d0-ffffffff81513a52: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567980)
Location: drivers/char/random.c:1502
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:print_oops_end_marker
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_process_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ext4/super.c:ext4_fill_super
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/random.c:random_int_secret_init
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:crng_initialize
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/neighbour.c:neigh_hash_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:__ipv6_regen_rndid
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff81567980-ffffffff81567b2d: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815940b0)
Location: drivers/char/random.c:1502
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:print_oops_end_marker
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ext4/super.c:ext4_fill_super
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/char/random.c:random_int_secret_init
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:crng_initialize
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/neighbour.c:neigh_hash_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff815940b0-ffffffff8159425d: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a820f)
Location: drivers/char/random.c:1530
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:print_oops_end_marker
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ext4/super.c:ext4_fill_super
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff815a8160-ffffffff815a8199: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160eb0f)
Location: drivers/char/random.c:1529
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:print_oops_end_marker
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/ip_fragment.c:ipqhashfn
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
**Symbols:**

```
ffffffff8160ea60-ffffffff8160ea99: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816486f8)
Location: drivers/char/random.c:1634
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81648650-ffffffff81648689: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666b10)
Location: drivers/char/random.c:1643
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81666b10-ffffffff81666b49: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c800)
Location: drivers/char/random.c:1725
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff8169c800-ffffffff8169c83b: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf570)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816bf570-ffffffff816bf5ab: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1571
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - lib/vsprintf.c:enable_ptr_key_workfn
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:subflow_rebuild_header
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff81773c1e-ffffffff81773c3f: get_random_bytes.cold (STB_LOCAL)
ffffffff81773630-ffffffff817736a5: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1570
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - lib/vsprintf.c:enable_ptr_key_workfn
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
```
**Symbols:**

```
ffffffff81c085b3-ffffffff81c085d4: get_random_bytes.cold (STB_LOCAL)
ffffffff8178e5f0-ffffffff8178e665: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1546
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - lib/vsprintf.c:enable_ptr_key_workfn
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff81bfa154-ffffffff81bfa175: get_random_bytes.cold (STB_LOCAL)
ffffffff81770e50-ffffffff81770ec5: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1566
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - lib/vsprintf.c:enable_ptr_key_workfn
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff81cfaa4a-ffffffff81cfaa7f: get_random_bytes.cold (STB_LOCAL)
ffffffff817f6980-ffffffff817f6a03: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff819351b0)
Location: drivers/char/random.c:393
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:uuid_gen
  - lib/uuid.c:guid_gen
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - lib/vsprintf.c:__ptr_to_hashval
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
**Symbols:**

```
ffffffff819351b0-ffffffff819351c8: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93740)
Location: drivers/char/random.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:uuid_gen
  - lib/uuid.c:guid_gen
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
  - lib/vsprintf.c:fill_ptr_key
```
**Symbols:**

```
ffffffff81a93740-ffffffff81a93758: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf230)
Location: drivers/char/random.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:uuid_gen
  - lib/uuid.c:guid_gen
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
  - lib/vsprintf.c:fill_ptr_key
```
**Symbols:**

```
ffffffff81adf230-ffffffff81adf248: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32650)
Location: drivers/char/random.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_secret
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/policy.c:set_encryption_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/random32.c:prandom_seed_full_state
  - lib/uuid.c:uuid_gen
  - lib/uuid.c:guid_gen
  - lib/uuid.c:generate_random_guid
  - lib/uuid.c:generate_random_uuid
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/md.c:md_set_array_info
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/ethtool/ioctl.c:netdev_rss_key_fill
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
  - lib/vsprintf.c:fill_ptr_key
```
**Symbols:**

```
ffffffff81b32650-ffffffff81b32668: get_random_bytes (STB_GLOBAL)
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
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0108)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffff8000108b0108-ffff8000108b0168: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa858)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c09aa858-c09aa9d4: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c0000000009480f0)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c0000000009480f0-c000000000948154: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000562540)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffe000562540-ffffffe000562676: get_random_bytes (STB_GLOBAL)
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
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81684fc0)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81684fc0-ffffffff81684ffb: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662c60)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/net/vxlan.c:vxlan_init_module
  - drivers/net/vxlan.c:vxlan_setup
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81662c60-ffffffff81662c9b: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b33b0)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_id
  - net/netfilter/nf_conntrack_core.c:hash_conntrack_raw
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash
  - net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816b33b0-ffffffff816b33eb: get_random_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd930)
Location: drivers/char/random.c:1726
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/kcmp.c:kcmp_cookies_init
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/crypto/policy.c:fscrypt_new_context_from_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_new_file_context
  - fs/fuse/inode.c:fuse_conn_init
  - security/keys/key.c:key_alloc
  - security/keys/big_key.c:big_key_preparse
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:__prandom_timer
  - lib/uuid.c:generate_random_uuid
  - drivers/md/md.c:md_ioctl
  - net/core/net_namespace.c:setup_net
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/ethtool.c:netdev_rss_key_fill
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
  - net/ipv4/inet_hashtables.c:inet_ehashfn
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/syncookies.c:cookie_hash
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/syncookies.c:cookie_hash
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816cd930-ffffffff816cd96b: get_random_bytes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>int nbytes</code>
</li>
</ul>
</details>
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
