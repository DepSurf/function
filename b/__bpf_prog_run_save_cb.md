# Function: <code>__bpf_prog_run_save_cb</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e1902)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818d5b97)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818e0b8d)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818f1011)
Location: include/linux/filter.h:594
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819dfef2)
Location: include/linux/filter.h:594
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff811f8b66)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81923335)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff8192f230)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff819429d1)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eb00)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff81205b96)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff8195555d)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819614a0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81977921)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a857a0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c4e0)
Location: include/linux/filter.h:679
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a28070)
Location: include/linux/filter.h:679
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a349a0)
Location: include/linux/filter.h:679
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a4c580)
Location: include/linux/filter.h:679
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f710)
Location: include/linux/filter.h:679
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff8122c4e0-ffffffff8122c5ed: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a28070-ffffffff81a2817d: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a349a0-ffffffff81a34aad: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a4c580-ffffffff81a4c68d: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81b7f710-ffffffff81b7f81d: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234910)
Location: include/linux/filter.h:688
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a28b00)
Location: include/linux/filter.h:688
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a36ce0)
Location: include/linux/filter.h:688
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a52200)
Location: include/linux/filter.h:688
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e6c0)
Location: include/linux/filter.h:688
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81234910-ffffffff81234a1d: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a28b00-ffffffff81a28c0d: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a36ce0-ffffffff81a36ded: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81a52200-ffffffff81a5230d: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81b8e6c0-ffffffff81b8e7cd: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239a06)
Location: include/linux/filter.h:731
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a1411a)
Location: include/linux/filter.h:731
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a1deec)
Location: include/linux/filter.h:731
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a37d90)
Location: include/linux/filter.h:731
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0ed)
Location: include/linux/filter.h:731
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812740f1)
Location: include/linux/filter.h:742
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81ac59ea)
Location: include/linux/filter.h:742
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad197c)
Location: include/linux/filter.h:742
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81aedba0)
Location: include/linux/filter.h:742
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a93d)
Location: include/linux/filter.h:742
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, const void *ctx);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c1dd0)
Location: include/linux/filter.h:745
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81c3c850)
Location: include/linux/filter.h:745
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81c4f220)
Location: include/linux/filter.h:745
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81c706d0)
Location: include/linux/filter.h:745
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff81de7ec0)
Location: include/linux/filter.h:745
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff812c1dd0-ffffffff812c1ef1: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81c3c850-ffffffff81c3c971: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81c4f220-ffffffff81c4f341: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81c706d0-ffffffff81c707f1: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81de7ec0-ffffffff81de7fe1: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, const void *ctx);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81326790)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81df4210)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81e043b0)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81e286c0)
Location: include/linux/filter.h:717
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb140)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81326790-ffffffff813268b1: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81df4210-ffffffff81df4331: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81e043b0-ffffffff81e044d1: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81e286c0-ffffffff81e287e1: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81fbb140-ffffffff81fbb261: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, const void *ctx);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81356ae0)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81e65e20)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81e76c00)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81e9dce0)
Location: include/linux/filter.h:717
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff8201b800)
Location: include/linux/filter.h:717
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81356ae0-ffffffff81356c02: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81e65e20-ffffffff81e65f42: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81e76c00-ffffffff81e76d22: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81e9dce0-ffffffff81e9de02: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff8201b800-ffffffff8201b922: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
u32 __bpf_prog_run_save_cb(const struct bpf_prog *prog, const void *ctx);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137f610)
Location: include/linux/filter.h:768
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81f24fd0)
Location: include/linux/filter.h:768
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81f36bc0)
Location: include/linux/filter.h:768
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81f60460)
Location: include/linux/filter.h:768
Inline: False
```
```
In net/ipv6/seg6_local.c (ffffffff820ea7c0)
Location: include/linux/filter.h:768
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff8137f610-ffffffff8137f732: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81f24fd0-ffffffff81f250f2: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81f36bc0-ffffffff81f36ce2: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff81f60460-ffffffff81f60582: __bpf_prog_run_save_cb (STB_LOCAL)
ffffffff820ea7c0-ffffffff820ea8e2: __bpf_prog_run_save_cb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028eb0c)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffff800010c02058)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffff800010c04d20)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffff800010c1ecf0)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d5183c)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (c04bddf4)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (c0d10458)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e1e8)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c0d3606c)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (c0e523dc)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (c00000000033b4b8)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (c000000000cdce10)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c000000000ceeeec)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c000000000d0fc34)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e89aa8)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffe0001c1d0e)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffe000778592)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffe00078397e)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffe000797d8e)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe000889a22)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff811fe1b6)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818f552d)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81901470)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81917791)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e30)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff811f0f06)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818af35d)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818bb2a0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818d1541)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bf0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff811fbf86)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff8194655d)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819524a0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81968921)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f8b0)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In kernel/bpf/cgroup.c (ffffffff8120ab8a)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81967e57)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81973ef2)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff8198acdf)
Location: include/linux/filter.h:650
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c640)
Location: include/linux/filter.h:650
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
