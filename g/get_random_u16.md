# Function: <code>get_random_u16</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 get_random_u16();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a938b0)
Location: drivers/char/random.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/module.c:module_alloc
  - fs/ext4/super.c:ext4_register_li_request
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
**Symbols:**

```
ffffffff81a938b0-ffffffff81a939e3: get_random_u16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 get_random_u16();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf3a0)
Location: drivers/char/random.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/module.c:module_alloc
  - fs/ext4/super.c:ext4_register_li_request
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
**Symbols:**

```
ffffffff81adf3a0-ffffffff81adf4d3: get_random_u16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 get_random_u16();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b327c0)
Location: drivers/char/random.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/module.c:module_alloc
  - fs/ext4/super.c:ext4_register_li_request
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
**Symbols:**

```
ffffffff81b327c0-ffffffff81b328f3: get_random_u16 (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
