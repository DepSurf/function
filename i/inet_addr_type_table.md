# Function: <code>inet_addr_type_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179a390)
Location: net/ipv4/fib_frontend.c:243
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8179a390-ffffffff8179a453: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81808ff9)
Location: net/ipv4/fib_frontend.c:244
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81808270-ffffffff81808330: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8183a0ef)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81839350-ffffffff81839410: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185b896)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8185a870-ffffffff8185a94b: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818db786)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff818da7a0-ffffffff818da87b: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81932206)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81931710-ffffffff819317f3: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81961a66)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81960f70-ffffffff81961053: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c61ed)
Location: net/ipv4/fib_frontend.c:245
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819c4cf0-ffffffff819c4d0d: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fcd9d)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819fb890-ffffffff819fb8ad: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeafc5)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81aeaca0-ffffffff81aeacb6: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af7e9a)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81af7b60-ffffffff81af7b76: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae35aa)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ae3270-ffffffff81ae3286: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba2eaa)
Location: net/ipv4/fib_frontend.c:236
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ba2b70-ffffffff81ba2b86: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d35608)
Location: net/ipv4/fib_frontend.c:237
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ping.c:ping_check_bind_addr
```
**Symbols:**

```
ffffffff81d352c0-ffffffff81d352e2: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efdb78)
Location: net/ipv4/fib_frontend.c:237
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ping.c:ping_check_bind_addr
```
**Symbols:**

```
ffffffff81efd820-ffffffff81efd842: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5d5fd)
Location: net/ipv4/fib_frontend.c:237
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ping.c:ping_check_bind_addr
```
**Symbols:**

```
ffffffff81f5d290-ffffffff81f5d2b2: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82023bbc)
Location: net/ipv4/fib_frontend.c:237
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ping.c:ping_check_bind_addr
```
**Symbols:**

```
ffffffff82023820-ffffffff82023842: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb44ec)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffff800010cb3768-ffff800010cb37b0: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dbf8d8)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c0dbff04-c0dc0054: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc5cc)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c000000000dca410-c000000000dca434: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080c1de)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffe00080b406-ffffffe00080b444: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199cb3d)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8199b630-ffffffff8199b64d: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819565fd)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819550f0-ffffffff8195510d: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a073dd)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a05ed0-ffffffff81a05eed: inet_addr_type_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_table(struct net *net, __be32 addr, u32 tb_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a11b31)
Location: net/ipv4/fib_frontend.c:246
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
Direct callers:
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a104e0-ffffffff81a104fd: inet_addr_type_table (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
