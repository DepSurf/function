# Function: <code>io_wqe_activate_free_worker</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138a197)
Location: fs/io-wq.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139b0b2)
Location: fs/io-wq.c:269
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe *wqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a2320)
Location: fs/io-wq.c:208
Inline: False
Direct callers:
  - fs/io-wq.c:io_wqe_hash_wake
  - fs/io-wq.c:io_wqe_enqueue
```
**Symbols:**

```
ffffffff813a2320-ffffffff813a2416: io_wqe_activate_free_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe *wqe, struct io_wqe_acct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f0ee0)
Location: fs/io-wq.c:250
Inline: False
Direct callers:
  - fs/io-wq.c:io_wqe_hash_wake
  - fs/io-wq.c:io_wqe_hash_wake
  - fs/io-wq.c:io_wqe_enqueue
```
**Symbols:**

```
ffffffff813f0ee0-ffffffff813f0fa8: io_wqe_activate_free_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe *wqe, struct io_wqe_acct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9aa0)
Location: io_uring/io-wq.c:257
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
  - io_uring/io-wq.c:io_wqe_hash_wake
  - io_uring/io-wq.c:io_wqe_enqueue
```
**Symbols:**

```
ffffffff816d9aa0-ffffffff816d9b81: io_wqe_activate_free_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe *wqe, struct io_wqe_acct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5ac0)
Location: io_uring/io-wq.c:259
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
  - io_uring/io-wq.c:io_wqe_hash_wake
  - io_uring/io-wq.c:io_wqe_enqueue
```
**Symbols:**

```
ffffffff817a5ac0-ffffffff817a5ba1: io_wqe_activate_free_worker (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_wqe_acct *acct</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
