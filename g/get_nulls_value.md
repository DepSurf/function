# Function: <code>get_nulls_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:48
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:48
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/list_nulls.h:48
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/list_nulls.h:48
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce73d)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfdee)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818732b1)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fe54d)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffbde)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a78d1)
Location: include/linux/list_nulls.h:48
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a46b)
Location: include/linux/list_nulls.h:53
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e8f6)
Location: include/linux/list_nulls.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fdac)
Location: include/linux/list_nulls.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce137)
Location: include/linux/list_nulls.h:53
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9c7b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189db2a)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ed7d)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952f60)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811c1130)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1d17)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f37fc)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac4f7)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811d2690)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f8ae)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8192131c)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e30d0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811e6e03)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819821a4)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c8d)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51e60)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811f3563)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8a04)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba46d)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88a60)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff81216d8f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa336a)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f98)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8408f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff8121914f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad89a)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf603)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b938ef)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bc5c32)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff8121cb4f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9895b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a90b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82a0f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bb67a2)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff81253a4f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53e3b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d7b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4eadf)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81c85816)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff8129be62)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce199e)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3aa3)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def3e5)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81e2ba6b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff812f8362)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2b5e)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea64a7)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc34a5)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff82003c4b)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff813263b2)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In mm/vmscan.c (ffffffff813b8092)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f0137e)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c7f)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820242f7)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff8207fda0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffffffff8134a9f2)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In mm/vmscan.c (ffffffff813e0f13)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc56ce)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f83)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3467)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff82155290)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
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
In kernel/bpf/hashtab.c (ffff8000102773a4)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69ee4)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bfe4)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d5570c)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (c04a9cdc)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (c0d79198)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7ae00)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (c0e55cc0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (c00000000031f910)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (c000000000d6efe0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71614)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e5c0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffe0001af658)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfc94)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d19ac)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088ceee)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811ebb83)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958874)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a2dd)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a280f0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811de913)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912364)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913dcd)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4eb0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811e9953)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199df44)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a10ee)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_next
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3044)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4aad)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93ca0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811f7d23)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819ccb14)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce546)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fdf0)
Location: include/linux/list_nulls.h:54
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
</li>
</ul>

## Differences
