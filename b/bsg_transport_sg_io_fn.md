# Function: <code>bsg_transport_sg_io_fn</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bsg_transport_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815ef860)
Location: block/bsg-lib.c:28
Inline: False
```
**Symbols:**

```
ffffffff815ef860-ffffffff815efbb9: bsg_transport_sg_io_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bsg_transport_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff816a0810)
Location: block/bsg-lib.c:28
Inline: False
```
**Symbols:**

```
ffffffff816a0810-ffffffff816a0bb4: bsg_transport_sg_io_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bsg_transport_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8175f390)
Location: block/bsg-lib.c:28
Inline: False
```
**Symbols:**

```
ffffffff8175f390-ffffffff8175f734: bsg_transport_sg_io_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bsg_transport_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, bool open_for_write, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8179e270)
Location: block/bsg-lib.c:28
Inline: False
```
**Symbols:**

```
ffffffff8179e270-ffffffff8179e61c: bsg_transport_sg_io_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bsg_transport_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, bool open_for_write, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff817e1cf0)
Location: block/bsg-lib.c:28
Inline: False
```
**Symbols:**

```
ffffffff817e1cf0-ffffffff817e209c: bsg_transport_sg_io_fn (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
