# Function: <code>inc_rlimit_ucounts</code>

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
long int inc_rlimit_ucounts(struct ucounts *ucounts, enum ucount_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea2e0)
Location: kernel/ucount.c:260
Inline: False
Direct callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/ucount.c:user_namespace_sysctl_init
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff810ea2e0-ffffffff810ea353: inc_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int inc_rlimit_ucounts(struct ucounts *ucounts, enum ucount_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104f70)
Location: kernel/ucount.c:266
Inline: False
Direct callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/ucount.c:user_namespace_sysctl_init
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81104f70-ffffffff81104ff8: inc_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int inc_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a990)
Location: kernel/ucount.c:262
Inline: False
Direct callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/ucount.c:user_namespace_sysctl_init
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff8112a990-ffffffff8112aa18: inc_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int inc_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137a10)
Location: kernel/ucount.c:262
Inline: False
Direct callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/ucount.c:user_namespace_sysctl_init
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81137a10-ffffffff81137b24: inc_rlimit_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int inc_rlimit_ucounts(struct ucounts *ucounts, enum rlimit_type type, long int v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142c20)
Location: kernel/ucount.c:263
Inline: False
Direct callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/ucount.c:user_namespace_sysctl_init
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81142c20-ffffffff81142d34: inc_rlimit_ucounts (STB_GLOBAL)
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
