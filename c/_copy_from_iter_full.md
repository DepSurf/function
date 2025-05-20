# Function: <code>_copy_from_iter_full</code>

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
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814661e0)
Location: lib/iov_iter.c:596
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff814661e0-ffffffff81466420: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814922f0)
Location: lib/iov_iter.c:596
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff814922f0-ffffffff8149253e: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6f80)
Location: lib/iov_iter.c:712
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff814c6f80-ffffffff814c71c7: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dbb20)
Location: lib/iov_iter.c:756
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff814dbb20-ffffffff814dbd7f: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8150ad88-ffffffff8150ad9d: _copy_from_iter_full.cold (STB_LOCAL)
ffffffff81507490-ffffffff815076f7: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815255a0)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff815255a0-ffffffff81525815: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158abd0)
Location: lib/iov_iter.c:778
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8158abd0-ffffffff8158aeb4: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5ff0)
Location: lib/iov_iter.c:785
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff815a5ff0-ffffffff815a6234: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b1ee0)
Location: lib/iov_iter.c:822
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff815b1ee0-ffffffff815b24b8: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062fd30)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffff80001062fd30-ffff80001062fff4: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d66d8)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
c07d66d8-c07d698c: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d6b90)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
c0000000007d6b90-c0000000007d6fc0: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045efce)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffe00045efce-ffffffe00045f206: _copy_from_iter_full (STB_GLOBAL)
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
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151db80)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8151db80-ffffffff8151ddf5: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150de70)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8150de70-ffffffff8150e0e5: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81519c10)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81519c10-ffffffff81519e85: _copy_from_iter_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool _copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81533420)
Location: lib/iov_iter.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81533420-ffffffff81533695: _copy_from_iter_full (STB_GLOBAL)
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
