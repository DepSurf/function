# Function: <code>rwsem_optimistic_spin</code>

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
In kernel/locking/rwsem-xadd.c (ffffffff81822e77)
Location: kernel/locking/rwsem-xadd.c:365
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff8189d8fa)
Location: kernel/locking/rwsem-xadd.c:390
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
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
In kernel/locking/rwsem-xadd.c (ffffffff818d27ca)
Location: kernel/locking/rwsem-xadd.c:390
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
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
In kernel/locking/rwsem-xadd.c (ffffffff81909691)
Location: kernel/locking/rwsem-xadd.c:391
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
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
In kernel/locking/rwsem-xadd.c (ffffffff81993681)
Location: kernel/locking/rwsem-xadd.c:419
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
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
In kernel/locking/rwsem-xadd.c (ffffffff819efc4a)
Location: kernel/locking/rwsem-xadd.c:419
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
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
In kernel/locking/rwsem-xadd.c (ffffffff81a2b67a)
Location: kernel/locking/rwsem-xadd.c:437
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f8020)
Location: kernel/locking/rwsem.c:783
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810f8020-ffffffff810f8212: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103e50)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff81103e50-ffffffff81104042: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e9c0)
Location: kernel/locking/rwsem.c:785
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8110e9c0-ffffffff8110eb91: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110bb50)
Location: kernel/locking/rwsem.c:736
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8110bb50-ffffffff8110bcb2: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110da30)
Location: kernel/locking/rwsem.c:736
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8110da30-ffffffff8110db92: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112d2e0)
Location: kernel/locking/rwsem.c:783
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8112d2e0-ffffffff8112d442: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e680)
Location: kernel/locking/rwsem.c:817
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8114e680-ffffffff8114e814: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d6e0)
Location: kernel/locking/rwsem.c:824
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8117d6e0-ffffffff8117d874: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118e390)
Location: kernel/locking/rwsem.c:819
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8118e390-ffffffff8118e513: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119cd40)
Location: kernel/locking/rwsem.c:819
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
**Symbols:**

```
ffffffff8119cd40-ffffffff8119cec3: rwsem_optimistic_spin (STB_LOCAL)
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
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010169048)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffff800010169048-ffff8000101692b0: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b58b0)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
c03b58b0-c03b5b7c: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c12f0)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
c0000000001c12f0-c0000000001c161c: rwsem_optimistic_spin (STB_LOCAL)
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
Location: kernel/locking/rwsem.c:970
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
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fd160)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810fd160-ffffffff810fd352: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed370)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810ed370-ffffffff810ed562: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa320)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810fa320-ffffffff810fa512: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore *sem, bool wlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811054a0)
Location: kernel/locking/rwsem.c:788
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff811054a0-ffffffff811056b0: rwsem_optimistic_spin (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>bool wlock</code>
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
