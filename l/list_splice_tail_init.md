# Function: <code>list_splice_tail_init</code>

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
In kernel/exit.c (ffffffff81083e46)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810990dd)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup.c (ffffffff81116b96)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In block/blk-mq.c (ffffffff813c47c6)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/dd.c (ffffffff8154b4ec)
Location: include/linux/list.h:336
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81633500)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff8171afb8)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff81734d0c)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
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
In kernel/exit.c (ffffffff81086eeb)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff8109c6c5)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup.c (ffffffff8111de8d)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In block/blk-mq.c (ffffffff8140a13e)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/dd.c (ffffffff8159d1dc)
Location: include/linux/list.h:336
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816941f3)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff8178381c)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817a0e47)
Location: include/linux/list.h:336
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
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
In kernel/exit.c (ffffffff8108be57)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a1856)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup.c (ffffffff811261bd)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In block/blk-mq.c (ffffffff81424b59)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff815cb71c)
Location: include/linux/list.h:349
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816238cc)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c22d3)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff817b0dd5)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817cfa75)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
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
In kernel/exit.c (ffffffff8108901a)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff8109eb96)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8112498a)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In block/blk-mq.c (ffffffff814304ab)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff815e02ec)
Location: include/linux/list.h:349
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8163861c)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d65a5)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff817d1159)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817eee85)
Location: include/linux/list.h:349
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
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
In kernel/exit.c (ffffffff8108fd74)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a53e0)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff81130aca)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In block/blk-mq.c (ffffffff8145c55b)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816473ac)
Location: include/linux/list.h:350
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816a0d1c)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81742cd5)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff8184b24e)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff81093947)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ab6b5)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8113f19a)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In block/blk-mq.c (ffffffff8148fe2b)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff8168289c)
Location: include/linux/list.h:350
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816dcfbd)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817837d8)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In net/core/dev.c (ffffffff8189564a)
Location: include/linux/list.h:350
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff8109bc01)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810b4735)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8114abba)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff813dced5)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814a973e)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816a23dc)
Location: include/linux/list.h:403
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816ff30d)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817aa738)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183ee47)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff818b72c2)
Location: include/linux/list.h:403
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810a01dd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ba33a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8115639a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff814089ec)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814d75a5)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816db11c)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817390bd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec865)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881b7d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff819030ec)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810a684b)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810c07ba)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff81161ffa)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff814202f2)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814f0925)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816ff0ec)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8175ce0d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181d735)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3a1d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81935e8c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810ac9ec)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c7f32)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8117345a)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff8146f038)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff815515d5)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/core.c (ffffffff817b4fbc)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_resume
```
```
In drivers/base/dd.c (ffffffff817b8cfc)
Location: include/linux/list.h:477
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8181c733)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1fa2)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff819845b8)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81a0ace7)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/mptcp/protocol.c (ffffffff81bacadf)
Location: include/linux/list.h:477
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In kernel/exit.c (ffffffff810a80ac)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c3054)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8117015a)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff81489798)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff8156d715)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8157329e)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/base/dd.c (ffffffff817cda6c)
Location: include/linux/list.h:495
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8182b783)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818faec2)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988658)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81a0bf37)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/mptcp/protocol.c (ffffffff81bbe61c)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_push_pending
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
In kernel/exit.c (ffffffff810a8ec4)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c4e7c)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff81170d8a)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff8148f01b)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff81575575)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8157b2ee)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff81706d1a)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff817089e8)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff817b13ec)
Location: include/linux/list.h:495
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8180eaa5)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddc82)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196ce7d)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff819f3129)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/mptcp/protocol.c (ffffffff81babd04)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_flush_join_list
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
In kernel/exit.c (ffffffff810ba9b1)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810d7a76)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8119745a)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff814e6a8b)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff815d9b88)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff815e065e)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff817825ca)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8178480c)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff8183a62c)
Location: include/linux/list.h:495
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81899085)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819797a2)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a1595a)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81aa3fa5)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/mptcp/protocol.c (ffffffff81c7da54)
Location: include/linux/list.h:495
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
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
In kernel/exit.c (ffffffff810d1577)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810f22b0)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff811c849b)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff81574828)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff816874f4)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8168f0cb)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff818b9040)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb4d4)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff8197ce7c)
Location: include/linux/list.h:504
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff819e2ffc)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6e8e)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7db8d)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81c1ca06)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810effb7)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff811130e0)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8120b48b)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff8161a62c)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff81745754)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8174dbcb)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff81a066f0)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07989)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09ff4)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff81aea26c)
Location: include/linux/list.h:504
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81b5ec5c)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61c0e)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1bafd)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81dcda96)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810fbf78)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff8111f47d)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff812209fe)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In mm/migrate.c (ffffffff8146b281)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
```
```
In fs/fuse/dev.c (ffffffff81652928)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff817816d4)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8178a14b)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff81a4f580)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50819)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52e6c)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff81b385fc)
Location: include/linux/list.h:504
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81bb2216)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8faf)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84c5d)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81e3e697)
Location: include/linux/list.h:504
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff81105488)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff8112972d)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123874e)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In mm/migrate.c (ffffffff8149a233)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
```
```
In fs/fuse/dev.c (ffffffff8168bf38)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff817c36b4)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff817cc8c8)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In drivers/dma/virt-dma.c (ffffffff81a9b220)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c4e9)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9ec1c)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/base/dd.c (ffffffff81b9009c)
Location: include/linux/list.h:585
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81c06706)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7de8f)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3c41d)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81efcf47)
Location: include/linux/list.h:585
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffff8000100fd71c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffff80001011d194)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffff8000101d33dc)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffff800010502e20)
Location: include/linux/list.h:463
Inline: True
```
```
In block/blk-mq.c (ffff8000105ef504)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/dma/virt-dma.c (ffff8000107fe704)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/amba-pl08x.c (ffff800010801e60)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff80001080505c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
```
```
In drivers/dma/mv_xor.c (ffff80001080680c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/base/dd.c (ffff8000108ea1cc)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffff80001095e5c4)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a578ac)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b7d4)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffff800010bd440c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (c035a90c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (c03731e4)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (c0416168)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (c06bf0a8)
Location: include/linux/list.h:463
Inline: True
```
```
In block/blk-mq.c (c079bcf0)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/dma/virt-dma.c (c091f9f4)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/amba-pl08x.c (c0922558)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/mv_xor.c (c092450c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/tegra20-apb-dma.c (c092987c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_tx_submit
```
```
In drivers/dma/ti/edma.c (c092da74)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_issue_pending
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
```
```
In drivers/dma/ti/omap-dma.c (c0932790)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_issue_pending
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
```
```
In drivers/base/dd.c (c09d81a0)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (c0b2a678)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (c0be9b58)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (c0cefc70)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (c000000000144654)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (c000000000167438)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (c00000000023e614)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (c0000000006471cc)
Location: include/linux/list.h:463
Inline: True
```
```
In block/blk-mq.c (c0000000007860d8)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (c000000000981150)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (c000000000a105f8)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b2553c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd5e0)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (c000000000cb347c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffe0000c5f30)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffe0000d76ec)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffe00014cbf8)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffe00036fbe4)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffe00042ed66)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffe00057dfec)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffe0005cc55e)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000672cd0)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f903e)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffe00075e31a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810a016b)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810bab2a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8115a61a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff814188d2)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814e8f05)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816c48dc)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817114fd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d5b15)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff8185989d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff818d5e5c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff8108eb9b)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a946a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8114d90a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff81409352)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814d9475)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff8169fb5c)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816e4f7d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/md/dm-kcopyd.c (ffffffff81820ead)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff8188fc9a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810a011b)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ba08a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff811583ea)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff81414a72)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814e4f95)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff816f2dac)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817502cd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818125b5)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a8ecd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81926e8c)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In kernel/exit.c (ffffffff810a809f)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810c308a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8116543a)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In fs/fuse/dev.c (ffffffff8142b2e2)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In block/blk-mq.c (ffffffff814fddc3)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
```
```
In drivers/base/dd.c (ffffffff8170d5dc)
Location: include/linux/list.h:463
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8176b74d)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182d085)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c52dd)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff819484dc)
Location: include/linux/list.h:463
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
</details>
</li>
</ul>

## Differences
