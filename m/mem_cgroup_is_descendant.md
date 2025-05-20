# Function: <code>mem_cgroup_is_descendant</code>

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
In mm/rmap.c (ffffffff811ca4a3)
Location: include/linux/memcontrol.h:323
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff811fad6c)
Location: include/linux/memcontrol.h:323
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff811e6973)
Location: include/linux/memcontrol.h:393
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8121fbac)
Location: include/linux/memcontrol.h:393
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff811f7d13)
Location: include/linux/memcontrol.h:395
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8123222b)
Location: include/linux/memcontrol.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff81202efa)
Location: include/linux/memcontrol.h:389
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8123d4e2)
Location: include/linux/memcontrol.h:389
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff8121bc3a)
Location: include/linux/memcontrol.h:389
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8125d0b9)
Location: include/linux/memcontrol.h:389
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff8123da8b)
Location: include/linux/memcontrol.h:422
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8128195a)
Location: include/linux/memcontrol.h:422
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff81252058)
Location: include/linux/memcontrol.h:457
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff81298936)
Location: include/linux/memcontrol.h:457
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
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
In mm/rmap.c (ffffffff81264393)
Location: include/linux/memcontrol.h:463
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812b3e14)
Location: include/linux/memcontrol.h:463
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff81272c03)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812c5735)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff812a39e3)
Location: include/linux/memcontrol.h:474
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812fc44a)
Location: include/linux/memcontrol.h:474
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
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
In mm/rmap.c (ffffffff812af2b5)
Location: include/linux/memcontrol.h:794
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8130865c)
Location: include/linux/memcontrol.h:794
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
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
In mm/rmap.c (ffffffff812b4795)
Location: include/linux/memcontrol.h:873
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8130d846)
Location: include/linux/memcontrol.h:873
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff812f6375)
Location: include/linux/memcontrol.h:869
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813585af)
Location: include/linux/memcontrol.h:869
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff8135b00b)
Location: include/linux/memcontrol.h:868
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813d2554)
Location: include/linux/memcontrol.h:868
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff813d5c2b)
Location: include/linux/memcontrol.h:859
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff81457c1b)
Location: include/linux/memcontrol.h:859
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff8140ab10)
Location: include/linux/memcontrol.h:877
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8148d94b)
Location: include/linux/memcontrol.h:877
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff81437370)
Location: include/linux/memcontrol.h:896
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff814bd2cb)
Location: include/linux/memcontrol.h:896
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffff80001030873c)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffff800010368554)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (c05256e0)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (c0559a14)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (c0000000003d770c)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (c00000000045628c)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffe000212f7e)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffe000246262)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff8126b253)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812bdd15)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff8125d333)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812aee4d)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff81268ff3)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812bbb25)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
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
In mm/rmap.c (ffffffff8127898b)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812cc2b3)
Location: include/linux/memcontrol.h:497
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
</details>
</li>
</ul>

## Differences
