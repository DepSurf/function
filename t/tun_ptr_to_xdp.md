# Function: <code>tun_ptr_to_xdp</code>

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
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c8e8)
Location: drivers/net/tun.c:268
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8173b6d0-ffffffff8173b6e2: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81760df8)
Location: drivers/net/tun.c:274
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8175ee90-ffffffff8175eea2: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179ea7a)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff8179c590-ffffffff8179c5a2: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c250a)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817c0040-ffffffff817c0052: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188c3d0)
Location: drivers/net/tun.c:234
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
ffffffff81889ae0-ffffffff81889af2: tun_ptr_to_xdp (STB_GLOBAL)
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
In drivers/net/tun.c (ffffffff8189ab35)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff8187d3b5)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff8190f6ca)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff81a62720)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff81bedf00)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff81c46430)
Location: include/linux/if_tun.h:38
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
In drivers/net/tun.c (ffffffff81cfbd40)
Location: include/linux/if_tun.h:38
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
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dcc4c)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffff8000109da710-ffff8000109da738: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac1760)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
c0ac11f8-c0ac1214: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa2af8)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
c000000000a9c710-c000000000a9c720: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000627a84)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffe00062547e-ffffffe0006254a2: tun_ptr_to_xdp (STB_GLOBAL)
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
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81786fda)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81784b10-ffffffff81784b22: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176692a)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff81764460-ffffffff81764472: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b738a)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817b4ec0-ffffffff817b4ed2: tun_ptr_to_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *tun_ptr_to_xdp(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cf443)
Location: drivers/net/tun.c:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_ptr_free
```
**Symbols:**

```
ffffffff817cee90-ffffffff817ceea2: tun_ptr_to_xdp (STB_GLOBAL)
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
