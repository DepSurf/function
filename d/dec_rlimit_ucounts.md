# Function: <code>dec_rlimit_ucounts</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dec_rlimit_ucounts(struct ucounts *ucounts, enum ucount_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea360)
Location: kernel/ucount.c:277
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/cred.c:commit_creds
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff810ea360-ffffffff810ea3c0: dec_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dec_rlimit_ucounts(struct ucounts *ucounts, enum ucount_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81105000)
Location: kernel/ucount.c:283
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/cred.c:commit_creds
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81105000-ffffffff81105084: dec_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dec_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112aa30)
Location: kernel/ucount.c:279
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/cred.c:commit_creds
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff8112aa30-ffffffff8112aab4: dec_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dec_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137b40)
Location: kernel/ucount.c:279
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/cred.c:commit_creds
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81137b40-ffffffff81137bf1: dec_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dec_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142d50)
Location: kernel/ucount.c:280
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/cred.c:commit_creds
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81142d50-ffffffff81142e01: dec_rlimit_ucounts (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum ucount_type type</code> ➡️ <code>enum rlimit_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
