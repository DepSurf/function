# Function: <code>percpu_rwsem_wait</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f1f0)
Location: kernel/locking/percpu-rwsem.c:139
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff8110f1f0-ffffffff8110f358: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110c3b0)
Location: kernel/locking/percpu-rwsem.c:139
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff8110c3b0-ffffffff8110c518: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110e1f0)
Location: kernel/locking/percpu-rwsem.c:139
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff8110e1f0-ffffffff8110e350: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8112d940)
Location: kernel/locking/percpu-rwsem.c:139
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff8112d940-ffffffff8112da8f: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8114eb00)
Location: kernel/locking/percpu-rwsem.c:141
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
**Symbols:**

```
ffffffff8114eb00-ffffffff8114ec1e: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117dcb0)
Location: kernel/locking/percpu-rwsem.c:141
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
**Symbols:**

```
ffffffff8117dcb0-ffffffff8117ddce: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e950)
Location: kernel/locking/percpu-rwsem.c:141
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
**Symbols:**

```
ffffffff8118e950-ffffffff8118ea6e: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore *sem, bool reader);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119d300)
Location: kernel/locking/percpu-rwsem.c:141
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
**Symbols:**

```
ffffffff8119d300-ffffffff8119d41e: percpu_rwsem_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
