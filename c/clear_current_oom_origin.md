# Function: <code>clear_current_oom_origin</code>

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
In mm/swapfile.c (ffffffff811d5dc6)
Location: include/linux/oom.h:63
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/ksm.c (ffffffff811e526d)
Location: include/linux/oom.h:63
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In mm/swapfile.c (ffffffff811f3e86)
Location: include/linux/oom.h:63
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/ksm.c (ffffffff81203dd8)
Location: include/linux/oom.h:63
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In mm/swapfile.c (ffffffff812049b6)
Location: include/linux/oom.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/ksm.c (ffffffff81215df8)
Location: include/linux/oom.h:51
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In mm/swapfile.c (ffffffff81210066)
Location: include/linux/oom.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/ksm.c (ffffffff8122150b)
Location: include/linux/oom.h:53
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In mm/swapfile.c (ffffffff8122b80a)
Location: include/linux/oom.h:54
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
```
```
In mm/ksm.c (ffffffff8123c81b)
Location: include/linux/oom.h:54
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8117a208)
Location: include/linux/oom.h:54
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff8124ca74)
Location: include/linux/oom.h:54
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8125fdac)
Location: include/linux/oom.h:54
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811871d8)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81260f98)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812744ec)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811945bf)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff8127beea)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8129065a)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811a007f)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff8128b9ca)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812a03da)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811b56af)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff812be8ba)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812d4ba9)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811b2f8d)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff812ca49a)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812e062a)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811b381d)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff812d0fce)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812e769a)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811dd5ed)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff813166c0)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8132f5ca)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8121436b)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81381867)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8139f86d)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8125de7b)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff813ffff1)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8141fc1d)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff812750eb)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81432ea0)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff814546cb)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8128fa12)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff8146c2c0)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8148ef7b)
Location: include/linux/oom.h:65
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffff8000102178c8)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffff800010326db0)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffff80001033fbf0)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (c045731c)
Location: include/linux/oom.h:64
Inline: True
```
```
In mm/swapfile.c (c053e504)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (c0545f08)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (c00000000029b830)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (c0000000003fd964)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (c00000000041c4dc)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffe000177b98)
Location: include/linux/oom.h:64
Inline: True
```
```
In mm/swapfile.c (ffffffe000226e52)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffe000234474)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8119869f)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81283faa)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812989ba)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8118bbaf)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81275e3a)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff8128a57a)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff8119646f)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81281dba)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812967ca)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
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
In kernel/trace/ring_buffer.c (ffffffff811a407f)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In mm/swapfile.c (ffffffff81291ac2)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/ksm.c (ffffffff812a65b2)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/ksm.c:run_store
```
</details>
</li>
</ul>

## Differences
