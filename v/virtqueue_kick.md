# Function: <code>virtqueue_kick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf7a0)
Location: drivers/virtio/virtio_ring.c:423
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_control_msg
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff814bf7a0-ffffffff814bf7d9: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150fa80)
Location: drivers/virtio/virtio_ring.c:593
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff8150fa80-ffffffff8150fab9: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153bf40)
Location: drivers/virtio/virtio_ring.c:593
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8153bf40-ffffffff8153bf79: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f780)
Location: drivers/virtio/virtio_ring.c:622
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8154f780-ffffffff8154f7b9: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b3090)
Location: drivers/virtio/virtio_ring.c:621
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff815b3090-ffffffff815b30cf: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb170)
Location: drivers/virtio/virtio_ring.c:620
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff815eb170-ffffffff815eb1af: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605070)
Location: drivers/virtio/virtio_ring.c:1865
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81605070-ffffffff816050b2: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81638270)
Location: drivers/virtio/virtio_ring.c:1870
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81638270-ffffffff816382b2: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165a060)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8165a060-ffffffff8165a0a2: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170afae)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170a3c0-ffffffff8170a404: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727dfe)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff817278f0-ffffffff81727934: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b430)
Location: drivers/virtio/virtio_ring.c:1871
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
```
**Symbols:**

```
ffffffff8170b430-ffffffff8170b474: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1969
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff81cf4a04-ffffffff81cf4a19: virtqueue_kick.cold (STB_LOCAL)
ffffffff81787500-ffffffff81787554: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1973
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff81ebcad3-ffffffff81ebcae8: virtqueue_kick.cold (STB_LOCAL)
ffffffff818be6a0-ffffffff818be6fa: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2259
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffffffff82093f51-ffffffff82093f66: virtqueue_kick.cold (STB_LOCAL)
ffffffff81a0db90-ffffffff81a0dbea: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2296
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff82114c9a-ffffffff82114caf: virtqueue_kick.cold (STB_LOCAL)
ffffffff81a56ae0-ffffffff81a56b3a: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2390
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/net/virtio_net.c:virtnet_send_command
```
**Symbols:**

```
ffffffff821f28f0-ffffffff821f2905: virtqueue_kick.cold (STB_LOCAL)
ffffffff81aa7cf0-ffffffff81aa7d4a: virtqueue_kick (STB_GLOBAL)
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
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822258)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
**Symbols:**

```
ffff800010822258-ffff8000108222c8: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093fb78)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
c093fb78-c093fbd8: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc6e0)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
c0000000008cc6e0-c0000000008cc788: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518bbc)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffe000518bbc-ffffffe000518c0c: virtqueue_kick (STB_GLOBAL)
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
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161ff00)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff8161ff00-ffffffff8161ff42: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81614490)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81614490-ffffffff816144d2: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164dea0)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
  - drivers/scsi/virtio_scsi.c:virtscsi_kick_event
```
**Symbols:**

```
ffffffff8164dea0-ffffffff8164dee2: virtqueue_kick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick(struct virtqueue *vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81668530)
Location: drivers/virtio/virtio_ring.c:1869
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:add_inbuf
```
**Symbols:**

```
ffffffff81668530-ffffffff81668572: virtqueue_kick (STB_GLOBAL)
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
