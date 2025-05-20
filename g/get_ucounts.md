# Function: <code>get_ucounts</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad7c6)
Location: kernel/ucount.c:126
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
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
In kernel/ucount.c (ffffffff810aa3a6)
Location: kernel/ucount.c:131
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
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
In kernel/ucount.c (ffffffff810b0c06)
Location: kernel/ucount.c:131
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
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
In kernel/ucount.c (ffffffff810b7a05)
Location: kernel/ucount.c:132
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
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
In kernel/ucount.c (ffffffff810c0b05)
Location: kernel/ucount.c:132
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6c05)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfcd5)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ucounts *get_ucounts(struct user_namespace *ns, kuid_t uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9ad0)
Location: kernel/ucount.c:128
Inline: False
Direct callers:
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d9ad0-ffffffff810d9c59: get_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ucounts *get_ucounts(struct user_namespace *ns, kuid_t uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4c80)
Location: kernel/ucount.c:128
Inline: False
Direct callers:
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffffffff810d4c80-ffffffff810d4e09: get_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6af0)
Location: kernel/ucount.c:181
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
**Symbols:**

```
ffffffff810d6af0-ffffffff810d6b76: get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea46d)
Location: kernel/ucount.c:153
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff810e9f50-ffffffff810e9f72: get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8110513d)
Location: kernel/ucount.c:159
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81104be0-ffffffff81104c09: get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112ab8d)
Location: kernel/ucount.c:155
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff8112a4e0-ffffffff8112a509: get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137cf6)
Location: kernel/ucount.c:155
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81137530-ffffffff81137559: get_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ucounts *get_ucounts(struct ucounts *ucounts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142f06)
Location: kernel/ucount.c:156
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - mm/mlock.c:user_shm_lock
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81142710-ffffffff81142739: get_ucounts (STB_GLOBAL)
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
struct ucounts *get_ucounts(struct user_namespace *ns, kuid_t uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff80001012fe10)
Location: kernel/ucount.c:125
Inline: False
Direct callers:
  - kernel/ucount.c:inc_ucount
```
**Symbols:**

```
ffff80001012fe10-ffff800010130030: get_ucounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037fa68)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c0000000001797a0)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
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
In kernel/ucount.c (ffffffe0000e375a)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ca055)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8875)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9585)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d1ae5)
Location: kernel/ucount.c:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucounts *ucounts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *ns</code>
</li>
<li>
<b>Param removed. </b>
<code>kuid_t uid</code>
</li>
</ul>
</details>
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
</ul>
