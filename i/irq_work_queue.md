# Function: <code>irq_work_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81170f00)
Location: kernel/irq_work.c:87
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - kernel/printk/printk.c:printk_deferred
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:ring_buffer_put_async
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
**Symbols:**

```
ffffffff81170f00-ffffffff81170f99: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8117e5f0)
Location: kernel/irq_work.c:87
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff8117e5f0-ffffffff8117e68d: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118a200)
Location: kernel/irq_work.c:87
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk.c:console_unlock
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff8118a200-ffffffff8118a29d: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118cd10)
Location: kernel/irq_work.c:87
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:console_unlock
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff8118cd10-ffffffff8118cdae: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8119a720)
Location: kernel/irq_work.c:90
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:console_unlock
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff8119a720-ffffffff8119a7bf: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811b0160)
Location: kernel/irq_work.c:90
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811b0160-ffffffff811b01f8: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811be770)
Location: kernel/irq_work.c:90
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811be770-ffffffff811be808: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811ce370)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811ce370-ffffffff811ce3ba: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811da990)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811da990-ffffffff811da9da: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f73e0)
Location: kernel/irq_work.c:67
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811f73e0-ffffffff811f7413: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f5f50)
Location: kernel/irq_work.c:67
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811f5f50-ffffffff811f5f83: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6e40)
Location: kernel/irq_work.c:67
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811f6e40-ffffffff811f6e80: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81228410)
Location: kernel/irq_work.c:67
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81228410-ffffffff81228450: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81269430)
Location: kernel/irq_work.c:106
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81269430-ffffffff81269499: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be2a0)
Location: kernel/irq_work.c:106
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff812be2a0-ffffffff812be309: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e4ee0)
Location: kernel/irq_work.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff812e4ee0-ffffffff812e4f49: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81302f90)
Location: kernel/irq_work.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/pid_list.c:trace_pid_list_set
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81302f90-ffffffff81302ff9: irq_work_queue (STB_GLOBAL)
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
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025b190)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_disable_inatomic
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/acpi/apei/ghes.c:ghes_sdei_critical_callback
  - drivers/acpi/apei/ghes.c:ghes_sdei_normal_callback
  - drivers/acpi/apei/ghes.c:ghes_notify_sea
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffff80001025b190-ffff80001025b1c8: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e2b0)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
c048e2b0-c048e2dc: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002fee10)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/powerpc/kernel/mce.c:machine_check_queue_event
  - arch/powerpc/kernel/mce.c:save_mce_event
  - arch/powerpc/platforms/pseries/ras.c:pseries_machine_check_realmode
  - arch/powerpc/platforms/pseries/ras.c:pseries_machine_check_realmode
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
c0000000002fee10-c0000000002fee60: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffe00019a1b4)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
**Symbols:**

```
ffffffe00019a1b4-ffffffe00019a21a: irq_work_queue (STB_GLOBAL)
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
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d2fb0)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811d2fb0-ffffffff811d2ffa: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811c5d70)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811c5d70-ffffffff811c5dba: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d0d80)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811d0d80-ffffffff811d0dca: irq_work_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_queue(struct irq_work *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811df040)
Location: kernel/irq_work.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_log
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/relay.c:relay_switch_subbuf
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811df040-ffffffff811df0a4: irq_work_queue (STB_GLOBAL)
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
