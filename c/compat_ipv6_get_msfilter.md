# Function: <code>compat_ipv6_get_msfilter</code>

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
int compat_ipv6_get_msfilter(struct sock *sk, void *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5e240)
Location: net/ipv6/ipv6_sockglue.c:1077
Inline: False
```
**Symbols:**

```
ffffffff81b5e240-ffffffff81b5e471: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, void *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4c4c0)
Location: net/ipv6/ipv6_sockglue.c:1077
Inline: False
```
**Symbols:**

```
ffffffff81b4c4c0-ffffffff81b4c6ef: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, void *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81c137d0)
Location: net/ipv6/ipv6_sockglue.c:1077
Inline: False
```
**Symbols:**

```
ffffffff81c137d0-ffffffff81c139ff: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, void *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81daee40)
Location: net/ipv6/ipv6_sockglue.c:1095
Inline: False
```
**Symbols:**

```
ffffffff81daee40-ffffffff81daf0c5: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7f320)
Location: net/ipv6/ipv6_sockglue.c:1097
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff81f7f320-ffffffff81f7f64c: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdf560)
Location: net/ipv6/ipv6_sockglue.c:1086
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff81fdf560-ffffffff81fdf88a: compat_ipv6_get_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ipv6_get_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff820ad370)
Location: net/ipv6/ipv6_sockglue.c:1066
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff820ad370-ffffffff820ad69a: compat_ipv6_get_msfilter (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int len</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *optlen</code> ➡️ <code>sockptr_t optlen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
