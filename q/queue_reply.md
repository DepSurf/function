# Function: <code>queue_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814d0340)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:185
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff814d0340-ffffffff814d03ad: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81521436)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81520fc0-ffffffff8152102d: queue_reply.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154dac3)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8154d420-ffffffff8154d48d: queue_reply.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8156168c)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81561590-ffffffff81561604: queue_reply.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5e1c)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff815c5850-ffffffff815c58c4: queue_reply.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe549)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff815fdf40-ffffffff815fdfb4: queue_reply.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619619)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:183
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81619010-ffffffff81619084: queue_reply.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164d356)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:186
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8164cd10-ffffffff8164cd84: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f846)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8166f450-ffffffff8166f4c4: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171fc2e)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8171f3e0-ffffffff8171f454: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173cb92)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8173c340-ffffffff8173c3b4: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff817206f8)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8171fea0-ffffffff8171ff14: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f518)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8179ef60-ffffffff8179efd4: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int queue_reply(struct list_head *queue, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d86c0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff818d86c0-ffffffff818d8759: queue_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int queue_reply(struct list_head *queue, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b3c0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81a2b3c0-ffffffff81a2b459: queue_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int queue_reply(struct list_head *queue, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74b60)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81a74b60-ffffffff81a74bf9: queue_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int queue_reply(struct list_head *queue, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6cc0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81ac6cc0-ffffffff81ac6d59: queue_reply (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a384)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffff80001083a108-ffff80001083a17c: queue_reply.part.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635906)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81635510-ffffffff81635584: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663686)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff81663290-ffffffff81663304: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167dc46)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:189
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
**Symbols:**

```
ffffffff8167d850-ffffffff8167d8c4: queue_reply.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
