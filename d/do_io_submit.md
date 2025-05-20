# Function: <code>do_io_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb **iocbpp, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125d420)
Location: fs/aio.c:1572
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_submit
  - fs/compat.c:compat_SyS_io_submit
```
**Symbols:**

```
ffffffff8125d420-ffffffff8125d91f: do_io_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb **iocbpp, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81286110)
Location: fs/aio.c:1580
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_submit
  - fs/compat.c:compat_SyS_io_submit
```
**Symbols:**

```
ffffffff81286110-ffffffff81286650: do_io_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb **iocbpp, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81299530)
Location: fs/aio.c:1629
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:SyS_io_submit
```
**Symbols:**

```
ffffffff81299530-ffffffff81299b43: do_io_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb **iocbpp, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a71e0)
Location: fs/aio.c:1647
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:SyS_io_submit
```
**Symbols:**

```
ffffffff812a71e0-ffffffff812a78ac: do_io_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb **iocbpp, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812ca570)
Location: fs/aio.c:1655
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:SyS_io_submit
```
**Symbols:**

```
ffffffff812ca570-ffffffff812cabde: do_io_submit (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
