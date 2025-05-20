# Function: <code>poll_requested_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:64
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a33c4)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/unix/af_unix.c (ffffffff817be239)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:64
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa48e)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/unix/af_unix.c (ffffffff8182b1b6)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:64
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8162875e)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/unix/af_unix.c (ffffffff8185cbe6)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:64
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e3a7)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/unix/af_unix.c (ffffffff8188135d)
Location: include/linux/poll.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:65
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a71aa)
Location: include/linux/poll.h:65
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/unix/af_unix.c (ffffffff819024f3)
Location: include/linux/poll.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c8f0b)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e3421)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff818706e0)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81959e51)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e2ece)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817067a1)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff818901cc)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff8198efa6)
Location: include/linux/poll.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140e9d1)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8174190b)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff818da04d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff819fa71f)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81427921)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765a8b)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff8190c02d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81a313a9)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477841)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825d43)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff819defbd)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81b25365)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492cc3)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8183672b)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff819de84d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81b33ed5)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81497c33)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818198fb)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff819c47ed)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81b21885)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ef843)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a4055)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81a73c4d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81be6bfd)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157cc9e)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed9d7)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81be6ebd)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81d7d5dc)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816227ee)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ad14)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81d92e9d)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81f4adec)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165ac2e)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe174)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81e012a4)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81faaa98)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816948fe)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c128c4)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81ebdc54)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff82077e88)
Location: include/linux/poll.h:68
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050c5b8)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffff800010965c8c)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffff800010ba10ec)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffff800010cf1ce0)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c5ec8)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (c0a3c858)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (c0cc344c)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (c0df7b38)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000064ffb4)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d2a0)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (c000000000c754e8)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (c000000000e15908)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000376de2)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d2960)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffe000739188)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffe00083da64)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141ff01)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a17b)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff818ac02d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff819d0a39)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410981)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f35eb)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff81865f7d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff8198d7f9)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141c0a1)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81758f4b)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff818fd02d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81a3b4b9)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81431be1)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817743d3)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In net/socket.c (ffffffff8191e09d)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/unix/af_unix.c (ffffffff81a46139)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
```
</details>
</li>
</ul>

## Differences
