# Function: <code>xb_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff814cc9e0)
Location: drivers/xen/xenbus/xenbus_comms.c:94
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff814cc9e0-ffffffff814ccc3a: xb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8151d550)
Location: drivers/xen/xenbus/xenbus_comms.c:94
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8151d550-ffffffff8151d7ab: xb_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81549a20)
Location: drivers/xen/xenbus/xenbus_comms.c:94
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81549a20-ffffffff81549c42: xb_write (STB_GLOBAL)
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155daf4)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c1e04)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815fa5e2)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81615692)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81649359)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8166b7f4)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171b850)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff8171b850-ffffffff8171b9f4: xb_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81738890)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff81738890-ffffffff81738a34: xb_write (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171c38c)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8179b0fc)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff818d44e0)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff818d44e0-ffffffff818d46b6: xb_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a26760)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff81a26760-ffffffff81a26929: xb_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff81a6fd30-ffffffff81a6ff9b: xb_write (STB_LOCAL)
ffffffff8211569d-ffffffff821156dc: xb_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xb_write(const void *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:106
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
```
**Symbols:**

```
ffffffff81ac1e30-ffffffff81ac209b: xb_write (STB_LOCAL)
ffffffff821f3323-ffffffff821f3362: xb_write.cold (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_comms.c (ffff800010835c8c)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81631664)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8165f634)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81679c2f)
Location: drivers/xen/xenbus/xenbus_comms.c:114
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
