# Function: <code>io_uring_get_socket</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d0b0)
Location: fs/io_uring.c:374
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff8132d0b0-ffffffff8132d0db: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133fe70)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff8133fe70-ffffffff8133fe9b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81379850)
Location: fs/io_uring.c:905
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81379850-ffffffff8137987b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81387b60)
Location: fs/io_uring.c:1034
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81387b60-ffffffff81387b8b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138ebe0)
Location: fs/io_uring.c:1072
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff8138ebe0-ffffffff8138ec0b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dc480)
Location: fs/io_uring.c:1111
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff813dc480-ffffffff813dc4ab: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4cb0)
Location: io_uring/io_uring.c:1265
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff816c4cb0-ffffffff816c4ce7: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81786250)
Location: io_uring/io_uring.c:156
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81786250-ffffffff81786287: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c6840)
Location: io_uring/io_uring.c:155
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff817c6840-ffffffff817c687a: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000103ffe18)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffff8000103ffe18-ffff8000103ffe6c: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d1c90)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
c05d1c90-c05d1cc8: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509310)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
c000000000509310-c000000000509350: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ac5a6)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffe0002ac5a6-ffffffe0002ac5de: io_uring_get_socket (STB_GLOBAL)
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
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338450)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81338450-ffffffff8133847b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81329180)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81329180-ffffffff813291ab: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81335f20)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81335f20-ffffffff81335f4b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *io_uring_get_socket(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81348ff0)
Location: fs/io_uring.c:375
Inline: False
Direct callers:
  - net/unix/scm.c:unix_get_socket
```
**Symbols:**

```
ffffffff81348ff0-ffffffff8134901b: io_uring_get_socket (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
