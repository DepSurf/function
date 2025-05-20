# Function: <code>tun_ptr_free</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173b930)
Location: drivers/net/tun.c:658
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff8173b930-ffffffff8173b957: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8175f090)
Location: drivers/net/tun.c:658
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff8175f090-ffffffff8175f0b7: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179c750)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff8179c750-ffffffff8179c777: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0200)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff817c0200-ffffffff817c0227: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188efb6)
Location: drivers/net/tun.c:620
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81889c80-ffffffff81889ca7: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189ced4)
Location: drivers/net/tun.c:591
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81897ea0-ffffffff81897ec7: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187f554)
Location: drivers/net/tun.c:599
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff8187a750-ffffffff8187a777: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff819113b3)
Location: drivers/net/tun.c:605
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff8190bc70-ffffffff8190bc97: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a64255)
Location: drivers/net/tun.c:610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81a60020-ffffffff81a60064: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bef4a5)
Location: drivers/net/tun.c:610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81beb790-ffffffff81beb7d4: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c47585)
Location: drivers/net/tun.c:610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81c43c40-ffffffff81c43c84: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfce85)
Location: drivers/net/tun.c:610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81cf9500-ffffffff81cf9544: tun_ptr_free (STB_GLOBAL)
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
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109da990)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffff8000109da990-ffff8000109da9d8: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac13ec)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
c0ac13ec-c0ac1424: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9c950)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
c000000000a9c950-c000000000a9c9bc: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000625776)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffe000625776-ffffffe0006257be: tun_ptr_free (STB_GLOBAL)
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
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81784cd0)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81784cd0-ffffffff81784cf7: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81764620)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff81764620-ffffffff81764647: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5080)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff817b5080-ffffffff817b50a7: tun_ptr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tun_ptr_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cf050)
Location: drivers/net/tun.c:652
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
**Symbols:**

```
ffffffff817cf050-ffffffff817cf077: tun_ptr_free (STB_GLOBAL)
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
