# Function: <code>to_kthread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a006f)
Location: kernel/kthread.c:59
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:probe_kthread_data
  - kernel/kthread.c:kthread_create_on_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a4174)
Location: kernel/kthread.c:59
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:probe_kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a954c)
Location: kernel/kthread.c:66
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6238)
Location: kernel/kthread.c:69
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810abda8)
Location: kernel/kthread.c:71
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3ae8)
Location: kernel/kthread.c:70
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810bc7f8)
Location: kernel/kthread.c:70
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810c270b)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810c7e1a)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810d10fc)
Location: kernel/kthread.c:80
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810cb6a7)
Location: kernel/kthread.c:81
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_is_per_cpu
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct kthread *to_kthread(struct task_struct *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd40b)
Location: kernel/kthread.c:71
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
Direct callers:
  - kernel/kthread.c:kthread
```
**Symbols:**

```
ffffffff810cc3f0-ffffffff810cc402: to_kthread (STB_LOCAL)
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
In kernel/kthread.c (ffffffff810df6ca)
Location: kernel/kthread.c:71
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810fb4ea)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_exit
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:get_kthread_comm
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
In kernel/kthread.c (ffffffff8111e42a)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_exit
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:get_kthread_comm
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
In kernel/kthread.c (ffffffff8112b69a)
Location: kernel/kthread.c:74
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_exit
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:get_kthread_comm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135dea)
Location: kernel/kthread.c:74
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_exit
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:get_kthread_comm
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
In kernel/kthread.c (ffff8000101271bc)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (c0379a38)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:__kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (c000000000172d14)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000de9fa)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
  - kernel/kthread.c:free_kthread_struct
```
</details>
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
In kernel/kthread.c (ffffffff810c219a)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810b09ea)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810c16ea)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
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
In kernel/kthread.c (ffffffff810c9b1a)
Location: kernel/kthread.c:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:kthread_probe_data
  - kernel/kthread.c:kthread_data
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:free_kthread_struct
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
