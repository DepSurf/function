# Function: <code>__io_wq_cpu_online</code>

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
int __io_wq_cpu_online(struct io_wq *wq, unsigned int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f10d0)
Location: fs/io-wq.c:1295
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_cpu_offline
  - fs/io-wq.c:io_wq_cpu_online
```
**Symbols:**

```
ffffffff813f10d0-ffffffff813f1177: __io_wq_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_wq_cpu_online(struct io_wq *wq, unsigned int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9ce0)
Location: io_uring/io-wq.c:1321
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
```
**Symbols:**

```
ffffffff816d9ce0-ffffffff816d9da8: __io_wq_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_wq_cpu_online(struct io_wq *wq, unsigned int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5d30)
Location: io_uring/io-wq.c:1314
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
```
**Symbols:**

```
ffffffff817a5d30-ffffffff817a5de8: __io_wq_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e6ffe)
Location: io_uring/io-wq.c:1271
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182cc1e)
Location: io_uring/io-wq.c:1290
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
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
</ul>
