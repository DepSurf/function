# Function: <code>rwsem_down_write_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f8220)
Location: kernel/locking/rwsem.c:1127
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff810f8220-ffffffff810f86d7: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81104050)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff81104050-ffffffff8110451f: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110ec60)
Location: kernel/locking/rwsem.c:1136
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff8110ec60-ffffffff8110f0f1: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110be70)
Location: kernel/locking/rwsem.c:1016
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff8110be70-ffffffff8110c2b8: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110dc90)
Location: kernel/locking/rwsem.c:1016
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff8110dc90-ffffffff8110e0fd: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:1058
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff8112d480-ffffffff8112d844: rwsem_down_write_slowpath (STB_LOCAL)
ffffffff81ca95a8-ffffffff81ca95c5: rwsem_down_write_slowpath.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81f25620)
Location: kernel/locking/rwsem.c:1108
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff81f25620-ffffffff81f25bcf: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff820d1010)
Location: kernel/locking/rwsem.c:1115
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff820d1010-ffffffff820d15a0: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff821553d0)
Location: kernel/locking/rwsem.c:1107
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff821553d0-ffffffff8215591f: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff82238210)
Location: kernel/locking/rwsem.c:1107
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff82238210-ffffffff8223875f: rwsem_down_write_slowpath (STB_LOCAL)
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
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010169878)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffff800010169878-ffff800010169e24: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b5b7c)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
c03b5b7c-c03b6060: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c1620)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
c0000000001c1620-c0000000001c1cdc: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010ac02)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffe00010ac02-ffffffe00010afea: rwsem_down_write_slowpath (STB_LOCAL)
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
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fd360)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff810fd360-ffffffff810fd82f: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed570)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff810ed570-ffffffff810eda23: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa520)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff810fa520-ffffffff810fa9ef: rwsem_down_write_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811056b0)
Location: kernel/locking/rwsem.c:1139
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
```
**Symbols:**

```
ffffffff811056b0-ffffffff81105bb3: rwsem_down_write_slowpath (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
