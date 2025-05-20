# Function: <code>io_wq_free_work</code>

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
struct io_wq_work *io_wq_free_work(struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e7bd0)
Location: fs/io_uring.c:6835
Inline: False
```
**Symbols:**

```
ffffffff813e7bd0-ffffffff813e7c3e: io_wq_free_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct io_wq_work *io_wq_free_work(struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8049
Inline: False
```
**Symbols:**

```
ffffffff816d3060-ffffffff816d3121: io_wq_free_work (STB_LOCAL)
ffffffff81e914ab-ffffffff81e914e0: io_wq_free_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_wq_work *io_wq_free_work(struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790800)
Location: io_uring/io_uring.c:1887
Inline: False
```
**Symbols:**

```
ffffffff81790800-ffffffff817908b7: io_wq_free_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_wq_work *io_wq_free_work(struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d1a10)
Location: io_uring/io_uring.c:1899
Inline: False
```
**Symbols:**

```
ffffffff817d1a10-ffffffff817d1b0d: io_wq_free_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_wq_work *io_wq_free_work(struct io_wq_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81814d30)
Location: io_uring/io_uring.c:1928
Inline: False
```
**Symbols:**

```
ffffffff81814d30-ffffffff81814e2d: io_wq_free_work (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
