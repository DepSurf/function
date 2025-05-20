# Function: <code>osq_lock_init</code>

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
In kernel/locking/mutex.c (ffffffff810c9a6a)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cba5b)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810ce3da)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d04eb)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810d5043)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d6eeb)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810d4183)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d5f4b)
Location: include/linux/osq_lock.h:27
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810dc0d3)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810ddf0b)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810e4714)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810e657c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810efc94)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1afc)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810f76f4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7abc)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff81103494)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff811038ec)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8110e024)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110e43c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8110b2e4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110b6fc)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8110d174)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110d51c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8112c8e4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8112cd6c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8114d4b4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8114e00c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8117c594)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8117cf5c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8118d274)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dc0c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff8119bc24)
Location: include/linux/osq_lock.h:23
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c5bc)
Location: include/linux/osq_lock.h:23
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffff8000101685e8)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffff800010168e7c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (c03b4ce8)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (c03b5250)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (c0000000001c0370)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (c0000000001c0b18)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/locking/mutex.c (ffffffff810fc7a4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fcbfc)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810ec9b4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810ece0c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff810f9964)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f9dbc)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
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
In kernel/locking/mutex.c (ffffffff81104ac4)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81104f2c)
Location: include/linux/osq_lock.h:28
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
</details>
</li>
</ul>

## Differences
