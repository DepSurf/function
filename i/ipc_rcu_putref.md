# Function: <code>ipc_rcu_putref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipc_rcu_putref(void *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81324c70)
Location: ipc/util.c:456
Inline: False
Direct callers:
  - ipc/msg.c:newque
  - ipc/msg.c:newque
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:newary
  - ipc/sem.c:newary
  - ipc/sem.c:freeary
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81324c70-ffffffff81324c8b: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipc_rcu_putref(void *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359860)
Location: ipc/util.c:451
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/msg.c:newque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81359860-ffffffff8135987e: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipc_rcu_putref(void *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136fd40)
Location: ipc/util.c:451
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/msg.c:newque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8136fd40-ffffffff8136fd5e: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813831d0)
Location: ipc/util.c:403
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813831d0-ffffffff813831ec: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a7560)
Location: ipc/util.c:466
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813a7560-ffffffff813a7582: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6900)
Location: ipc/util.c:470
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813d6900-ffffffff813d6922: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f0f90)
Location: ipc/util.c:470
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff813f0f90-ffffffff813f0fb2: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d230)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8141d230-ffffffff8141d251: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81437080)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81437080-ffffffff814370a1: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814871b0)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff814871b0-ffffffff814871ec: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a47d0)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff814a47d0-ffffffff814a480c: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aa790)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff814aa790-ffffffff814aa7cc: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502c50)
Location: ipc/util.c:533
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81502c50-ffffffff81502c8c: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81594230)
Location: ipc/util.c:533
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81594230-ffffffff81594290: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163ce30)
Location: ipc/util.c:533
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8163ce30-ffffffff8163ce90: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81675340)
Location: ipc/util.c:533
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81675340-ffffffff816753a0: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1700)
Location: ipc/util.c:533
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff816b1700-ffffffff816b1760: ipc_rcu_putref (STB_GLOBAL)
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
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051d7f8)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffff80001051d7f8-ffff80001051d83c: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9c24)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
c06d9c24-c06d9c60: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666a90)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
c000000000666a90-c000000000666af0: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe000385088)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffe000385088-ffffffe0003850da: ipc_rcu_putref (STB_GLOBAL)
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
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f660)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8142f660-ffffffff8142f681: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814200e0)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff814200e0-ffffffff81420101: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142b800)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff8142b800-ffffffff8142b821: ipc_rcu_putref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipc_rcu_putref(struct kern_ipc_perm *ptr, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442810)
Location: ipc/util.c:499
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
**Symbols:**

```
ffffffff81442810-ffffffff81442831: ipc_rcu_putref (STB_GLOBAL)
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
