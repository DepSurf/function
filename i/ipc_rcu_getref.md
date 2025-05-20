# Function: <code>ipc_rcu_getref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipc_rcu_getref(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81324c20)
Location: ipc/util.c:449
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81324c20-ffffffff81324c69: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipc_rcu_getref(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359810)
Location: ipc/util.c:444
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81359810-ffffffff81359859: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipc_rcu_getref(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136fcf0)
Location: ipc/util.c:444
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8136fcf0-ffffffff8136fd39: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81383180)
Location: ipc/util.c:398
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81383180-ffffffff813831c1: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a74f0)
Location: ipc/util.c:461
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813a74f0-ffffffff813a7556: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6890)
Location: ipc/util.c:465
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813d6890-ffffffff813d68fa: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f0f20)
Location: ipc/util.c:465
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813f0f20-ffffffff813f0f88: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d1f0)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8141d1f0-ffffffff8141d22a: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81437040)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81437040-ffffffff8143707a: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487150)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81487150-ffffffff814871a2: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4770)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814a4770-ffffffff814a47c2: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aa740)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814aa740-ffffffff814aa78e: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502c00)
Location: ipc/util.c:528
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:exit_shm
```
**Symbols:**

```
ffffffff81502c00-ffffffff81502c4e: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff815941c0)
Location: ipc/util.c:528
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:exit_shm
```
**Symbols:**

```
ffffffff815941c0-ffffffff81594221: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163cdb0)
Location: ipc/util.c:528
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:exit_shm
```
**Symbols:**

```
ffffffff8163cdb0-ffffffff8163ce11: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816752c0)
Location: ipc/util.c:528
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:exit_shm
```
**Symbols:**

```
ffffffff816752c0-ffffffff81675321: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1680)
Location: ipc/util.c:528
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:exit_shm
```
**Symbols:**

```
ffffffff816b1680-ffffffff816b16e1: ipc_rcu_getref (STB_GLOBAL)
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
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051d7c8)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffff80001051d7c8-ffff80001051d7f4: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9c04)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c06d9c04-c06d9c24: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666a40)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c000000000666a40-c000000000666a88: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe000385044)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffe000385044-ffffffe000385088: ipc_rcu_getref (STB_GLOBAL)
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
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f620)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8142f620-ffffffff8142f65a: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814200a0)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814200a0-ffffffff814200da: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142b7c0)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8142b7c0-ffffffff8142b7fa: ipc_rcu_getref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ipc_rcu_getref(struct kern_ipc_perm *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814427d0)
Location: ipc/util.c:494
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff814427d0-ffffffff8144280a: ipc_rcu_getref (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *ptr</code> ➡️ <code>struct kern_ipc_perm *ptr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
