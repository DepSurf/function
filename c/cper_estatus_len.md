# Function: <code>cper_estatus_len</code>

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
In drivers/acpi/apei/ghes.c (ffffffff814b5783)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
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
In drivers/acpi/apei/bert.c (ffffffff81fcfb43)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815060e6)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
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
In drivers/acpi/apei/bert.c (ffffffff8200d1fa)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a326)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
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
In drivers/acpi/apei/bert.c (ffffffff820eebc4)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153d51a)
Location: drivers/acpi/apei/apei-internal.h:128
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
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
In drivers/acpi/apei/bert.c (ffffffff826f83e0)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815a00fa)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
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
In drivers/acpi/apei/bert.c (ffffffff827227a3)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d729e)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
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
In drivers/acpi/apei/bert.c (ffffffff828da8df)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f1509)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
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
In drivers/acpi/apei/bert.c (ffffffff828f51c7)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff816232ef)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
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
In drivers/acpi/apei/bert.c (ffffffff828fe21e)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644dbf)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
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
In drivers/acpi/apei/bert.c (ffffffff82d15057)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_print_all
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1fd4)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff83002ceb)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_print_all
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f394)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff8320dea1)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0c74)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff832f66f7)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ad84)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff834aebd4)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f934)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff83ee8037)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8d01)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff8370da07)
Location: drivers/acpi/apei/apei-internal.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30ce1)
Location: drivers/acpi/apei/apei-internal.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffffffff839410e7)
Location: drivers/acpi/apei/apei-internal.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c155)
Location: drivers/acpi/apei/apei-internal.h:123
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
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
In drivers/acpi/apei/bert.c (ffff800011481010)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afc24)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
</details>
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/bert.c (ffffffff828de38f)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (ffffffff828f9541)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638bff)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
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
In drivers/acpi/apei/bert.c (ffffffff828ff272)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652f4f)
Location: drivers/acpi/apei/apei-internal.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
</details>
</li>
</ul>

## Differences
