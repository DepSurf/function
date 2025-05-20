# Function: <code>modify_domain</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In kernel/module.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In mm/maccess.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/exec.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/splice.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/block_dev.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In security/integrity/iint.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In net/socket.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: arch/arm/include/asm/domain.h:125
Inline: True
```
</details>
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
