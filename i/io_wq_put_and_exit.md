# Function: <code>io_wq_put_and_exit</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a39f0)
Location: fs/io-wq.c:1082
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_cancel
```
**Symbols:**

```
ffffffff813a39f0-ffffffff813a3b55: io_wq_put_and_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f2f60)
Location: fs/io-wq.c:1271
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff813f2f60-ffffffff813f3227: io_wq_put_and_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816dbad0)
Location: io_uring/io-wq.c:1297
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff816dbad0-ffffffff816dbda3: io_wq_put_and_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a7bd0)
Location: io_uring/io-wq.c:1290
Inline: False
Direct callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff817a7bd0-ffffffff817a7ea6: io_wq_put_and_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e8ad0)
Location: io_uring/io-wq.c:1247
Inline: False
Direct callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff817e8ad0-ffffffff817e8cd9: io_wq_put_and_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_wq_put_and_exit(struct io_wq *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182e880)
Location: io_uring/io-wq.c:1266
Inline: False
Direct callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff8182e880-ffffffff8182ea89: io_wq_put_and_exit (STB_GLOBAL)
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
