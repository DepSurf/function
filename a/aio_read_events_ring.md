# Function: <code>aio_read_events_ring</code>

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
In fs/aio.c (ffffffff8125baf3)
Location: fs/aio.c:1162
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff812845b3)
Location: fs/aio.c:1172
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff81298273)
Location: fs/aio.c:1187
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff812a5d46)
Location: fs/aio.c:1192
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff812c9276)
Location: fs/aio.c:1216
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff812f21f0)
Location: fs/aio.c:1141
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff81306c00)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff813281ac)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff8133af4c)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375910)
Location: fs/aio.c:1173
Inline: False
Direct callers:
  - fs/aio.c:aio_read_events
```
**Symbols:**

```
ffffffff81375910-ffffffff81375b8d: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813837f0)
Location: fs/aio.c:1175
Inline: False
Direct callers:
  - fs/aio.c:aio_read_events
```
**Symbols:**

```
ffffffff813837f0-ffffffff81383a58: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a580)
Location: fs/aio.c:1172
Inline: False
Direct callers:
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff8138a580-ffffffff8138a7e0: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7890)
Location: fs/aio.c:1173
Inline: False
Direct callers:
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff813d7890-ffffffff813d7aed: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461b60)
Location: fs/aio.c:1199
Inline: False
Direct callers:
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81461b60-ffffffff81461e13: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f1d00)
Location: fs/aio.c:1200
Inline: False
Direct callers:
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff814f1d00-ffffffff814f1fb3: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81527ce0)
Location: fs/aio.c:1195
Inline: False
Direct callers:
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81527ce0-ffffffff81527f1d: aio_read_events_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155cb00)
Location: fs/aio.c:1224
Inline: False
Direct callers:
  - fs/aio.c:aio_read_events
```
**Symbols:**

```
ffffffff8155cb00-ffffffff8155cd3d: aio_read_events_ring (STB_LOCAL)
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
long int aio_read_events_ring(struct kioctx *ctx, struct io_event *event, long int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fb828)
Location: fs/aio.c:1173
Inline: False
Direct callers:
  - fs/aio.c:aio_read_events
```
**Symbols:**

```
ffff8000103fb828-ffff8000103fbbac: aio_read_events_ring (STB_LOCAL)
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
In fs/aio.c (c05ce6e4)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (c0000000005030b4)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffe0002a9678)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff8133352c)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff8132419c)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff81330ffc)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
In fs/aio.c (ffffffff81343bdb)
Location: fs/aio.c:1173
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
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
</ul>
