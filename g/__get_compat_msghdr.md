# Function: <code>__get_compat_msghdr</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, compat_uptr_t *ptr, compat_size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a62af0)
Location: net/compat.c:36
Inline: False
Direct callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81a62af0-ffffffff81a62c2e: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, compat_uptr_t *ptr, compat_size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a6ac10)
Location: net/compat.c:36
Inline: False
Direct callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81a6ac10-ffffffff81a6ad4e: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, compat_uptr_t *ptr, compat_size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a53340)
Location: net/compat.c:36
Inline: False
Direct callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81a53340-ffffffff81a5347b: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, compat_uptr_t *ptr, compat_size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81b0c050)
Location: net/compat.c:36
Inline: False
Direct callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81b0c050-ffffffff81b0c18b: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, compat_uptr_t *ptr, compat_size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81c92730)
Location: net/compat.c:36
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81c92730-ffffffff81c928ca: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *msg, struct sockaddr **save_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81e4ddc0)
Location: net/compat.c:36
Inline: False
Direct callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81e4ddc0-ffffffff81e4de9f: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *msg, struct sockaddr **save_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81ea9450)
Location: net/compat.c:36
Inline: False
Direct callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81ea9450-ffffffff81ea952f: __get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *msg, struct sockaddr **save_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81f6bf10)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81f6bf10-ffffffff81f6bfef: __get_compat_msghdr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct compat_msghdr *msg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_msghdr *umsg</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_uptr_t *ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_size_t *len</code>
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
