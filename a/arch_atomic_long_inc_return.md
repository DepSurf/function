# Function: <code>arch_atomic_long_inc_return</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290f63)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f7e74)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81313508)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81341145)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366e6c)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff81375115)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81bebb0b)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff812e635e)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135dc19)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e9de)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff813b7f58)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e4352)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff813f4405)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81d83feb)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In fs/super.c (ffffffff8147d4d5)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81f5186b)
Location: include/linux/atomic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
