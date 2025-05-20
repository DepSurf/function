# Function: <code>ktime_to_ns</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:79
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:79
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-crypto-fallback.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/ktime.h:80
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:80
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/trace/trace_osnoise.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-flush.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In io_uring/cancel.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/pmdomain/core.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/pmdomain/governor.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/ktime.h:78
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/ktime.h:78
Inline: True
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
In virt/kvm/kvm_main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/soc/bcm/bcm2835-power.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-pin.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In arch/arm/common/bL_switcher.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/clk/ti/clkctrl.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/netfilter/nf_conntrack_standalone.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
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
In kernel/fork.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/itimer.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/delayacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/connector/cn_proc.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/media/cec/cec-pin.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/secure_seq.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/ktime.h:97
Inline: True
```
</details>
</li>
</ul>

## Differences
