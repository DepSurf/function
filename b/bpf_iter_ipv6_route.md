# Function: <code>bpf_iter_ipv6_route</code>

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
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82d2f9bc)
Location: net/ipv6/route.c:6424
Inline: False
```
**Symbols:**

```
ffffffff82d2f9bc-ffffffff82d2f9c9: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8301e5ab)
Location: net/ipv6/route.c:6408
Inline: False
```
**Symbols:**

```
ffffffff8301e5ab-ffffffff8301e5b8: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8322969e)
Location: net/ipv6/route.c:6479
Inline: False
```
**Symbols:**

```
ffffffff8322969e-ffffffff832296ab: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff83313ca9)
Location: net/ipv6/route.c:6639
Inline: False
```
**Symbols:**

```
ffffffff83313ca9-ffffffff83313cb6: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff834ce041)
Location: net/ipv6/route.c:6632
Inline: False
```
**Symbols:**

```
ffffffff834ce041-ffffffff834ce052: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff83f11160)
Location: net/ipv6/route.c:6639
Inline: False
```
**Symbols:**

```
ffffffff83f11160-ffffffff83f11171: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff837377b0)
Location: net/ipv6/route.c:6637
Inline: False
```
**Symbols:**

```
ffffffff837377b0-ffffffff837377c1: bpf_iter_ipv6_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_ipv6_route(struct bpf_iter_meta *meta, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8396be60)
Location: net/ipv6/route.c:6639
Inline: False
```
**Symbols:**

```
ffffffff8396be60-ffffffff8396be71: bpf_iter_ipv6_route (STB_GLOBAL)
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
