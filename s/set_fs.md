# Function: <code>set_fs</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81086d98)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff8108f886)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff810e8a10)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/module.c (ffffffff8112524d)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c34)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/callchain.c (ffffffff811c339d)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff811d2dbe)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff8127409c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff8127b87c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812aa201)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812b452c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff812da5d6)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd6ee)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff8141de00)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff8182528c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/socket.c:kernel_sock_ioctl
  - net/socket.c:kernel_sock_ioctl
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/compat.c (ffffffff8187775a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e93db)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff8191687a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/exthdrs.c (ffffffff8193ebac)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
  - net/ipv6/exthdrs.c:ipv6_renew_options_kern
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810933f6)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff810f0d20)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/module.c (ffffffff81133602)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6151)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/core.c (ffffffff811dfe34)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff811e374f)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff811f4142)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff8129ae0c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812a20dc)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812d1f8f)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812dbb4c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff8130620f)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309ba7)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff814500b0)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff8187024a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/compat.c (ffffffff818c91d7)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff8193f01d)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff8196df1a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b6b6)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff810fc3b0)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/module.c (ffffffff8113ef77)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/events/core.c (ffffffff811f0284)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff811f3c1d)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff812064d2)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812afd0c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812b6dfc)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff812e736c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff812f123c)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/binfmt_elf.c (ffffffff8131b99f)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f3a7)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In security/integrity/iint.c (ffffffff8146d090)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff81890e1a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/compat.c (ffffffff818f4087)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff8196f76d)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff819a3a9a)
Location: arch/x86/include/asm/uaccess.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109fd25)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff81104bff)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff81126136)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114a39b)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff811f869d)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff81207adf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8120b90f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff8121da76)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812ca37c)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812d3b5f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff813059c0)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8131389f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff81330aea)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81343361)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346cf8)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81365237)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff8149a780)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff818db70a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff819d8fd8)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a0fde3)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6328)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff81110faf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff81132106)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff81155ffa)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff8120550d)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff81214e4f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff81218bef)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff8122b516)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812dbd9c)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812e56ef)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81318a50)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff813267af)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff81344498)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff8135b79f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f006)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d4c7)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff814b4980)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff8190de5a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a0fd48)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a46b23)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae0e9)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/kthread.c (ffffffff810d1082)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/stacktrace.c (ffffffff8114154e)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/events/core.c (ffffffff812320d7)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (ffffffff812448ab)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff8125840b)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In fs/read_write.c (ffffffff81311c0b)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/exec.c (ffffffff8131e590)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/splice.c (ffffffff81351d1c)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
```
```
In net/socket.c (ffffffff819df459)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_fs(mm_segment_t fs);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008e7c0)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
```
```
In kernel/exit.c (ffff8000100fd2c8)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/module.c (ffff8000101c1818)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
```
```
In kernel/bpf/cgroup.c (ffff80001028e0a8)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffff8000102983f0)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (ffff8000102a3a2c)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffff8000102b9f8c)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffff800010381788)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffff80001038db78)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffff8000103cfa54)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffff8000103e0b68)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffff80001040609c)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffff800010421134)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104249e0)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffff80001044a0ec)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffff8000105ac9dc)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4be3c)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/arm_sdei.c:sdei_event_handler
```
```
In net/socket.c (ffff800010ba2d34)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
Direct callers:
  - net/socket.c:__arm64_sys_setsockopt
```
```
In net/ipv4/ipmr.c (ffff800010ccbca4)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffff800010d09678)
Location: arch/arm64/include/asm/uaccess.h:28
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
**Symbols:**

```
ffff800010ba28f0-ffff800010ba2934: set_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f5b8)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:dump_mem
  - arch/arm/kernel/traps.c:dump_mem
```
```
In kernel/exit.c (c035a3b8)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/module.c (c040c4fc)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (c04be050)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (c04ceb70)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (c04d3260)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (c04e60c0)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (c056bfa0)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (c0574c7c)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (c05aab08)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (c05b9164)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (c05d5c84)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (c05e8fa0)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/binfmt_elf_fdpic.c (c05e9d68)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
```
In fs/proc/proc_sysctl.c (c060f588)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (c075c368)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (c0cc3c9c)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (c0dd5030)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (c0e0fca8)
Location: arch/arm/include/asm/uaccess.h:65
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0000000001440e4)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/module.c (c00000000022cbdc)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (c00000000033aaf0)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (c0000000003427c4)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (c000000000355e68)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (c000000000371f90)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (c000000000477bdc)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (c000000000485320)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (c0000000004d1f78)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (c0000000004e5ed0)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (c00000000050ef4c)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (c00000000052ffbc)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c000000000533bd4)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (c000000000561f5c)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (c00000000072aef8)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (c000000000c76470)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (c000000000de78e4)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (c000000000e33e3c)
Location: arch/powerpc/include/asm/uaccess.h:34
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/process.c (ffffffe0000b5996)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/riscv/kernel/process.c:start_thread
```
```
In kernel/exit.c (ffffffe0000c5b76)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/module.c (ffffffe000145d12)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffe0001c0be4)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffe0001ce984)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffe0001d1fa8)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffe0001dd2b0)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffe000256778)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffe00025ec3c)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
```
In fs/splice.c (ffffffe00028bb72)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffe000296ffe)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffe0002afb88)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffe0002c16d2)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffe0002df870)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffe0003f5164)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffe000739d32)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffe00081d478)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffe0008513be)
Location: arch/riscv/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109fc48)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff8110958f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff8112a8b6)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114e61a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff811fdb2d)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8120d49f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8121123f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff81223b66)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812d437c)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ddccf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81311030)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8131ed8f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8133ca78)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81353d7f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813575e6)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81375aa7)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff814acf60)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff818ade5a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff819af768)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff819e61b3)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e678)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff810fa46f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff8111d126)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff811418ca)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff811f087d)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8120026f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff81203fcf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff81216d16)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812c4ffc)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ce94f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81301c40)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8130f92f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8132d748)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81344a3f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81348296)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81366577)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff8149d980)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff81867daa)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff8196bd98)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff819a2f73)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109fbf8)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff8110747f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff811285d6)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8114c4ca)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff811fb8fd)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8120b23f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8120efdf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff81221906)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812d218c)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812dbadf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff8130ee20)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8131c85f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8133a548)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff8135184f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813550b6)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff81373577)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff814a9000)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff818fee5a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1a008)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a50c33)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7b68)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/user.c (ffffffff8111283f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/stacktrace.c (ffffffff81134c66)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff811591b0)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
```
In kernel/bpf/cgroup.c (ffffffff8120a4ad)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffffffff8121a04f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (ffffffff8121deef)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/maccess.c (ffffffff81230ac6)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In fs/read_write.c (ffffffff812e2fec)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffffffff812ecaaf)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/splice.c (ffffffff81320620)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/block_dev.c (ffffffff8132eb5f)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/io_uring.c (ffffffff8134d0a8)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/binfmt_elf.c (ffffffff81364def)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81368696)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/proc/proc_sysctl.c (ffffffff813878c7)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/integrity/iint.c (ffffffff814c1a10)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In net/socket.c (ffffffff8191fe4a)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a24e38)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv6/addrconf.c (ffffffff81a5cb63)
Location: arch/x86/include/asm/uaccess.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
