# Function: <code>ipc_free_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341ac9)
Location: security/selinux/hooks.c:5167
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_free_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81377169)
Location: security/selinux/hooks.c:5311
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_free_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_free_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_free_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138db69)
Location: security/selinux/hooks.c:5392
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_free_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_free_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_free_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fca12)
Location: security/selinux/hooks.c:5924
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_free_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
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
