# Function: <code>osync_buffers_list</code>

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
In fs/buffer.c (ffffffff8124675d)
Location: fs/buffer.c:507
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8126f6ad)
Location: fs/buffer.c:503
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812828ad)
Location: fs/buffer.c:504
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8128ff58)
Location: fs/buffer.c:501
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812b2c72)
Location: fs/buffer.c:480
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812dabac)
Location: fs/buffer.c:472
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff812f008f)
Location: fs/buffer.c:473
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131192c)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff81324947)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int osync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135aa30)
Location: fs/buffer.c:500
Inline: False
Direct callers:
  - fs/buffer.c:fsync_buffers_list
```
**Symbols:**

```
ffffffff8135aa30-ffffffff8135aaf8: osync_buffers_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int osync_buffers_list(spinlock_t *lock, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368870)
Location: fs/buffer.c:499
Inline: False
Direct callers:
  - fs/buffer.c:fsync_buffers_list
```
**Symbols:**

```
ffffffff81368870-ffffffff81368938: osync_buffers_list (STB_LOCAL)
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
In fs/buffer.c (ffffffff8137176a)
Location: fs/buffer.c:499
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffffffff813c01d0)
Location: fs/buffer.c:499
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffffffff81444e6c)
Location: fs/buffer.c:499
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffffffff814d3cb7)
Location: fs/buffer.c:499
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffffffff8150bcc7)
Location: fs/buffer.c:540
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffffffff815408c7)
Location: fs/buffer.c:534
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (ffff8000103ddd44)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (c05b71d4)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:fsync_buffers_list
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
In fs/buffer.c (c0000000004e391c)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffe000295c5c)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131cf27)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8130dac7)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8131a9f7)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
In fs/buffer.c (ffffffff8132c6d0)
Location: fs/buffer.c:474
Inline: True
Inline callers:
  - fs/buffer.c:sync_mapping_buffers
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
</ul>
