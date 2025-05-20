# Function: <code>scsi_prot_sg_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a5d26)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad6ab)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
```
```
In drivers/scsi/sd.c (ffffffff815ba8ff)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fde2e)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605707)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff81613057)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162d42c)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81634c27)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff8164332c)
Location: include/scsi/scsi_cmnd.h:308
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81642aed)
Location: include/scsi/scsi_cmnd.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649bcd)
Location: include/scsi/scsi_cmnd.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff8165977c)
Location: include/scsi/scsi_cmnd.h:313
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816abb22)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b234d)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff816c414c)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8090)
Location: include/scsi/scsi_cmnd.h:322
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff816eef5d)
Location: include/scsi/scsi_cmnd.h:322
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff817006a8)
Location: include/scsi/scsi_cmnd.h:322
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170bb90)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712a30)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff817234be)
Location: include/scsi/scsi_cmnd.h:319
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747298)
Location: include/scsi/scsi_cmnd.h:291
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e3a7)
Location: include/scsi/scsi_cmnd.h:291
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff8175eaab)
Location: include/scsi/scsi_cmnd.h:291
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176b3e8)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81772557)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff817822bc)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182d6da)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183811c)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/sd.c (ffffffff81843e03)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183e71a)
Location: include/scsi/scsi_cmnd.h:293
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848a5e)
Location: include/scsi/scsi_cmnd.h:293
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/sd.c (ffffffff8185413e)
Location: include/scsi/scsi_cmnd.h:293
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818218d3)
Location: include/scsi/scsi_cmnd.h:295
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bd76)
Location: include/scsi/scsi_cmnd.h:295
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/sd.c (ffffffff81837b85)
Location: include/scsi/scsi_cmnd.h:295
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ac223)
Location: include/scsi/scsi_cmnd.h:320
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7938)
Location: include/scsi/scsi_cmnd.h:320
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (ffffffff818c4685)
Location: include/scsi/scsi_cmnd.h:320
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f6bf3)
Location: include/scsi/scsi_cmnd.h:310
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02eac)
Location: include/scsi/scsi_cmnd.h:310
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (ffffffff81a112f0)
Location: include/scsi/scsi_cmnd.h:310
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b74b06)
Location: include/scsi/scsi_cmnd.h:311
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b819fe)
Location: include/scsi/scsi_cmnd.h:311
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (ffffffff81b9157f)
Location: include/scsi/scsi_cmnd.h:311
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc85d9)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5743)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be28be)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
```
```
In drivers/scsi/sd.c (ffffffff81be7a8b)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1d149)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a397)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c37a9d)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
```
```
In drivers/scsi/sd.c (ffffffff81c3ce05)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096d294)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffff800010975a98)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffff800010988fa4)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a42c48)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (c0a4a358)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (c0a5af14)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a2626c)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (c000000000a2fcd8)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (c000000000a48f60)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d7be2)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de1d8)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffe0005ed1dc)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8171fad8)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81726c47)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff817369ac)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f8f08)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700077)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff8171864c)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175e8a8)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765a17)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/virtio_scsi.c (ffffffff817728a0)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
  - drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd
```
```
In drivers/scsi/sd.c (ffffffff8177713c)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81779f08)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (ffffffff817810a7)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
```
In drivers/scsi/sd.c (ffffffff81790f5c)
Location: include/scsi/scsi_cmnd.h:292
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
</ul>

## Differences
