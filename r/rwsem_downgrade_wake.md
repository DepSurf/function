# Function: <code>rwsem_downgrade_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810cbc50)
Location: kernel/locking/rwsem-xadd.c:562
Inline: False
```
**Symbols:**

```
ffffffff810cbc50-ffffffff810cbca3: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d0730)
Location: kernel/locking/rwsem-xadd.c:634
Inline: False
```
**Symbols:**

```
ffffffff810d0730-ffffffff810d07d0: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d7070)
Location: kernel/locking/rwsem-xadd.c:633
Inline: False
```
**Symbols:**

```
ffffffff810d7070-ffffffff810d7115: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d60b0)
Location: kernel/locking/rwsem-xadd.c:637
Inline: False
```
**Symbols:**

```
ffffffff810d60b0-ffffffff810d6157: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810de070)
Location: kernel/locking/rwsem-xadd.c:692
Inline: False
```
**Symbols:**

```
ffffffff810de070-ffffffff810de117: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810e66d0)
Location: kernel/locking/rwsem-xadd.c:692
Inline: False
```
**Symbols:**

```
ffffffff810e66d0-ffffffff810e6774: rwsem_downgrade_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_downgrade_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810f1de0)
Location: kernel/locking/rwsem-xadd.c:710
Inline: False
```
**Symbols:**

```
ffffffff810f1de0-ffffffff810f1e79: rwsem_downgrade_wake (STB_GLOBAL)
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
In kernel/locking/rwsem.c (ffffffff810f7de2)
Location: kernel/locking/rwsem.c:1298
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff81103c12)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8110e7a2)
Location: kernel/locking/rwsem.c:1319
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8110ba22)
Location: kernel/locking/rwsem.c:1189
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d842)
Location: kernel/locking/rwsem.c:1189
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8112d0a2)
Location: kernel/locking/rwsem.c:1196
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8114e3be)
Location: kernel/locking/rwsem.c:1228
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8117d34e)
Location: kernel/locking/rwsem.c:1235
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8118e012)
Location: kernel/locking/rwsem.c:1224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff8119c9c2)
Location: kernel/locking/rwsem.c:1224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffff8000101696d4)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (c03b5668)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (c0000000001c0f20)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffe00010aa98)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff810fcf22)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff810ed132)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff810fa0e2)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
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
In kernel/locking/rwsem.c (ffffffff81105252)
Location: kernel/locking/rwsem.c:1322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
