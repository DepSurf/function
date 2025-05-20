# Function: <code>read_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125be40)
Location: fs/aio.c:1260
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_getevents
```
**Symbols:**

```
ffffffff8125be40-ffffffff8125c17a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812848f0)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_getevents
```
**Symbols:**

```
ffffffff812848f0-ffffffff81284c2a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812985a0)
Location: fs/aio.c:1285
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_getevents
```
**Symbols:**

```
ffffffff812985a0-ffffffff812988b7: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a6090)
Location: fs/aio.c:1290
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_getevents
```
**Symbols:**

```
ffffffff812a6090-ffffffff812a6324: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c95c0)
Location: fs/aio.c:1314
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff812c95c0-ffffffff812c9768: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f24c0)
Location: fs/aio.c:1238
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff812f24c0-ffffffff812f2649: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81306ec0)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81306ec0-ffffffff81307049: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328490)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81328490-ffffffff81328614: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b260)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff8133b260-ffffffff8133b3ca: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375c20)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81375c20-ffffffff81375d8a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383af0)
Location: fs/aio.c:1272
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81383af0-ffffffff81383c5a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a870)
Location: fs/aio.c:1269
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff8138a870-ffffffff8138aa1b: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7b80)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff813d7b80-ffffffff813d7d2b: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461ed0)
Location: fs/aio.c:1296
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81461ed0-ffffffff814620da: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f2090)
Location: fs/aio.c:1297
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff814f2090-ffffffff814f229a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81528cd0)
Location: fs/aio.c:1289
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81528cd0-ffffffff81528eda: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155ce10)
Location: fs/aio.c:1318
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff8155ce10-ffffffff8155d01f: read_events (STB_LOCAL)
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
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fbc70)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffff8000103fbc70-ffff8000103fbdd4: read_events (STB_LOCAL)
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
In fs/aio.c (c05cfabc)
Location: fs/aio.c:1270
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000503500)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
c000000000503500-c0000000005036d4: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9936)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffe0002a9936-ffffffe0002a9a46: read_events (STB_LOCAL)
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
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333840)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81333840-ffffffff813339aa: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813244b0)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff813244b0-ffffffff8132461a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331310)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81331310-ffffffff8133147a: read_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int read_events(struct kioctx *ctx, long int min_nr, long int nr, struct io_event *event, ktime_t until);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81343f10)
Location: fs/aio.c:1270
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
ffffffff81343f10-ffffffff81344069: read_events (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>ktime_t until</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec *timeout</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
