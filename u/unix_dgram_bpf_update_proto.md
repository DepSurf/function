# Function: <code>unix_dgram_bpf_update_proto</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_dgram_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81beb900)
Location: net/unix/unix_bpf.c:142
Inline: False
```
**Symbols:**

```
ffffffff81beb900-ffffffff81beb9c6: unix_dgram_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_dgram_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81d83d80)
Location: net/unix/unix_bpf.c:141
Inline: False
```
**Symbols:**

```
ffffffff81d83d80-ffffffff81d83e6a: unix_dgram_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_dgram_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81f51590)
Location: net/unix/unix_bpf.c:141
Inline: False
```
**Symbols:**

```
ffffffff81f51590-ffffffff81f5169f: unix_dgram_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_dgram_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81fb0f10)
Location: net/unix/unix_bpf.c:144
Inline: False
```
**Symbols:**

```
ffffffff81fb0f10-ffffffff81fb101f: unix_dgram_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_dgram_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff8207e5b0)
Location: net/unix/unix_bpf.c:144
Inline: False
```
**Symbols:**

```
ffffffff8207e5b0-ffffffff8207e6bf: unix_dgram_bpf_update_proto (STB_GLOBAL)
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
