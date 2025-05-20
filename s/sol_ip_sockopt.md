# Function: <code>sol_ip_sockopt</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sol_ip_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df1be0)
Location: net/core/filter.c:5228
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81df1be0-ffffffff81df1c8c: sol_ip_sockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sol_ip_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63b70)
Location: net/core/filter.c:5282
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81e63b70-ffffffff81e63c1c: sol_ip_sockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sol_ip_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22d50)
Location: net/core/filter.c:5356
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81f22d50-ffffffff81f22dfc: sol_ip_sockopt (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
