# Function: <code>free_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813255b0)
Location: ipc/msgutil.c:171
Inline: False
Direct callers:
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff813255b0-ffffffff813255ee: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8135a1a0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8135a1a0-ffffffff8135a1de: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81370680)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff81370680-ffffffff813706be: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81383a50)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff81383a50-ffffffff81383a8e: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813a7ec0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff813a7ec0-ffffffff813a7efe: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813d72c0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff813d72c0-ffffffff813d72fe: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff813f18d0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
ffffffff813f18d0-ffffffff813f190e: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8141db90)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff8141db90-ffffffff8141dbd3: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814379e0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff814379e0-ffffffff81437a23: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81487954)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81487c10-ffffffff81487c53: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814a4f74)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff814a5230-ffffffff814a5273: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff814aaf1c)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff814ab1d0-ffffffff814ab213: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff815033dc)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81503690-ffffffff815036d3: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81594a5d)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81594d50-ffffffff81594d9b: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8163d70d)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff8163da30-ffffffff8163da7b: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81675c0d)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81675f30-ffffffff81675f7b: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff816b1fcd)
Location: ipc/msgutil.c:169
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff816b22f0-ffffffff816b233b: free_msg (STB_GLOBAL)
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
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffff80001051e588)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffff80001051e588-ffff80001051e5dc: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (c06da670)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
c06da670-c06da6c0: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (c000000000667750)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
c000000000667750-c0000000006677dc: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffe000385892)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffe000385892-ffffffe0003858e8: free_msg (STB_GLOBAL)
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
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8142ffc0)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff8142ffc0-ffffffff81430003: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81420a40)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81420a40-ffffffff81420a83: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff8142c160)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff8142c160-ffffffff8142c1a3: free_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_msg(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msgutil.c (ffffffff81443180)
Location: ipc/msgutil.c:169
Inline: False
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81443180-ffffffff814431bb: free_msg (STB_GLOBAL)
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
