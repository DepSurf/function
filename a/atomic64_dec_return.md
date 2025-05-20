# Function: <code>atomic64_dec_return</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81246ced)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812a54f6)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc3d)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812d3d18)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
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
In kernel/events/uprobes.c (ffffffff8125135a)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b0984)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c76ed)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812df710)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff819f9469)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35cd0)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/events/uprobes.c (ffffffff81255454)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b5fb6)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce066)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812e8040)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff819dea58)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1ce23)
Location: include/asm-generic/atomic-instrumented.h:1148
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In net/core/net_namespace.c (ffffffff81a8e861)
Location: include/linux/atomic/atomic-instrumented.h:827
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad06a3)
Location: include/linux/atomic/atomic-instrumented.h:827
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In net/core/net_namespace.c (ffffffff81c04782)
Location: include/linux/atomic/atomic-instrumented.h:881
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4df32)
Location: include/linux/atomic/atomic-instrumented.h:881
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In net/core/net_namespace.c (ffffffff81db4252)
Location: include/linux/atomic/atomic-instrumented.h:881
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d73)
Location: include/linux/atomic/atomic-instrumented.h:881
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
In drivers/xen/grant-table.c (ffffffff81a62c34)
Location: include/linux/atomic/atomic-instrumented.h:2171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/net_namespace.c (ffffffff81e24902)
Location: include/linux/atomic/atomic-instrumented.h:2171
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e752f3)
Location: include/linux/atomic/atomic-instrumented.h:2171
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
In drivers/xen/grant-table.c (ffffffff81ab5264)
Location: include/linux/atomic/atomic-instrumented.h:2171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/net_namespace.c (ffffffff81ee2552)
Location: include/linux/atomic/atomic-instrumented.h:2171
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34b93)
Location: include/linux/atomic/atomic-instrumented.h:2171
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
In kernel/acct.c (ffff8000101c7f34)
Location: include/linux/atomic-fallback.h:1563
Inline: True
```
```
In kernel/audit_tree.c (ffff8000101f550c)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (ffff80001029c468)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (ffff80001038571c)
Location: include/linux/atomic-fallback.h:1563
Inline: True
```
```
In fs/notify/mark.c (ffff8000103e93bc)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffff8000105e8858)
Location: include/linux/atomic-fallback.h:1563
Inline: True
```
```
In net/unix/scm.c (ffff800010cf548c)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (c0000000002301a4)
Location: include/linux/atomic-fallback.h:1622
Inline: True
```
```
In kernel/audit_tree.c (c00000000026ab04)
Location: include/linux/atomic-fallback.h:1622
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (c00000000034c8fc)
Location: include/linux/atomic-fallback.h:1622
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (c00000000047bb54)
Location: include/linux/atomic-fallback.h:1622
Inline: True
```
```
In fs/notify/mark.c (c0000000004f0214)
Location: include/linux/atomic-fallback.h:1622
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (c00000000077d4b4)
Location: include/linux/atomic-fallback.h:1622
Inline: True
```
```
In net/unix/scm.c (c000000000e1b618)
Location: include/linux/atomic-fallback.h:1622
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In kernel/acct.c (ffffffe0001481d4)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/audit_tree.c (ffffffe0001679b0)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - kernel/audit_tree.c:__put_chunk
```
```
In kernel/events/core.c (ffffffe0001d04c4)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In fs/file_table.c (ffffffe00025861e)
Location: include/linux/atomic-fallback.h:1563
Inline: True
```
```
In fs/notify/mark.c (ffffffe00029dd4e)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (ffffffe0004293ae)
Location: include/linux/atomic-fallback.h:1563
Inline: True
```
```
In net/unix/scm.c (ffffffe000840f6a)
Location: include/linux/atomic-fallback.h:1563
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
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
