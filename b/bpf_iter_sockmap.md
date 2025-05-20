# Function: <code>bpf_iter_sockmap</code>

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
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8301c121)
Location: net/core/sock_map.c:725
Inline: False
```
**Symbols:**

```
ffffffff8301c121-ffffffff8301c12e: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8322728f)
Location: net/core/sock_map.c:717
Inline: False
```
**Symbols:**

```
ffffffff8322728f-ffffffff8322729c: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8331162f)
Location: net/core/sock_map.c:708
Inline: False
```
**Symbols:**

```
ffffffff8331162f-ffffffff8331163c: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff834cb43c)
Location: net/core/sock_map.c:702
Inline: False
```
**Symbols:**

```
ffffffff834cb43c-ffffffff834cb44d: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff83f0d820)
Location: net/core/sock_map.c:704
Inline: False
```
**Symbols:**

```
ffffffff83f0d820-ffffffff83f0d831: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff83733e10)
Location: net/core/sock_map.c:700
Inline: False
```
**Symbols:**

```
ffffffff83733e10-ffffffff83733e21: bpf_iter_sockmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_sockmap(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff83968350)
Location: net/core/sock_map.c:704
Inline: False
```
**Symbols:**

```
ffffffff83968350-ffffffff83968361: bpf_iter_sockmap (STB_GLOBAL)
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
