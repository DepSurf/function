# Function: <code>timer_shutdown_sync</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int timer_shutdown_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d70c0)
Location: kernel/time/timer.c:1668
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - block/blk-iocost.c:ioc_rqos_exit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/block/loop.c:lo_free_disk
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff811d70c0-ffffffff811d70dd: timer_shutdown_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int timer_shutdown_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb540)
Location: kernel/time/timer.c:1668
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - block/blk-iocost.c:ioc_rqos_exit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/block/loop.c:lo_free_disk
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff811eb540-ffffffff811eb55d: timer_shutdown_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int timer_shutdown_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201570)
Location: kernel/time/timer.c:1668
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - block/blk-iocost.c:ioc_rqos_exit
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/block/loop.c:lo_free_disk
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81201570-ffffffff8120158d: timer_shutdown_sync (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
