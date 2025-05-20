# Function: <code>bpf_iter_tcp</code>

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
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8301cdba)
Location: net/ipv4/tcp_ipv4.c:2970
Inline: False
```
**Symbols:**

```
ffffffff8301cdba-ffffffff8301cdc7: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff83227ea9)
Location: net/ipv4/tcp_ipv4.c:2992
Inline: False
```
**Symbols:**

```
ffffffff83227ea9-ffffffff83227eb6: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff833122c4)
Location: net/ipv4/tcp_ipv4.c:3245
Inline: False
```
**Symbols:**

```
ffffffff833122c4-ffffffff833122d1: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff834cc252)
Location: net/ipv4/tcp_ipv4.c:3189
Inline: False
```
**Symbols:**

```
ffffffff834cc252-ffffffff834cc263: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff83f0eb10)
Location: net/ipv4/tcp_ipv4.c:3300
Inline: False
```
**Symbols:**

```
ffffffff83f0eb10-ffffffff83f0eb21: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff83735120)
Location: net/ipv4/tcp_ipv4.c:3310
Inline: False
```
**Symbols:**

```
ffffffff83735120-ffffffff83735131: bpf_iter_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_tcp(struct bpf_iter_meta *meta, struct sock_common *sk_common, uid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff839696e0)
Location: net/ipv4/tcp_ipv4.c:3517
Inline: False
```
**Symbols:**

```
ffffffff839696e0-ffffffff839696f1: bpf_iter_tcp (STB_GLOBAL)
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
