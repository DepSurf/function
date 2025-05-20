# Function: <code>iomap_dio_complete</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b0fe0)
Location: fs/iomap.c:624
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff812b0fe0-ffffffff812b107f: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812be3a0)
Location: fs/iomap.c:713
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff812be3a0-ffffffff812be440: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e1ce0)
Location: fs/iomap.c:714
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff812e1ce0-ffffffff812e1dd6: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130e470)
Location: fs/iomap.c:832
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8130e470-ffffffff8130e5b2: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323ca0)
Location: fs/iomap.c:1466
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff81323ca0-ffffffff81323de2: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134cf90)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8134cf90-ffffffff8134d0c4: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365240)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff81365240-ffffffff81365371: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813ad2d0)
Location: fs/iomap/direct-io.c:78
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813ad2d0-ffffffff813ad401: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813be2c0)
Location: fs/iomap/direct-io.c:79
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813be2c0-ffffffff813be3f6: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5300)
Location: fs/iomap/direct-io.c:79
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813c5300-ffffffff813c5436: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff814150a0)
Location: fs/iomap/direct-io.c:77
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814150a0-ffffffff814151d9: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8148c6e0)
Location: fs/iomap/direct-io.c:80
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8148c6e0-ffffffff8148c83c: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81520e40)
Location: fs/iomap/direct-io.c:80
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81520e40-ffffffff81520fb7: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81558e50)
Location: fs/iomap/direct-io.c:80
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81558e50-ffffffff81558ff8: iomap_dio_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8158f590)
Location: fs/iomap/direct-io.c:83
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_deferred_complete
```
**Symbols:**

```
ffffffff8158f590-ffffffff8158f738: iomap_dio_complete (STB_GLOBAL)
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
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042cf10)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffff80001042cf10-ffff80001042d0a4: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f5d54)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
c05f5d54-c05f5f4c: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053d410)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
c00000000053d410-c00000000053d660: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9632)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffe0002c9632-ffffffe0002c9766: iomap_dio_complete (STB_LOCAL)
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
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135d820)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8135d820-ffffffff8135d951: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134e4c0)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8134e4c0-ffffffff8134e5f1: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135b2f0)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8135b2f0-ffffffff8135b421: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t iomap_dio_complete(struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136ea40)
Location: fs/iomap/direct-io.c:73
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete_work
```
**Symbols:**

```
ffffffff8136ea40-ffffffff8136eb71: iomap_dio_complete (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
