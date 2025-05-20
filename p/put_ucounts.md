# Function: <code>put_ucounts</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad5f0)
Location: kernel/ucount.c:161
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810ad5f0-ffffffff810ad65b: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa1d0)
Location: kernel/ucount.c:166
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810aa1d0-ffffffff810aa234: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b0a30)
Location: kernel/ucount.c:166
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810b0a30-ffffffff810b0a94: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7840)
Location: kernel/ucount.c:167
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810b7840-ffffffff810b78a4: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0940)
Location: kernel/ucount.c:167
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810c0940-ffffffff810c09a4: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6a40)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810c6a40-ffffffff810c6aad: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfb10)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810cfb10-ffffffff810cfb7d: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9a10)
Location: kernel/ucount.c:163
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d9a10-ffffffff810d9a7f: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4bc0)
Location: kernel/ucount.c:163
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d4bc0-ffffffff810d4c2f: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6b80)
Location: kernel/ucount.c:200
Inline: False
Direct callers:
  - kernel/cred.c:set_cred_ucounts
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d6b80-ffffffff810d6bef: put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810e9e70)
Location: kernel/ucount.c:201
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:alloc_ucounts
  - mm/mlock.c:user_shm_unlock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff810e9e70-ffffffff810e9f43: put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104af0)
Location: kernel/ucount.c:207
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:alloc_ucounts
  - mm/mlock.c:user_shm_unlock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81104af0-ffffffff81104bd1: put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a3e0)
Location: kernel/ucount.c:203
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:alloc_ucounts
  - mm/mlock.c:user_shm_unlock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff8112a3e0-ffffffff8112a4c1: put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137430)
Location: kernel/ucount.c:203
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:alloc_ucounts
  - mm/mlock.c:user_shm_unlock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81137430-ffffffff81137511: put_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142610)
Location: kernel/ucount.c:204
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:alloc_ucounts
  - mm/mlock.c:user_shm_unlock
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
```
**Symbols:**

```
ffffffff81142610-ffffffff811426f1: put_ucounts (STB_GLOBAL)
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
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff800010130030)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffff800010130030-ffff800010130124: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037f898)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
c037f898-c037f918: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c000000000179430)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
c000000000179430-c000000000179514: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e3572)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffe0000e3572-ffffffe0000e35e0: put_ucounts (STB_LOCAL)
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
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9e90)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810c9e90-ffffffff810c9efd: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b86b0)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810b86b0-ffffffff810b871d: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c93c0)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810c93c0-ffffffff810c942d: put_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d1920)
Location: kernel/ucount.c:160
Inline: False
Direct callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d1920-ffffffff810d198d: put_ucounts (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
