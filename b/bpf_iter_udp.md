# Function: <code>bpf_iter_udp</code>

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
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8301d040)
Location: net/ipv4/udp.c:3184
Inline: False
```
**Symbols:**

```
ffffffff8301d040-ffffffff8301d04d: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff83228128)
Location: net/ipv4/udp.c:3255
Inline: False
```
**Symbols:**

```
ffffffff83228128-ffffffff83228135: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff83312543)
Location: net/ipv4/udp.c:3270
Inline: False
```
**Symbols:**

```
ffffffff83312543-ffffffff83312550: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff834cc61a)
Location: net/ipv4/udp.c:3285
Inline: False
```
**Symbols:**

```
ffffffff834cc61a-ffffffff834cc62b: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff83f0f040)
Location: net/ipv4/udp.c:3413
Inline: False
```
**Symbols:**

```
ffffffff83f0f040-ffffffff83f0f051: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff83735650)
Location: net/ipv4/udp.c:3559
Inline: False
```
**Symbols:**

```
ffffffff83735650-ffffffff83735661: bpf_iter_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_udp(struct bpf_iter_meta *meta, struct udp_sock *udp_sk, uid_t uid, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff83969cc0)
Location: net/ipv4/udp.c:3548
Inline: False
```
**Symbols:**

```
ffffffff83969cc0-ffffffff83969cd1: bpf_iter_udp (STB_GLOBAL)
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
