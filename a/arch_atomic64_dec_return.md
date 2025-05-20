# Function: <code>arch_atomic64_dec_return</code>

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
Location: include/linux/atomic-arch-fallback.h:1562
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812a54f6)
Location: include/linux/atomic-arch-fallback.h:1562
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc3d)
Location: include/linux/atomic-arch-fallback.h:1562
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812d3d18)
Location: include/linux/atomic-arch-fallback.h:1562
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
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b0984)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c76ed)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812df710)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff819f9469)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35cd0)
Location: include/linux/atomic-arch-fallback.h:1632
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
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b5fb6)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce066)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812e8040)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff819dea58)
Location: include/linux/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1ce23)
Location: include/linux/atomic-arch-fallback.h:1632
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
In kernel/events/uprobes.c (ffffffff81290e93)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f885d)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813134e6)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8132ff52)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff81a8e861)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad06a3)
Location: include/linux/atomic/atomic-arch-fallback.h:1632
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
In kernel/events/uprobes.c (ffffffff812e634c)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135eddb)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e8a8)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff813a0347)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In net/core/net_namespace.c (ffffffff81c04782)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4df32)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
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
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d73)
Location: include/linux/atomic/atomic-arch-fallback.h:1730
Inline: True
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
