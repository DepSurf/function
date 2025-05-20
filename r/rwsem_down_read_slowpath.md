# Function: <code>rwsem_down_read_slowpath</code>

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
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a9af80)
Location: kernel/locking/rwsem.c:983
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81a9af80-ffffffff81a9b417: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81ad28d0)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81ad28d0-ffffffff81ad2d67: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81bca9f0)
Location: kernel/locking/rwsem.c:992
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81bca9f0-ffffffff81bcae32: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c438b0)
Location: kernel/locking/rwsem.c:892
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81c438b0-ffffffff81c43c28: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c356e0)
Location: kernel/locking/rwsem.c:892
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81c356e0-ffffffff81c35a7d: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81d53f00)
Location: kernel/locking/rwsem.c:938
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81d53f00-ffffffff81d5427a: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81f24f80)
Location: kernel/locking/rwsem.c:997
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81f24f80-ffffffff81f25431: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff820d08a0)
Location: kernel/locking/rwsem.c:1004
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff820d08a0-ffffffff820d0d67: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff82154c30)
Location: kernel/locking/rwsem.c:996
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff82154c30-ffffffff821550fa: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, long int count, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff82237a70)
Location: kernel/locking/rwsem.c:996
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff82237a70-ffffffff82237f3a: rwsem_down_read_slowpath (STB_LOCAL)
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
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010da4dd0)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffff800010da4dd0-ffff800010da531c: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0e9cea0)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
c0e9cea0-c0e9d3ac: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c000000000ee7460)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
c000000000ee7460-c000000000ee7abc: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe0008c7bf0)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffe0008c7bf0-ffffffe0008c7e5c: rwsem_down_read_slowpath (STB_LOCAL)
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
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a71740)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81a71740-ffffffff81a71bd7: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a2db30)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81a2db30-ffffffff81a2dfa9: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81addb50)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81addb50-ffffffff81addfe7: rwsem_down_read_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_read_slowpath(struct rw_semaphore *sem, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81aea000)
Location: kernel/locking/rwsem.c:995
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81aea000-ffffffff81aea4c2: rwsem_down_read_slowpath (STB_LOCAL)
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
<b>Param added. </b>
<code>long int count</code>
</li>
<li>
<b>Param reordered. </b>
<code>sem, state</code> ➡️ <code>sem, count, state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int state</code> ➡️ <code>unsigned int state</code>
</li>
</ul>
</details>
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
