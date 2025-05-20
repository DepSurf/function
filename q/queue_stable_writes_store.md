# Function: <code>queue_stable_writes_store</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81563250)
Location: block/blk-sysfs.c:290
Inline: False
```
**Symbols:**

```
ffffffff81563250-ffffffff815632e1: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8156b8a0)
Location: block/blk-sysfs.c:301
Inline: False
```
**Symbols:**

```
ffffffff8156b8a0-ffffffff8156b930: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815cfc50)
Location: block/blk-sysfs.c:305
Inline: False
```
**Symbols:**

```
ffffffff815cfc50-ffffffff815cfce0: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8167b410)
Location: block/blk-sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff8167b410-ffffffff8167b4b0: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81737ad0)
Location: block/blk-sysfs.c:311
Inline: False
```
**Symbols:**

```
ffffffff81737ad0-ffffffff81737b70: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81774090)
Location: block/blk-sysfs.c:307
Inline: False
```
**Symbols:**

```
ffffffff81774090-ffffffff81774130: queue_stable_writes_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t queue_stable_writes_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817b6580)
Location: block/blk-sysfs.c:307
Inline: False
```
**Symbols:**

```
ffffffff817b6580-ffffffff817b6620: queue_stable_writes_store (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
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
