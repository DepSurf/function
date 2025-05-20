# Function: <code>msg_get</code>

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
In ipc/mqueue.c (ffffffff8132cf65)
Location: ipc/mqueue.c:156
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
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
In ipc/mqueue.c (ffffffff81362825)
Location: ipc/mqueue.c:156
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
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
In ipc/mqueue.c (ffffffff81379015)
Location: ipc/mqueue.c:156
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
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
In ipc/mqueue.c (ffffffff8138c70d)
Location: ipc/mqueue.c:159
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
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
In ipc/mqueue.c (ffffffff813b1abd)
Location: ipc/mqueue.c:159
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
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
In ipc/mqueue.c (ffffffff813e25fb)
Location: ipc/mqueue.c:159
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
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
In ipc/mqueue.c (ffffffff813fd04c)
Location: ipc/mqueue.c:159
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
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
In ipc/mqueue.c (ffffffff81429679)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff814433a9)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff81494039)
Location: ipc/mqueue.c:249
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff814b1999)
Location: ipc/mqueue.c:249
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff814b7819)
Location: ipc/mqueue.c:249
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct msg_msg *msg_get(struct mqueue_inode_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff8150fd70)
Location: ipc/mqueue.c:249
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
Direct callers:
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff8150e270-ffffffff8150e402: msg_get (STB_LOCAL)
ffffffff81cd2d6c-ffffffff81cd2dc6: msg_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct msg_msg *msg_get(struct mqueue_inode_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff815a11ea)
Location: ipc/mqueue.c:248
Inline: True
Direct callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff815a10d0-ffffffff815a1260: msg_get (STB_LOCAL)
ffffffff81e85f3e-ffffffff81e85f98: msg_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct msg_msg *msg_get(struct mqueue_inode_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff8164abca)
Location: ipc/mqueue.c:248
Inline: True
Direct callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff8164aab0-ffffffff8164ac69: msg_get (STB_LOCAL)
ffffffff8207307c-ffffffff820730a6: msg_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct msg_msg *msg_get(struct mqueue_inode_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff816837ae)
Location: ipc/mqueue.c:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
Direct callers:
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff81682df0-ffffffff81682fa9: msg_get (STB_LOCAL)
ffffffff820f2cc8-ffffffff820f2cf2: msg_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct msg_msg *msg_get(struct mqueue_inode_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (ffffffff816bfbce)
Location: ipc/mqueue.c:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
Direct callers:
  - ipc/mqueue.c:do_mq_timedreceive
```
**Symbols:**

```
ffffffff816bf1f0-ffffffff816bf3a9: msg_get (STB_LOCAL)
ffffffff821cff60-ffffffff821cff8a: msg_get.cold (STB_LOCAL)
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
In ipc/mqueue.c (ffff80001052b074)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (c06e3374)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (c000000000676840)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffe00038e1bc)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff8143b989)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff8142c3f9)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff81437b29)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
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
In ipc/mqueue.c (ffffffff8144e0a7)
Location: ipc/mqueue.c:189
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
