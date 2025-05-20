# Function: <code>rwsem_spin_on_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem, struct task_struct *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810cbcb0)
Location: kernel/locking/rwsem-xadd.c:329
Inline: False
```
**Symbols:**

```
ffffffff810cbcb0-ffffffff810cbd28: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d07d0)
Location: kernel/locking/rwsem-xadd.c:356
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d07d0-ffffffff810d0831: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d7230)
Location: kernel/locking/rwsem-xadd.c:352
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d7230-ffffffff810d72a8: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d6270)
Location: kernel/locking/rwsem-xadd.c:353
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d6270-ffffffff810d62e7: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810de230)
Location: kernel/locking/rwsem-xadd.c:381
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810de230-ffffffff810de298: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810e6880)
Location: kernel/locking/rwsem-xadd.c:382
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810e6880-ffffffff810e68f1: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810f1e80)
Location: kernel/locking/rwsem-xadd.c:400
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810f1e80-ffffffff810f1ef9: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7f50)
Location: kernel/locking/rwsem.c:714
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810f7f50-ffffffff810f801b: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103d80)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff81103d80-ffffffff81103e44: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e800)
Location: kernel/locking/rwsem.c:715
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110e800-ffffffff8110e8f9: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110ba80)
Location: kernel/locking/rwsem.c:666
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110ba80-ffffffff8110bb47: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d960)
Location: kernel/locking/rwsem.c:666
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110d960-ffffffff8110da21: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112d210)
Location: kernel/locking/rwsem.c:713
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8112d210-ffffffff8112d2d1: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e540)
Location: kernel/locking/rwsem.c:745
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8114e540-ffffffff8114e680: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d550)
Location: kernel/locking/rwsem.c:752
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8117d550-ffffffff8117d6c1: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118e230)
Location: kernel/locking/rwsem.c:747
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8118e230-ffffffff8118e380: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119cbe0)
Location: kernel/locking/rwsem.c:747
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8119cbe0-ffffffff8119cd30: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010168e88)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffff800010168e88-ffff800010168f48: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b5258)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c03b5258-c03b5358: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c1140)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c0000000001c1140-c0000000001c1264: rwsem_spin_on_owner (STB_LOCAL)
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
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:984
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fd090)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fd090-ffffffff810fd154: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed2a0)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810ed2a0-ffffffff810ed364: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa250)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fa250-ffffffff810fa314: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum owner_state rwsem_spin_on_owner(struct rw_semaphore *sem, long unsigned int nonspinnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811053c0)
Location: kernel/locking/rwsem.c:718
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff811053c0-ffffffff8110549a: rwsem_spin_on_owner (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *owner</code>
</li>
</ul>
</details>
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
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nonspinnable</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum owner_state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int nonspinnable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
