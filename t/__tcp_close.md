# Function: <code>__tcp_close</code>

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
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab8190)
Location: net/ipv4/tcp.c:2655
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81ab8190-ffffffff81ab8610: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa34c0)
Location: net/ipv4/tcp.c:2709
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81aa34c0-ffffffff81aa390a: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5f660)
Location: net/ipv4/tcp.c:2734
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81b5f660-ffffffff81b5fab6: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cee0d0)
Location: net/ipv4/tcp.c:2762
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81cee0d0-ffffffff81cee564: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb13a0)
Location: net/ipv4/tcp.c:2862
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81eb13a0-ffffffff81eb179c: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0fa30)
Location: net/ipv4/tcp.c:2748
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81f0fa30-ffffffff81f0fe2c: __tcp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tcp_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd3c20)
Location: net/ipv4/tcp.c:2760
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81fd3c20-ffffffff81fd4025: __tcp_close (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
