# Function: <code>tun_is_xdp_frame</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c8e4)
Location: drivers/net/tun.c:256
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8173b6a0-ffffffff8173b6b0: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81760df4)
Location: drivers/net/tun.c:262
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8175ee60-ffffffff8175ee70: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179ea76)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8179c560-ffffffff8179c570: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c2506)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817c0010-ffffffff817c0020: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188c3cc)
Location: drivers/net/tun.c:222
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81889ab0-ffffffff81889ac0: tun_is_xdp_frame (STB_GLOBAL)
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
In drivers/net/tun.c (ffffffff8189ab31)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
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
In drivers/net/tun.c (ffffffff8187d3b1)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
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
In drivers/net/tun.c (ffffffff8190f6c6)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a6271c)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bedefc)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
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
In drivers/net/tun.c (ffffffff81c4642c)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
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
In drivers/net/tun.c (ffffffff81cfbd3c)
Location: include/linux/if_tun.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dcc48)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffff8000109da6c0-ffff8000109da6e8: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac1758)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
c0ac11c0-c0ac11dc: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa2af0)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
c000000000a9c6f0-c000000000a9c700: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000627a7e)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffe000625436-ffffffe00062545a: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81786fd6)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81784ae0-ffffffff81784af0: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81766926)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81764430-ffffffff81764440: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b7386)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817b4e90-ffffffff817b4ea0: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tun_is_xdp_frame(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cf43f)
Location: drivers/net/tun.c:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817cee60-ffffffff817cee70: tun_is_xdp_frame (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
