# Function: <code>get_compat_bpf_fprog</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ab080)
Location: net/compat.c:313
Inline: False
Direct callers:
  - net/compat.c:compat_sock_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff817ab080-ffffffff817ab0fa: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817da6a0)
Location: net/compat.c:313
Inline: False
Direct callers:
  - net/compat.c:compat_sock_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff817da6a0-ffffffff817da71a: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817f9bb0)
Location: net/compat.c:312
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff817f9bb0-ffffffff817f9c4b: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818774c0)
Location: net/compat.c:319
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818774c0-ffffffff8187755b: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c8bc0)
Location: net/compat.c:319
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818c8bc0-ffffffff818c8c5b: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f3af0)
Location: net/compat.c:319
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818f3af0-ffffffff818f3b8b: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953840)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81953840-ffffffff819538de: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81989d90)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81989d90-ffffffff81989e2e: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a62150)
Location: net/compat.c:340
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81a62150-ffffffff81a621ee: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c329f0)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffff800010c329f0-ffff800010c32cf0: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2b7f0)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
c000000000d2b7f0-c000000000d2b8d0: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81929c00)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81929c00-ffffffff81929c9e: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e39b0)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818e39b0-ffffffff818e3a4e: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197ad90)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff8197ad90-ffffffff8197ae2e: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock_fprog *get_compat_bpf_fprog(char *optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d2e0)
Location: net/compat.c:321
Inline: False
Direct callers:
  - net/compat.c:__compat_sys_setsockopt
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff8199d2e0-ffffffff8199d37e: get_compat_bpf_fprog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
