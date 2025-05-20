# Function: <code>completion_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c3bd0)
Location: kernel/sched/completion.c:298
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
**Symbols:**

```
ffffffff810c3bd0-ffffffff810c3bf8: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c7850)
Location: kernel/sched/completion.c:298
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
**Symbols:**

```
ffffffff810c7850-ffffffff810c7872: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810cd710)
Location: kernel/sched/completion.c:298
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810cd710-ffffffff810cd732: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ca140)
Location: kernel/sched/completion.c:301
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ca140-ffffffff810ca162: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d19b0)
Location: kernel/sched/completion.c:316
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810d19b0-ffffffff810d19e2: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d9f70)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810d9f70-ffffffff810d9fa2: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810e3ac0)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810e3ac0-ffffffff810e3af2: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ea6d0)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ea6d0-ffffffff810ea704: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f60a0)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810f60a0-ffffffff810f60d4: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ff920)
Location: kernel/sched/completion.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ff920-ffffffff810ff956: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810fe430)
Location: kernel/sched/completion.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810fe430-ffffffff810fe466: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81100810)
Location: kernel/sched/completion.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff81100810-ffffffff81100846: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8111c870)
Location: kernel/sched/completion.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - block/blk-exec.c:blk_execute_rq
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8111c870-ffffffff8111c8a6: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113e5c0)
Location: kernel/sched/completion.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - block/blk-mq.c:blk_execute_rq
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8113e5c0-ffffffff8113e609: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168c40)
Location: kernel/sched/completion.c:327
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - block/blk-mq.c:blk_execute_rq
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff81168c40-ffffffff81168c89: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811791f0)
Location: kernel/sched/completion.c:327
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - block/blk-mq.c:blk_execute_rq
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff811791f0-ffffffff81179239: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81186d30)
Location: kernel/sched/completion.c:337
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - block/blk-mq.c:blk_execute_rq
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff81186d30-ffffffff81186d79: completion_done (STB_GLOBAL)
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
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010159b40)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffff800010159b40-ffff800010159bf8: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c03a6b90)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
c03a6b90-c03a6bd8: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0000000001adf30)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
c0000000001adf30-c0000000001adfa8: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0000ff7e4)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffe0000ff7e4-ffffffe0000ff826: completion_done (STB_GLOBAL)
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
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ef4a0)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ef4a0-ffffffff810ef4d4: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810df510)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
```
**Symbols:**

```
ffffffff810df510-ffffffff810df544: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ec5d0)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ec5d0-ffffffff810ec604: completion_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool completion_done(struct completion *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f7610)
Location: kernel/sched/completion.c:313
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_is_req_done
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810f7610-ffffffff810f7644: completion_done (STB_GLOBAL)
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
