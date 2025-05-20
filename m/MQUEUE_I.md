# Function: <code>MQUEUE_I</code>

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
In ipc/mqueue.c (ffffffff8132c476)
Location: ipc/mqueue.c:96
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_i_callback
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
In ipc/mqueue.c (ffffffff81362729)
Location: ipc/mqueue.c:96
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:mqueue_i_callback
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
In ipc/mqueue.c (ffffffff81378f19)
Location: ipc/mqueue.c:96
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:mqueue_i_callback
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
In ipc/mqueue.c (ffffffff8138c617)
Location: ipc/mqueue.c:99
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_i_callback
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
In ipc/mqueue.c (ffffffff813b19c7)
Location: ipc/mqueue.c:99
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_i_callback
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
In ipc/mqueue.c (ffffffff813e127c)
Location: ipc/mqueue.c:99
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_i_callback
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff813fbe5c)
Location: ipc/mqueue.c:99
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_i_callback
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff8142811f)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff81441e4f)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff81492a2f)
Location: ipc/mqueue.c:168
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff814b032f)
Location: ipc/mqueue.c:168
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff814b617f)
Location: ipc/mqueue.c:168
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff8150eabf)
Location: ipc/mqueue.c:168
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff815a28b1)
Location: ipc/mqueue.c:167
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
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
In ipc/mqueue.c (ffffffff8164c3d1)
Location: ipc/mqueue.c:167
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
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
In ipc/mqueue.c (ffffffff81684b17)
Location: ipc/mqueue.c:167
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_free_inode
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
In ipc/mqueue.c (ffffffff816c0f57)
Location: ipc/mqueue.c:167
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_free_inode
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
In ipc/mqueue.c (ffff80001052a8b0)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (c06e4ee0)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (c000000000675544)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffe00038ce5c)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff8143a42f)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff8142ae9f)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff814365cf)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
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
In ipc/mqueue.c (ffffffff8144cd6f)
Location: ipc/mqueue.c:107
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_free_inode
  - ipc/mqueue.c:mqueue_get_inode
```
</details>
</li>
</ul>

## Differences
