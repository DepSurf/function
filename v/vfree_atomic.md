# Function: <code>vfree_atomic</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd420)
Location: mm/vmalloc.c:1520
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff811fd420-ffffffff811fd47a: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812080f0)
Location: mm/vmalloc.c:1572
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812080f0-ffffffff8120814a: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812211d0)
Location: mm/vmalloc.c:1570
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812211d0-ffffffff81221228: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81243080)
Location: mm/vmalloc.c:1557
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81243080-ffffffff812430d8: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257790)
Location: mm/vmalloc.c:1559
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81257790-ffffffff812577e8: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812686e0)
Location: mm/vmalloc.c:2285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812686e0-ffffffff81268739: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81277020)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff81277020-ffffffff81277079: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac220)
Location: mm/vmalloc.c:2338
Inline: False
Direct callers:
  - kernel/fork.c:free_thread_stack
```
**Symbols:**

```
ffffffff812ac220-ffffffff812ac27f: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b77b0)
Location: mm/vmalloc.c:2319
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812b77b0-ffffffff812b780f: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bd080)
Location: mm/vmalloc.c:2601
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812bd080-ffffffff812bd0df: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff7f0)
Location: mm/vmalloc.c:2654
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812ff7f0-ffffffff812ff84f: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366990)
Location: mm/vmalloc.c:2698
Inline: False
```
**Symbols:**

```
ffffffff81366990-ffffffff81366a13: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2620)
Location: mm/vmalloc.c:2760
Inline: False
```
**Symbols:**

```
ffffffff813e2620-ffffffff813e26a3: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416eb0)
Location: mm/vmalloc.c:2774
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
ffffffff81416eb0-ffffffff81416f26: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443c10)
Location: mm/vmalloc.c:2774
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:delayed_vfree_work
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
**Symbols:**

```
ffffffff81443c10-ffffffff81443c86: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030d570)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:free_thread_stack
```
**Symbols:**

```
ffff80001030d570-ffff80001030d5f4: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052909c)
Location: mm/vmalloc.c:2291
Inline: False
```
**Symbols:**

```
c052909c-c0529114: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003ddfb0)
Location: mm/vmalloc.c:2291
Inline: False
```
**Symbols:**

```
c0000000003ddfb0-c0000000003de060: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216310)
Location: mm/vmalloc.c:2291
Inline: False
```
**Symbols:**

```
ffffffe000216310-ffffffe000216396: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f670)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8126f670-ffffffff8126f6c9: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812615e0)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff812615e0-ffffffff81261639: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126d410)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8126d410-ffffffff8126d469: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfree_atomic(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127cda0)
Location: mm/vmalloc.c:2291
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff8127cda0-ffffffff8127cdf9: vfree_atomic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
