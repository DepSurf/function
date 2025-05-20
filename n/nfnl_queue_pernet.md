# Function: <code>nfnl_queue_pernet</code>

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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/nfnetlink_queue.c (ffffffff81999195)
Location: net/netfilter/nfnetlink_queue.c:91
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_init
  - net/netfilter/nfnetlink_queue.c:seq_stop
  - net/netfilter/nfnetlink_queue.c:seq_next
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_nl_event
  - net/netfilter/nfnetlink_queue.c:nfqnl_nf_hook_drop
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_dev_event
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
