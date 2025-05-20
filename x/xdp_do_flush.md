# Function: <code>xdp_do_flush</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29980)
Location: net/core/filter.c:3532
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff81a29980-ffffffff81a2999a: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a2e0)
Location: net/core/filter.c:3939
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81a2a2e0-ffffffff81a2a2fa: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11540)
Location: net/core/filter.c:3918
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81a11540-ffffffff81a1155a: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac29a0)
Location: net/core/filter.c:3914
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81ac29a0-ffffffff81ac29ba: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d5a0)
Location: net/core/filter.c:4134
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81c3d5a0-ffffffff81c3d5be: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df1720)
Location: net/core/filter.c:4148
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81df1720-ffffffff81df173e: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e636b0)
Location: net/core/filter.c:4202
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81e636b0-ffffffff81e636ce: xdp_do_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_do_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f228a0)
Location: net/core/filter.c:4267
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81f228a0-ffffffff81f228be: xdp_do_flush (STB_GLOBAL)
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
