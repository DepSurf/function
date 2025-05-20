# Function: <code>virtqueue_get_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bfc20)
Location: drivers/virtio/virtio_ring.c:477
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_control_msg
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
**Symbols:**

```
ffffffff814bfc20-ffffffff814bfd32: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150fca0)
Location: drivers/virtio/virtio_ring.c:663
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
**Symbols:**

```
ffffffff8150fca0-ffffffff8150fdc1: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153bdc0)
Location: drivers/virtio/virtio_ring.c:663
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8153bdc0-ffffffff8153bee1: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f8f0)
Location: drivers/virtio/virtio_ring.c:758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8154f8f0-ffffffff8154f902: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2fb0)
Location: drivers/virtio/virtio_ring.c:757
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff815b2fb0-ffffffff815b2fc2: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb4c0)
Location: drivers/virtio/virtio_ring.c:756
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff815eb4c0-ffffffff815eb4d2: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605b20)
Location: drivers/virtio/virtio_ring.c:1899
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81605b20-ffffffff81605b32: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163ac80)
Location: drivers/virtio/virtio_ring.c:1905
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8163ac80-ffffffff8163ac92: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165d140)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8165d140-ffffffff8165d152: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ab50)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170ab50-ffffffff8170ab6f: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817276c0)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff817276c0-ffffffff817276df: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b300)
Location: drivers/virtio/virtio_ring.c:1906
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170b300-ffffffff8170b31f: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2004
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff81cf49f0-ffffffff81cf4a04: virtqueue_get_buf.cold (STB_LOCAL)
ffffffff817874b0-ffffffff817874f6: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2008
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff81ebcabe-ffffffff81ebcad3: virtqueue_get_buf.cold (STB_LOCAL)
ffffffff818be640-ffffffff818be69d: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2294
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff82093f3c-ffffffff82093f51: virtqueue_get_buf.cold (STB_LOCAL)
ffffffff81a0db20-ffffffff81a0db7d: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2331
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
**Symbols:**

```
ffffffff82114c85-ffffffff82114c9a: virtqueue_get_buf.cold (STB_LOCAL)
ffffffff81a56a70-ffffffff81a56acd: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2425
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/scsi/virtio_scsi.c:virtscsi_mq_poll
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
**Symbols:**

```
ffffffff821f28b1-ffffffff821f28c6: virtqueue_get_buf.cold (STB_LOCAL)
ffffffff81aa7b90-ffffffff81aa7bed: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108233f0)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffff8000108233f0-ffff800010823428: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940f60)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
c0940f60-c0940f80: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d0e90)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
c0000000008d0e90-c0000000008d0ea8: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519c56)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffe000519c56-ffffffe000519c8a: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622fe0)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81622fe0-ffffffff81622ff2: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81617630)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81617630-ffffffff81617642: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650f80)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/scsi/virtio_scsi.c:virtscsi_vq_done
```
**Symbols:**

```
ffffffff81650f80-ffffffff81650f92: virtqueue_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *virtqueue_get_buf(struct virtqueue *_vq, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166b610)
Location: drivers/virtio/virtio_ring.c:1904
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8166b610-ffffffff8166b622: virtqueue_get_buf (STB_GLOBAL)
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
