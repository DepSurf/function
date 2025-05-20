# Function: <code>iov_iter_kvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb810)
Location: lib/iov_iter.c:529
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff813fb810-ffffffff813fb834: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442bc0)
Location: lib/iov_iter.c:478
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81442bc0-ffffffff81442be4: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145fdd0)
Location: lib/iov_iter.c:805
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8145fdd0-ffffffff8145fdf4: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464ec0)
Location: lib/iov_iter.c:931
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81464ec0-ffffffff81464ee4: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490e40)
Location: lib/iov_iter.c:933
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81490e40-ffffffff81490e63: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6090)
Location: lib/iov_iter.c:1063
Inline: True
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff814c6090-ffffffff814c60b3: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814d9eb0)
Location: lib/iov_iter.c:1117
Inline: False
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff814d9eb0-ffffffff814d9ede: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8150ac78-ffffffff8150aca9: iov_iter_kvec.cold (STB_LOCAL)
ffffffff81505720-ffffffff8150575b: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523670)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81523670-ffffffff81523699: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586c70)
Location: lib/iov_iter.c:1165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81586c70-ffffffff81586c99: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a3f40)
Location: lib/iov_iter.c:1172
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff815a3f40-ffffffff815a3f69: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aae50)
Location: lib/iov_iter.c:1274
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff815aae50-ffffffff815aae7c: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614130)
Location: lib/iov_iter.c:1127
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81614130-ffffffff8161415a: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0a50)
Location: lib/iov_iter.c:1179
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff816e0a50-ffffffff816e0a8d: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d0da0)
Location: lib/iov_iter.c:997
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff817d0da0-ffffffff817d0ddd: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180fb70)
Location: lib/iov_iter.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/core/skbuff.c:__skb_send_sock
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff8180fb70-ffffffff8180fbad: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818557e0)
Location: lib/iov_iter.c:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/core/skbuff.c:__skb_send_sock
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/handshake/alert.c:tls_alert_send
```
**Symbols:**

```
ffffffff818557e0-ffffffff8185581d: iov_iter_kvec (STB_GLOBAL)
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
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d4b8)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffff80001062d4b8-ffff80001062d4f4: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4088)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
c07d4088-c07d40ec: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0680)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
c0000000007d0680-c0000000007d06b8: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d328)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffe00045d328-ffffffe00045d350: iov_iter_kvec (STB_GLOBAL)
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
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bc50)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8151bc50-ffffffff8151bc79: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150bf40)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8150bf40-ffffffff8150bf69: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517ce0)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81517ce0-ffffffff81517d09: iov_iter_kvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iov_iter_kvec(struct iov_iter *i, unsigned int direction, const struct kvec *kvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531480)
Location: lib/iov_iter.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81531480-ffffffff815314a9: iov_iter_kvec (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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
