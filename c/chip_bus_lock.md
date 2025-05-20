# Function: <code>chip_bus_lock</code>

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
In kernel/irq/irqdesc.c (ffffffff810da395)
Location: kernel/irq/internals.h:116
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810db41a)
Location: kernel/irq/internals.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
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
In kernel/irq/irqdesc.c (ffffffff810df895)
Location: kernel/irq/internals.h:120
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810e2732)
Location: kernel/irq/internals.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810e6172)
Location: kernel/irq/internals.h:120
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810e904f)
Location: kernel/irq/internals.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810e57c8)
Location: kernel/irq/internals.h:135
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810e6aa7)
Location: kernel/irq/internals.h:135
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810eda88)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810eecd7)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810f5ec8)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff810f70c7)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81101658)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81102837)
Location: kernel/irq/internals.h:138
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81109e56)
Location: kernel/irq/internals.h:145
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8110b047)
Location: kernel/irq/internals.h:145
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81116226)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811175a7)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81121ed6)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81122b47)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8111df56)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8111e977)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8111e1f6)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8111ee07)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8113e676)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8113f3d7)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81161c24)
Location: kernel/irq/internals.h:145
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81162e67)
Location: kernel/irq/internals.h:145
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811953f4)
Location: kernel/irq/internals.h:147
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81196a57)
Location: kernel/irq/internals.h:147
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811a6dc4)
Location: kernel/irq/internals.h:152
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811a8417)
Location: kernel/irq/internals.h:152
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811b68e4)
Location: kernel/irq/internals.h:152
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811b7e97)
Location: kernel/irq/internals.h:152
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffff800010177dc8)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffff80001017a3a8)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (c03c979c)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (c03cae24)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (c0000000001d1880)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (c0000000001d3a70)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffe000112a56)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffe000113d80)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8110e806)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8110fb87)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810ff556)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff811008c7)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8110c6f6)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff8110da77)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81117c06)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffffffff81119237)
Location: kernel/irq/internals.h:143
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
```
</details>
</li>
</ul>

## Differences
