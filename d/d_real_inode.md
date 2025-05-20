# Function: <code>d_real_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812413ed)
Location: include/linux/dcache.h:587
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
```
```
In net/unix/af_unix.c (ffffffff8182d9a2)
Location: include/linux/dcache.h:587
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
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
In fs/inode.c (ffffffff81264926)
Location: include/linux/dcache.h:587
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/locks.c (ffffffff812a0423)
Location: include/linux/dcache.h:587
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
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
In fs/inode.c (ffffffff8127214f)
Location: include/linux/dcache.h:593
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
```
```
In fs/locks.c (ffffffff812af253)
Location: include/linux/dcache.h:593
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2c23)
Location: include/linux/dcache.h:598
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
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
In kernel/trace/trace_uprobe.c (ffffffff811ae71c)
Location: include/linux/dcache.h:599
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In fs/locks.c (ffffffff812fcc2d)
Location: include/linux/dcache.h:599
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811bcd90)
Location: include/linux/dcache.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cc493)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d89f0)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f57c5)
Location: include/linux/dcache.h:595
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4155)
Location: include/linux/dcache.h:596
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4d00)
Location: include/linux/dcache.h:599
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81226f10)
Location: include/linux/dcache.h:599
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81266a4d)
Location: include/linux/dcache.h:589
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b8ca2)
Location: include/linux/dcache.h:589
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812dc302)
Location: include/linux/dcache.h:589
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/bpf_trace.c (ffffffff812ea55a)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_unregister
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa3e2)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In security/integrity/ima/ima_main.c (ffffffff8177113a)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_api.c (ffffffff8177464b)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff800010259a70)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048ba14)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fd284)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d1010)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c3de0)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cede0)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811dd070)
Location: include/linux/dcache.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
</ul>

## Differences
