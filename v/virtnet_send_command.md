# Function: <code>virtnet_send_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info *vi, u8 class, u8 cmd, struct scatterlist *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f1ad0)
Location: drivers/net/virtio_net.c:981
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_config_changed_work
```
**Symbols:**

```
ffffffff815f1ad0-ffffffff815f1c12: virtnet_send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info *vi, u8 class, u8 cmd, struct scatterlist *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff816513e0)
Location: drivers/net/virtio_net.c:927
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff816513e0-ffffffff81651522: virtnet_send_command (STB_LOCAL)
```
</details>
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
bool virtnet_send_command(struct virtnet_info *vi, u8 class, u8 cmd, struct scatterlist *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81c4d000)
Location: drivers/net/virtio_net.c:2262
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff81c4d000-ffffffff81c4d1ee: virtnet_send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info *vi, u8 class, u8 cmd, struct scatterlist *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81d028b0)
Location: drivers/net/virtio_net.c:2514
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_send_rx_notf_coal_cmds
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff81d028b0-ffffffff81d02a9e: virtnet_send_command (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
