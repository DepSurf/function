# Function: <code>nfnl_unlock</code>

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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nfnl_unlock(__u8 subsys_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nfnetlink.c (ffffffff8199897f)
Location: net/netfilter/nfnetlink.c:66
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_msg
  - net/netfilter/nfnetlink.c:nfnetlink_subsys_unregister
Direct callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
**Symbols:**

```
ffffffff81998210-ffffffff81998230: nfnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
