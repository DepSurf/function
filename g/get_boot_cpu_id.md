# Function: <code>get_boot_cpu_id</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/smp.h:125
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/smp.h:125
Inline: True
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
In kernel/module.c (0)
Location: include/linux/smp.h:130
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/smp.h:130
Inline: True
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
In kernel/module.c (ffffffff81130cce)
Location: include/linux/smp.h:130
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8121bf74)
Location: include/linux/smp.h:130
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff8113c57e)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8122ef54)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff81147be5)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8123ef42)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff81153a25)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8124d3a2)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff81165625)
Location: include/linux/smp.h:148
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8127b6e2)
Location: include/linux/smp.h:148
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
In kernel/module.c (ffffffff81161d95)
Location: include/linux/smp.h:150
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff81286212)
Location: include/linux/smp.h:150
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
In kernel/module.c (ffffffff81162826)
Location: include/linux/smp.h:180
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8128b4c8)
Location: include/linux/smp.h:180
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
In kernel/module.c (ffffffff81187d45)
Location: include/linux/smp.h:180
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff812cb1da)
Location: include/linux/smp.h:180
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
In kernel/module/main.c (ffffffff8118dd28)
Location: include/linux/smp.h:179
Inline: True
Inline callers:
  - kernel/module/main.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff81328bc3)
Location: include/linux/smp.h:179
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
In kernel/rcu/srcutree.c (ffffffff811ae903)
Location: include/linux/smp.h:179
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/module/main.c (ffffffff811ca8a5)
Location: include/linux/smp.h:179
Inline: True
Inline callers:
  - kernel/module/main.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff8139de60)
Location: include/linux/smp.h:179
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/rcu/srcutree.c (ffffffff811c08ef)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/module/main.c (ffffffff811ddaf5)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - kernel/module/main.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff813d0fc0)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/rcu/srcutree.c (ffffffff811d0dcf)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/module/main.c (ffffffff811f37f5)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - kernel/module/main.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff813fb9f0)
Location: include/linux/smp.h:186
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffff8000101c2d78)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffff8000102e3ccc)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (c0409fe4)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (c0507fc0)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (c00000000022952c)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (c0000000003a4320)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffe000143f84)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffe0001fa5d2)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff8114c045)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff812459f2)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff8113f2f5)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff812389a2)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff81149ef5)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff81243792)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
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
In kernel/module.c (ffffffff81156bbc)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - kernel/module.c:__is_module_percpu_address
```
```
In mm/percpu.c (ffffffff81252f52)
Location: include/linux/smp.h:134
Inline: True
Inline callers:
  - mm/percpu.c:__is_kernel_percpu_address
```
</details>
</li>
</ul>

## Differences
