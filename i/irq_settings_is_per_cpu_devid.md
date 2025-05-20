# Function: <code>irq_settings_is_per_cpu_devid</code>

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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:48
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: kernel/irq/settings.h:48
Inline: True
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:48
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: kernel/irq/settings.h:48
Inline: True
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:48
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: kernel/irq/settings.h:48
Inline: True
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:48
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: kernel/irq/settings.h:48
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: kernel/irq/settings.h:49
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810f8cad)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110444d)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110cf3c)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111931c)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff811220b9)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81124bbc)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff8111d609)
Location: kernel/irq/settings.h:51
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81120a1c)
Location: kernel/irq/settings.h:51
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff8111e3da)
Location: kernel/irq/settings.h:51
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81120cec)
Location: kernel/irq/settings.h:51
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff8113e86e)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8114126c)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff81161e47)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81164c7d)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff8119567a)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81198a9d)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff811a704a)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811aa77d)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffff811b6baa)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811ba2cd)
Location: kernel/irq/settings.h:53
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffff80001017be48)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (c03c9aa8)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
```
```
In kernel/irq/manage.c (c03cced4)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (c0000000001d1d1c)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
```
```
In kernel/irq/manage.c (c0000000001d6908)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (ffffffe000112d6a)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_irqs
```
```
In kernel/irq/manage.c (ffffffe0001156e4)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811118fc)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110262c)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110f7ec)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
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
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/settings.h:49
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111ad1c)
Location: kernel/irq/settings.h:49
Inline: True
Inline callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_nmi
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:remove_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:irq_wake_thread
```
</details>
</li>
</ul>

## Differences
