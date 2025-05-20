# Function: <code>chip_bus_sync_unlock</code>

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
In kernel/irq/irqdesc.c (ffffffff810da3e3)
Location: kernel/irq/internals.h:122
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810db43a)
Location: kernel/irq/internals.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
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
In kernel/irq/irqdesc.c (ffffffff810df8e3)
Location: kernel/irq/internals.h:126
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810e2750)
Location: kernel/irq/internals.h:126
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
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
In kernel/irq/irqdesc.c (ffffffff810e61c3)
Location: kernel/irq/internals.h:126
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810e906d)
Location: kernel/irq/internals.h:126
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
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
In kernel/irq/irqdesc.c (ffffffff810e5813)
Location: kernel/irq/internals.h:141
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810e6ac7)
Location: kernel/irq/internals.h:141
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810edad3)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810eecf7)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810f5f13)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff810f70e7)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811016a3)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff81102857)
Location: kernel/irq/internals.h:144
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81109ea3)
Location: kernel/irq/internals.h:151
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8110b067)
Location: kernel/irq/internals.h:151
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81116273)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff811175c7)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81121f23)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff81122b67)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8111dfa3)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8111e997)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8111e243)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8111ee27)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8113e6c3)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8113f3f7)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81161c73)
Location: kernel/irq/internals.h:151
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff81162e87)
Location: kernel/irq/internals.h:151
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81195453)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff81196a77)
Location: kernel/irq/internals.h:153
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811a6e23)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff811a8437)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff811b6943)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff811b7eb7)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffff800010177eb4)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffff80001017a3c4)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (c03c9804)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (c03cae44)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (c0000000001d1900)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (c0000000001d3a94)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffe000112a9a)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffe000113d9a)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8110e853)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8110fba7)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff810ff5a3)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff811008e7)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff8110c743)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff8110da97)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
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
In kernel/irq/irqdesc.c (ffffffff81117c53)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_put_desc_unlock
```
```
In kernel/irq/manage.c (ffffffff81119257)
Location: kernel/irq/internals.h:149
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
</details>
</li>
</ul>

## Differences
