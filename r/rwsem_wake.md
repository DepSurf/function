# Function: <code>rwsem_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810cbbb0)
Location: kernel/locking/rwsem-xadd.c:509
Inline: False
```
**Symbols:**

```
ffffffff810cbbb0-ffffffff810cbc47: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d0660)
Location: kernel/locking/rwsem-xadd.c:579
Inline: False
```
**Symbols:**

```
ffffffff810d0660-ffffffff810d072d: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d7150)
Location: kernel/locking/rwsem-xadd.c:579
Inline: False
```
**Symbols:**

```
ffffffff810d7150-ffffffff810d7221: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d6190)
Location: kernel/locking/rwsem-xadd.c:583
Inline: False
```
**Symbols:**

```
ffffffff810d6190-ffffffff810d626a: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810de150)
Location: kernel/locking/rwsem-xadd.c:611
Inline: False
```
**Symbols:**

```
ffffffff810de150-ffffffff810de22a: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810e67b0)
Location: kernel/locking/rwsem-xadd.c:611
Inline: False
```
**Symbols:**

```
ffffffff810e67b0-ffffffff810e687b: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_wake(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810f1d10)
Location: kernel/locking/rwsem-xadd.c:629
Inline: False
```
**Symbols:**

```
ffffffff810f1d10-ffffffff810f1ddd: rwsem_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7e40)
Location: kernel/locking/rwsem.c:1277
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810f7e40-ffffffff810f7eda: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103c70)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff81103c70-ffffffff81103d0a: rwsem_wake.isra.0 (STB_LOCAL)
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
In kernel/locking/rwsem.c (ffffffff8110ec00)
Location: kernel/locking/rwsem.c:1298
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8110be10)
Location: kernel/locking/rwsem.c:1168
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8110dc30)
Location: kernel/locking/rwsem.c:1168
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112d100)
Location: kernel/locking/rwsem.c:1175
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff8112d100-ffffffff8112d197: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e410)
Location: kernel/locking/rwsem.c:1207
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff8114e410-ffffffff8114e4af: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d3b0)
Location: kernel/locking/rwsem.c:1214
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff8117d3b0-ffffffff8117d44f: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118e090)
Location: kernel/locking/rwsem.c:1203
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff8118e090-ffffffff8118e12f: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119ca40)
Location: kernel/locking/rwsem.c:1203
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff8119ca40-ffffffff8119cadf: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010169518)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffff800010169518-ffff800010169618: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (c03b56c4)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
c03b56c4-c03b5770: rwsem_wake.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c0fc0)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
c0000000001c0fc0-c0000000001c109c: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010aaf4)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffe00010aaf4-ffffffe00010ab6e: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fcf80)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810fcf80-ffffffff810fd01a: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed190)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810ed190-ffffffff810ed22a: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa140)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810fa140-ffffffff810fa1da: rwsem_wake.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811052b0)
Location: kernel/locking/rwsem.c:1301
Inline: True
Direct callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff811052b0-ffffffff8110534a: rwsem_wake.isra.0 (STB_LOCAL)
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
