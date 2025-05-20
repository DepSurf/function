# Function: <code>bpf_lsm_socket_getpeersec_dgram</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812392d0)
Location: include/linux/lsm_hook_defs.h:296
Inline: False
```
**Symbols:**

```
ffffffff812392d0-ffffffff812392dd: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123dac0)
Location: include/linux/lsm_hook_defs.h:306
Inline: False
```
**Symbols:**

```
ffffffff8123dac0-ffffffff8123dacd: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278580)
Location: include/linux/lsm_hook_defs.h:306
Inline: False
```
**Symbols:**

```
ffffffff81278580-ffffffff8127858d: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8ce0)
Location: include/linux/lsm_hook_defs.h:305
Inline: False
```
**Symbols:**

```
ffffffff812c8ce0-ffffffff812c8cf1: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f530)
Location: include/linux/lsm_hook_defs.h:313
Inline: False
```
**Symbols:**

```
ffffffff8132f530-ffffffff8132f541: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813601a0)
Location: include/linux/lsm_hook_defs.h:314
Inline: False
```
**Symbols:**

```
ffffffff813601a0-ffffffff813601b1: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_dgram(struct socket *sock, struct sk_buff *skb, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389050)
Location: include/linux/lsm_hook_defs.h:324
Inline: False
```
**Symbols:**

```
ffffffff81389050-ffffffff81389064: bpf_lsm_socket_getpeersec_dgram (STB_GLOBAL)
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
