# Function: <code>rwsem_mark_wake</code>

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
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7b50)
Location: kernel/locking/rwsem.c:397
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810f7b50-ffffffff810f7d65: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103980)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff81103980-ffffffff81103b95: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e4d0)
Location: kernel/locking/rwsem.c:400
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8110e4d0-ffffffff8110e723: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110b760)
Location: kernel/locking/rwsem.c:380
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8110b760-ffffffff8110b9a4: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d580)
Location: kernel/locking/rwsem.c:380
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8110d580-ffffffff8110d7c2: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112cdd0)
Location: kernel/locking/rwsem.c:405
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8112cdd0-ffffffff8112d02e: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e090)
Location: kernel/locking/rwsem.c:406
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8114e090-ffffffff8114e33e: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d010)
Location: kernel/locking/rwsem.c:414
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8117d010-ffffffff8117d2be: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118dcc0)
Location: kernel/locking/rwsem.c:411
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8118dcc0-ffffffff8118df6e: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119c670)
Location: kernel/locking/rwsem.c:411
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff8119c670-ffffffff8119c91e: rwsem_mark_wake (STB_LOCAL)
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
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff8000101692b0)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffff8000101692b0-ffff800010169514: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b5358)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
c03b5358-c03b55d0: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c0b70)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
c0000000001c0b70-c0000000001c0e78: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010a8b2)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffe00010a8b2-ffffffe00010aa4e: rwsem_mark_wake (STB_LOCAL)
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
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fcc90)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810fcc90-ffffffff810fcea5: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ecea0)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810ecea0-ffffffff810ed0b5: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f9e50)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff810f9e50-ffffffff810fa065: rwsem_mark_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore *sem, enum rwsem_wake_type wake_type, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81104fc0)
Location: kernel/locking/rwsem.c:401
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff81104fc0-ffffffff811051d5: rwsem_mark_wake (STB_LOCAL)
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
