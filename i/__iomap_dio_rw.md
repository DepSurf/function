# Function: <code>__iomap_dio_rw</code>

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
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, bool wait_for_completion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813be9c0)
Location: fs/iomap/direct-io.c:421
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff813be9c0-ffffffff813beeae: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5620)
Location: fs/iomap/direct-io.c:451
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff813c5620-ffffffff813c5ba5: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:453
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81cc7a95-ffffffff81cc7b41: __iomap_dio_rw.cold (STB_LOCAL)
ffffffff814159f0-ffffffff8141603b: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:484
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81e7a67f-ffffffff81e7a735: __iomap_dio_rw.cold (STB_LOCAL)
ffffffff8148d190-ffffffff8148d870: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:483
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff8206b628-ffffffff8206b6e6: __iomap_dio_rw.cold (STB_LOCAL)
ffffffff815206f0-ffffffff81520e28: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:470
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff820eb594-ffffffff820eb605: __iomap_dio_rw.cold (STB_LOCAL)
ffffffff81558710-ffffffff81558e3c: __iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct iomap_dio *__iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:540
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff821c87db-ffffffff821c882f: __iomap_dio_rw.cold (STB_LOCAL)
ffffffff8158ee10-ffffffff8158f57a: __iomap_dio_rw (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int dio_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait_for_completion</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *private</code>
</li>
<li>
<b>Param added. </b>
<code>size_t done_before</code>
</li>
</ul>
</details>
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
