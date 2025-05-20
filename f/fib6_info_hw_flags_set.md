# Function: <code>fib6_info_hw_flags_set</code>

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
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41920)
Location: net/ipv6/route.c:6067
Inline: False
```
**Symbols:**

```
ffffffff81b41920-ffffffff81b41aa8: fib6_info_hw_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c09680)
Location: net/ipv6/route.c:6226
Inline: False
```
**Symbols:**

```
ffffffff81c09680-ffffffff81c097d7: fib6_info_hw_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da4800)
Location: net/ipv6/route.c:6219
Inline: False
```
**Symbols:**

```
ffffffff81da4800-ffffffff81da498b: fib6_info_hw_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f73ca0)
Location: net/ipv6/route.c:6220
Inline: False
```
**Symbols:**

```
ffffffff81f73ca0-ffffffff81f73e2b: fib6_info_hw_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd3d80)
Location: net/ipv6/route.c:6218
Inline: False
```
**Symbols:**

```
ffffffff81fd3d80-ffffffff81fd3f0b: fib6_info_hw_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib6_info_hw_flags_set(struct net *net, struct fib6_info *f6i, bool offload, bool trap, bool offload_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a1690)
Location: net/ipv6/route.c:6211
Inline: False
```
**Symbols:**

```
ffffffff820a1690-ffffffff820a181b: fib6_info_hw_flags_set (STB_GLOBAL)
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
