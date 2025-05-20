# Function: <code>get_random_u8</code>

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
u8 get_random_u8();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93770)
Location: drivers/char/random.c:530
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - net/core/stream.c:sk_stream_wait_memory
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv6/route.c:rt6_insert_exception
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81a93770-ffffffff81a9389e: get_random_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 get_random_u8();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf260)
Location: drivers/char/random.c:530
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/kfence/core.c:kfence_guarded_alloc
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - net/core/stream.c:sk_stream_wait_memory
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv6/route.c:rt6_insert_exception
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81adf260-ffffffff81adf38e: get_random_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 get_random_u8();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32680)
Location: drivers/char/random.c:530
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/kfence/core.c:kfence_guarded_alloc
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - net/core/stream.c:sk_stream_wait_memory
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv6/route.c:rt6_insert_exception
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81b32680-ffffffff81b327ae: get_random_u8 (STB_GLOBAL)
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
