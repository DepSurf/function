# Function: <code>__skb_array_destroy_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8165068c)
Location: include/linux/skb_array.h:154
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff8164cd30-ffffffff8164cd40: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8168236b)
Location: include/linux/skb_array.h:154
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff8167ea70-ffffffff8167ea80: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816976b8)
Location: include/linux/skb_array.h:179
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff81693c50-ffffffff81693c60: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81702585)
Location: include/linux/skb_array.h:179
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
**Symbols:**

```
ffffffff816fda80-ffffffff816fda90: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173b94f)
Location: include/linux/skb_array.h:189
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff818cc58f)
Location: include/linux/skb_array.h:189
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff818cbb40-ffffffff818cbb50: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8175f0af)
Location: include/linux/skb_array.h:189
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff818f77c2)
Location: include/linux/skb_array.h:189
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff818f6e40-ffffffff818f6e50: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179c76f)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff81956daa)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81956570-ffffffff81956580: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c021f)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff8198d24a)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8198ca10-ffffffff8198ca20: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188efdb)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81a644a0)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81a644a0-ffffffff81a644b0: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189cf00)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81a6c5e0)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81a6c5e0-ffffffff81a6c5f0: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187f580)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81a54d70)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81a54d70-ffffffff81a54d80: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff819113df)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81b0d9f0)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81b0d9f0-ffffffff81b0da00: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a64288)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81c94ad0)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81c94ad0-ffffffff81c94aed: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bef4d8)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81e50520)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81e50520-ffffffff81e5053d: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c475b8)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81eabcc0)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81eabcc0-ffffffff81eabcdd: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfceb8)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/sched/sch_generic.c (ffffffff81f6e760)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffffffff81f6e760-ffffffff81f6e77d: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109da9c4)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffff800010c37740)
Location: include/linux/skb_array.h:185
Inline: True
```
**Symbols:**

```
ffff800010c37740-ffff800010c3776c: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac141c)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (c0d4adf4)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
c0d4a220-c0d4a23c: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9c97c)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (c000000000d306c0)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
c000000000d2fe00-c000000000d2fe34: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe0006257aa)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffe0007a9bf8)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffe0007a934a-ffffffe0007a9374: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81784cef)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff8192d0ba)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8192c880-ffffffff8192c890: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176463f)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff818e6bba)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff818e6380-ffffffff818e6390: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b509f)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff8197e24a)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8197da10-ffffffff8197da20: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __skb_array_destroy_skb(void *ptr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cf06f)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ptr_free
```
```
In net/sched/sch_generic.c (ffffffff819a0a4b)
Location: include/linux/skb_array.h:185
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8199ff80-ffffffff8199ff90: __skb_array_destroy_skb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
