# Function: <code>io_wake_function</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340350)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffff81340350-ffffffff81340393: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81382980)
Location: fs/io_uring.c:6282
Inline: False
```
**Symbols:**

```
ffffffff81382980-ffffffff81382a28: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a640)
Location: fs/io_uring.c:7205
Inline: False
```
**Symbols:**

```
ffffffff8138a640-ffffffff8138a696: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391ca0)
Location: fs/io_uring.c:6986
Inline: False
```
**Symbols:**

```
ffffffff81391ca0-ffffffff81391cf6: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de280)
Location: fs/io_uring.c:7568
Inline: False
```
**Symbols:**

```
ffffffff813de280-ffffffff813de2bf: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8a50)
Location: io_uring/io_uring.c:8873
Inline: False
```
**Symbols:**

```
ffffffff816c8a50-ffffffff816c8ab3: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a380)
Location: io_uring/io_uring.c:2449
Inline: False
```
**Symbols:**

```
ffffffff8178a380-ffffffff8178a3f5: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ca810)
Location: io_uring/io_uring.c:2474
Inline: False
```
**Symbols:**

```
ffffffff817ca810-ffffffff817ca880: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f2f0)
Location: io_uring/io_uring.c:2505
Inline: False
```
**Symbols:**

```
ffffffff8180f2f0-ffffffff8180f35d: io_wake_function (STB_LOCAL)
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
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104004b0)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffff8000104004b0-ffff800010400544: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d27f0)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
c05d27f0-c05d2848: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509c30)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
c000000000509c30-c000000000509ca8: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002acbb0)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffe0002acbb0-ffffffe0002acc1a: io_wake_function (STB_LOCAL)
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
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338930)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffff81338930-ffffffff81338973: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81329660)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffff81329660-ffffffff813296a3: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336400)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffff81336400-ffffffff81336443: io_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_wake_function(struct wait_queue_entry *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813494d0)
Location: fs/io_uring.c:2942
Inline: False
```
**Symbols:**

```
ffffffff813494d0-ffffffff81349513: io_wake_function (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
