# Function: <code>tcp_bpf_clone</code>

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
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b09c50)
Location: net/ipv4/tcp_bpf.c:623
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81b09c50-ffffffff81b09c8a: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b18050)
Location: net/ipv4/tcp_bpf.c:624
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81b18050-ffffffff81b1808a: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b05b20)
Location: net/ipv4/tcp_bpf.c:545
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81b05b20-ffffffff81b05b5a: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc8680)
Location: net/ipv4/tcp_bpf.c:634
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81bc8680-ffffffff81bc86ba: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5dd60)
Location: net/ipv4/tcp_bpf.c:632
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81d5dd60-ffffffff81d5ddb5: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f28370)
Location: net/ipv4/tcp_bpf.c:641
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81f28370-ffffffff81f283a4: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f87ec0)
Location: net/ipv4/tcp_bpf.c:679
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81f87ec0-ffffffff81f87ef4: tcp_bpf_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_bpf_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204f5e0)
Location: net/ipv4/tcp_bpf.c:693
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff8204f5e0-ffffffff8204f614: tcp_bpf_clone (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
