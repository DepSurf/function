# Function: <code>ipc_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8132478a)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81329fa3)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_close
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8135937a)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff813602e9)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136f867)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81376b00)
Location: ipc/util.h:183
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81382d97)
Location: ipc/util.h:170
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8138a6c0)
Location: ipc/util.h:170
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a6d37)
Location: ipc/util.h:184
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff813af836)
Location: ipc/util.h:184
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6119)
Location: ipc/util.h:196
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff813df715)
Location: ipc/util.h:196
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f07c2)
Location: ipc/util.h:195
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff813f9e62)
Location: ipc/util.h:195
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141cae9)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81426360)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81436939)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff814400b0)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81486d89)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81490e59)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a3d80)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff814ae5bb)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aa360)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff814b43e8)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502849)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8150ca95)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81593463)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8159ea23)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163be33)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff816480e3)
Location: ipc/util.h:224
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816742e3)
Location: ipc/util.h:222
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8168060f)
Location: ipc/util.h:222
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b06a3)
Location: ipc/util.h:223
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff816bca2e)
Location: ipc/util.h:223
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051cb8c)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffff800010528918)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d8f84)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (c06e1d64)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666100)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (c000000000673370)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe0003849c6)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffe00038beb6)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142ef19)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81438690)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141f999)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81429100)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142b0b9)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff81434830)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81441e30)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8144b965)
Location: ipc/util.h:221
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
</details>
</li>
</ul>

## Differences
