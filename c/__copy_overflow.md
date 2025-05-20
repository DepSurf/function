# Function: <code>__copy_overflow</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fbd70)
Location: mm/maccess.c:220
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/sys.c:override_release
  - kernel/printk/printk.c:syslog_print_all
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/scsi/sg.c:sg_write
  - net/core/sock.c:sock_getsockopt
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff812fbd70-ffffffff812fbd98: __copy_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81365f60)
Location: mm/maccess.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/sys.c:override_release
  - kernel/printk/printk.c:syslog_print_all
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - io_uring/net.c:io_recvmsg
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/scsi/sg.c:sg_write
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81365f60-ffffffff81365f88: __copy_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398400)
Location: mm/maccess.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/sys.c:override_release
  - kernel/printk/printk.c:syslog_print_all
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - io_uring/net.c:io_recvmsg
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/scsi/sg.c:sg_write
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81398400-ffffffff81398428: __copy_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2200)
Location: mm/maccess.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/sys.c:override_release
  - kernel/printk/printk.c:syslog_print_all
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - io_uring/net.c:io_recvmsg
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/scsi/sg.c:sg_write
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff813c2200-ffffffff813c2228: __copy_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
