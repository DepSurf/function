# Function: <code>__xfrm6_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff817fc7e0)
Location: net/ipv6/xfrm6_state.c:60
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
```
**Symbols:**

```
ffffffff817fc7e0-ffffffff817fc903: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff8186c100)
Location: net/ipv6/xfrm6_state.c:60
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff8186c100-ffffffff8186c223: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff8189ef10)
Location: net/ipv6/xfrm6_state.c:60
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff8189ef10-ffffffff8189f033: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff818c5470)
Location: net/ipv6/xfrm6_state.c:60
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff818c5470-ffffffff818c55bf: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff81948740)
Location: net/ipv6/xfrm6_state.c:61
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff81948740-ffffffff81948892: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff819a1730)
Location: net/ipv6/xfrm6_state.c:61
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff819a1730-ffffffff819a1851: __xfrm6_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __xfrm6_sort(void **dst, void **src, int n, int (*cmp)(void *), int maxclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_state.c (ffffffff819d8360)
Location: net/ipv6/xfrm6_state.c:61
Inline: False
Direct callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_tmpl_sort
  - net/ipv6/xfrm6_state.c:__xfrm6_state_sort
```
**Symbols:**

```
ffffffff819d8360-ffffffff819d8481: __xfrm6_sort (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
