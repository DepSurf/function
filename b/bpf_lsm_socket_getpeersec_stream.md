# Function: <code>bpf_lsm_socket_getpeersec_stream</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, char *optval, int *optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812392c0)
Location: include/linux/lsm_hook_defs.h:294
Inline: False
```
**Symbols:**

```
ffffffff812392c0-ffffffff812392cd: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, char *optval, int *optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123dab0)
Location: include/linux/lsm_hook_defs.h:304
Inline: False
```
**Symbols:**

```
ffffffff8123dab0-ffffffff8123dabd: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, char *optval, int *optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278570)
Location: include/linux/lsm_hook_defs.h:304
Inline: False
```
**Symbols:**

```
ffffffff81278570-ffffffff8127857d: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, char *optval, int *optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8cc0)
Location: include/linux/lsm_hook_defs.h:303
Inline: False
```
**Symbols:**

```
ffffffff812c8cc0-ffffffff812c8cd1: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, sockptr_t optval, sockptr_t optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f500)
Location: include/linux/lsm_hook_defs.h:311
Inline: False
```
**Symbols:**

```
ffffffff8132f500-ffffffff8132f511: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, sockptr_t optval, sockptr_t optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81360170)
Location: include/linux/lsm_hook_defs.h:312
Inline: False
```
**Symbols:**

```
ffffffff81360170-ffffffff81360181: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_socket_getpeersec_stream(struct socket *sock, sockptr_t optval, sockptr_t optlen, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389020)
Location: include/linux/lsm_hook_defs.h:322
Inline: False
```
**Symbols:**

```
ffffffff81389020-ffffffff81389034: bpf_lsm_socket_getpeersec_stream (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *optlen</code> ➡️ <code>sockptr_t optlen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
