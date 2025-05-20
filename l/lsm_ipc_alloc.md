# Function: <code>lsm_ipc_alloc</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lsm_ipc_alloc(struct kern_ipc_perm *kip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a045e)
Location: security/security.c:561
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff8139dc30-ffffffff8139dc6c: lsm_ipc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lsm_ipc_alloc(struct kern_ipc_perm *kip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6213)
Location: security/security.c:521
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff813c3550-ffffffff813c358d: lsm_ipc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814115d5)
Location: security/security.c:590
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff8143ee55)
Location: security/security.c:589
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff81458815)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab6d5)
Location: security/security.c:687
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8cde)
Location: security/security.c:689
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf31e)
Location: security/security.c:692
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527fde)
Location: security/security.c:692
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd06e)
Location: security/security.c:720
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816693be)
Location: security/security.c:769
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a19be)
Location: security/security.c:777
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de23e)
Location: security/security.c:771
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544744)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (c06fa620)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (c000000000699684)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffe0003a082a)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff81450df5)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff81441845)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff8144ce95)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
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
In security/security.c (ffffffff81464265)
Location: security/security.c:623
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
  - security/security.c:security_shm_alloc
  - security/security.c:security_msg_queue_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
