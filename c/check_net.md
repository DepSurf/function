# Function: <code>check_net</code>

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
In net/ipv4/tcp.c (ffffffff818a635e)
Location: include/net/net_namespace.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7099)
Location: include/net/net_namespace.h:226
Inline: True
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
In net/ipv4/tcp.c (ffffffff818fb3cf)
Location: include/net/net_namespace.h:245
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c8f9)
Location: include/net/net_namespace.h:245
Inline: True
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
In net/ipv4/tcp.c (ffffffff81929313)
Location: include/net/net_namespace.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ac29)
Location: include/net/net_namespace.h:248
Inline: True
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
In net/ipv4/tcp.c (ffffffff8198c248)
Location: include/net/net_namespace.h:257
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff8199efc8)
Location: include/net/net_namespace.h:257
Inline: True
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
In net/ipv4/tcp.c (ffffffff819c2b98)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5a68)
Location: include/net/net_namespace.h:266
Inline: True
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
In kernel/bpf/net_namespace.c (ffffffff8122a7ac)
Location: include/net/net_namespace.h:276
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81aae1cb)
Location: include/net/net_namespace.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac20a8)
Location: include/net/net_namespace.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8123254c)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81ab8426)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdb28)
Location: include/net/net_namespace.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
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
In kernel/bpf/net_namespace.c (ffffffff812366ec)
Location: include/net/net_namespace.h:271
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81aa3720)
Location: include/net/net_namespace.h:271
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8cd8)
Location: include/net/net_namespace.h:271
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
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
In kernel/bpf/net_namespace.c (ffffffff81270ccc)
Location: include/net/net_namespace.h:273
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81b5f8ab)
Location: include/net/net_namespace.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81b75ef8)
Location: include/net/net_namespace.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812bfdac)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81cee36e)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05839)
Location: include/net/net_namespace.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8132358c)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81eb15a6)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81eca969)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff813537bc)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81f0fc36)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81f294bb)
Location: include/net/net_namespace.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137acac)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In net/ipv4/tcp.c (ffffffff81fd3e26)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81fedffb)
Location: include/net/net_namespace.h:289
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
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
In net/ipv4/tcp.c (ffff800010c759a8)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffff800010c88c50)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (c0d84034)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (c0d979e0)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (c000000000d7d158)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (c000000000d95870)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (ffffffe0007d8b1c)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9974)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (ffffffff81962a08)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff819758d8)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (ffffffff8191c4f8)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f398)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (ffffffff819cd1d8)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff819e00a8)
Location: include/net/net_namespace.h:266
Inline: True
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
In net/ipv4/tcp.c (ffffffff819d6d68)
Location: include/net/net_namespace.h:266
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9d68)
Location: include/net/net_namespace.h:266
Inline: True
```
</details>
</li>
</ul>

## Differences
