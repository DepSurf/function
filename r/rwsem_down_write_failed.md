# Function: <code>rwsem_down_write_failed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff81822e40)
Location: kernel/locking/rwsem-xadd.c:437
Inline: True
```
**Symbols:**

```
ffffffff81822e40-ffffffff8182318d: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff8189d4f0)
Location: kernel/locking/rwsem-xadd.c:561
Inline: False
```
**Symbols:**

```
ffffffff8189d4f0-ffffffff8189d8af: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff818d23e0)
Location: kernel/locking/rwsem-xadd.c:561
Inline: False
```
**Symbols:**

```
ffffffff818d23e0-ffffffff818d2772: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff81909a70)
Location: kernel/locking/rwsem-xadd.c:565
Inline: False
```
**Symbols:**

```
ffffffff81909a70-ffffffff81909de2: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff81993dd0)
Location: kernel/locking/rwsem-xadd.c:593
Inline: False
```
**Symbols:**

```
ffffffff81993dd0-ffffffff81994123: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff819f0370)
Location: kernel/locking/rwsem-xadd.c:593
Inline: False
```
**Symbols:**

```
ffffffff819f0370-ffffffff819f06ae: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rw_semaphore *rwsem_down_write_failed(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff81a2af50)
Location: kernel/locking/rwsem-xadd.c:611
Inline: False
```
**Symbols:**

```
ffffffff81a2af50-ffffffff81a2b28e: rwsem_down_write_failed (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
