# Function: <code>queue_nonrot_store</code>

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
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815632f0)
Location: block/blk-sysfs.c:287
Inline: False
```
**Symbols:**

```
ffffffff815632f0-ffffffff81563381: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8156ba50)
Location: block/blk-sysfs.c:298
Inline: False
```
**Symbols:**

```
ffffffff8156ba50-ffffffff8156bae0: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815cfce0)
Location: block/blk-sysfs.c:302
Inline: False
```
**Symbols:**

```
ffffffff815cfce0-ffffffff815cfd70: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8167b4b0)
Location: block/blk-sysfs.c:303
Inline: False
```
**Symbols:**

```
ffffffff8167b4b0-ffffffff8167b550: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81737ce0)
Location: block/blk-sysfs.c:308
Inline: False
```
**Symbols:**

```
ffffffff81737ce0-ffffffff81737d80: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817742a0)
Location: block/blk-sysfs.c:304
Inline: False
```
**Symbols:**

```
ffffffff817742a0-ffffffff81774340: queue_nonrot_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t queue_nonrot_store(struct request_queue *q, const char *page, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817b6630)
Location: block/blk-sysfs.c:304
Inline: False
```
**Symbols:**

```
ffffffff817b6630-ffffffff817b66d0: queue_nonrot_store (STB_LOCAL)
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
