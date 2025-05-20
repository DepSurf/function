# Function: <code>bpf_iter_init_tcp</code>

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
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0340)
Location: net/ipv4/tcp_ipv4.c:2973
Inline: False
```
**Symbols:**

```
ffffffff81ad0340-ffffffff81ad03be: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abb4b0)
Location: net/ipv4/tcp_ipv4.c:2995
Inline: False
```
**Symbols:**

```
ffffffff81abb4b0-ffffffff81abb52e: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b79a60)
Location: net/ipv4/tcp_ipv4.c:3250
Inline: True
```
**Symbols:**

```
ffffffff81b79a60-ffffffff81b79aa2: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d09470)
Location: net/ipv4/tcp_ipv4.c:3194
Inline: True
```
**Symbols:**

```
ffffffff81d09470-ffffffff81d094b9: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ece700)
Location: net/ipv4/tcp_ipv4.c:3305
Inline: True
```
**Symbols:**

```
ffffffff81ece700-ffffffff81ece749: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d370)
Location: net/ipv4/tcp_ipv4.c:3315
Inline: True
```
**Symbols:**

```
ffffffff81f2d370-ffffffff81f2d3b9: bpf_iter_init_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_tcp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2210)
Location: net/ipv4/tcp_ipv4.c:3522
Inline: True
```
**Symbols:**

```
ffffffff81ff2210-ffffffff81ff2259: bpf_iter_init_tcp (STB_LOCAL)
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
