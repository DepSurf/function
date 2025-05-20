# Function: <code>io_setup_async_addr</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_setup_async_addr(struct io_kiocb *req, struct __kernel_sockaddr_storage *addr_storage, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff81795a80)
Location: io_uring/net.c:219
Inline: False
Direct callers:
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
```
**Symbols:**

```
ffffffff81795a80-ffffffff81795b63: io_setup_async_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_setup_async_addr(struct io_kiocb *req, struct __kernel_sockaddr_storage *addr_storage, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d6710)
Location: io_uring/net.c:225
Inline: False
Direct callers:
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
```
**Symbols:**

```
ffffffff817d6710-ffffffff817d67f3: io_setup_async_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_setup_async_addr(struct io_kiocb *req, struct __kernel_sockaddr_storage *addr_storage, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff8181a5d0)
Location: io_uring/net.c:237
Inline: False
Direct callers:
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
```
**Symbols:**

```
ffffffff8181a5d0-ffffffff8181a6b3: io_setup_async_addr (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
