# Function: <code>io_poll_wake</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e560)
Location: fs/io_uring.c:1628
Inline: False
```
**Symbols:**

```
ffffffff8132e560-ffffffff8132e68d: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81341940)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffff81341940-ffffffff81341ab2: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137da30)
Location: fs/io_uring.c:4710
Inline: False
```
**Symbols:**

```
ffffffff8137da30-ffffffff8137da51: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138ce40)
Location: fs/io_uring.c:5636
Inline: False
```
**Symbols:**

```
ffffffff8138ce40-ffffffff8138ce61: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813930f0)
Location: fs/io_uring.c:5399
Inline: False
```
**Symbols:**

```
ffffffff813930f0-ffffffff81393114: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e08d0)
Location: fs/io_uring.c:5858
Inline: False
```
**Symbols:**

```
ffffffff813e08d0-ffffffff813e08f4: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cea40)
Location: io_uring/io_uring.c:6794
Inline: False
```
**Symbols:**

```
ffffffff816cea40-ffffffff816ceb34: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179d590)
Location: io_uring/poll.c:414
Inline: False
```
**Symbols:**

```
ffffffff8179d590-ffffffff8179d719: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817de7c0)
Location: io_uring/poll.c:416
Inline: False
```
**Symbols:**

```
ffffffff817de7c0-ffffffff817de949: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81822b90)
Location: io_uring/poll.c:428
Inline: False
```
**Symbols:**

```
ffffffff81822b90-ffffffff81822d19: io_poll_wake (STB_LOCAL)
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
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010402148)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffff800010402148-ffff800010402308: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d4b7c)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
c05d4b7c-c05d4cb4: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050ba60)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
c00000000050ba60-c00000000050bc8c: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002adc2c)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffe0002adc2c-ffffffe0002add6e: io_poll_wake (STB_LOCAL)
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
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339f20)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffff81339f20-ffffffff8133a092: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132ac50)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffff8132ac50-ffffffff8132adae: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813379f0)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffff813379f0-ffffffff81337b62: io_poll_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_poll_wake(struct wait_queue_entry *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134be50)
Location: fs/io_uring.c:1814
Inline: False
```
**Symbols:**

```
ffffffff8134be50-ffffffff8134bfc2: io_poll_wake (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
