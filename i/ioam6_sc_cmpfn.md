# Function: <code>ioam6_sc_cmpfn</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ioam6_sc_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81c3a1f7)
Location: net/ipv6/ioam6.c:54
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
```
**Symbols:**

```
ffffffff81c38ad0-ffffffff81c38aea: ioam6_sc_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ioam6_sc_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81dd7b7d)
Location: net/ipv6/ioam6.c:56
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
```
**Symbols:**

```
ffffffff81dd6750-ffffffff81dd6774: ioam6_sc_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ioam6_sc_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81fa955d)
Location: net/ipv6/ioam6.c:56
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
```
**Symbols:**

```
ffffffff81fa8050-ffffffff81fa8074: ioam6_sc_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ioam6_sc_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff82009edd)
Location: net/ipv6/ioam6.c:56
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
```
**Symbols:**

```
ffffffff820089e0-ffffffff82008a04: ioam6_sc_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ioam6_sc_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff820d8e7d)
Location: net/ipv6/ioam6.c:56
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
```
**Symbols:**

```
ffffffff820d7900-ffffffff820d7924: ioam6_sc_cmpfn (STB_LOCAL)
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
