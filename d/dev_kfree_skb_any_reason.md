# Function: <code>dev_kfree_skb_any_reason</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_kfree_skb_any_reason(struct sk_buff *skb, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2ee90)
Location: net/core/dev.c:3160
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/net_failover.c:net_failover_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81e2ee90-ffffffff81e2eefa: dev_kfree_skb_any_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_kfree_skb_any_reason(struct sk_buff *skb, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eedb10)
Location: net/core/dev.c:3163
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/net_failover.c:net_failover_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81eedb10-ffffffff81eedb7a: dev_kfree_skb_any_reason (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
