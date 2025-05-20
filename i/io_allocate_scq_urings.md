# Function: <code>io_allocate_scq_urings</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813310f1)
Location: fs/io_uring.c:3243
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff81344cb6)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c6a0)
Location: fs/io_uring.c:8067
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8137c6a0-ffffffff8137c794: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138abd0)
Location: fs/io_uring.c:9558
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8138abd0-ffffffff8138acac: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399cc8)
Location: fs/io_uring.c:9532
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e8da5)
Location: fs/io_uring.c:10207
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f452)
Location: io_uring/io_uring.c:11862
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81e8f452-ffffffff81e8f534: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a4c0)
Location: io_uring/io_uring.c:3436
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8178a4c0-ffffffff8178a5a5: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cb700)
Location: io_uring/io_uring.c:3722
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff817cb700-ffffffff817cb84f: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_allocate_scq_urings(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818165f0)
Location: io_uring/io_uring.c:3745
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff818165f0-ffffffff8181674a: io_allocate_scq_urings (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff80001040303c)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (c05d64d8)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (c00000000050f9ac)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffe0002b085e)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8133d296)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8132df56)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8133ad66)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8134df16)
Location: fs/io_uring.c:3796
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
