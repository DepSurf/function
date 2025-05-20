# Function: <code>tcp_bpf_bypass_getsockopt</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d020)
Location: net/ipv4/tcp.c:4237
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81a9d020-ffffffff81a9d039: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b58e90)
Location: net/ipv4/tcp.c:4262
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81b58e90-ffffffff81b58ea9: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce7100)
Location: net/ipv4/tcp.c:4284
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81ce7100-ffffffff81ce7123: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaa800)
Location: net/ipv4/tcp.c:4389
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81eaa800-ffffffff81eaa823: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f08ff0)
Location: net/ipv4/tcp.c:4285
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81f08ff0-ffffffff81f09013: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_bpf_bypass_getsockopt(int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fcd450)
Location: net/ipv4/tcp.c:4353
Inline: False
Direct callers:
  - net/socket.c:do_sock_getsockopt
```
**Symbols:**

```
ffffffff81fcd450-ffffffff81fcd473: tcp_bpf_bypass_getsockopt (STB_GLOBAL)
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
