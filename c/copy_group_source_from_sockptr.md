# Function: <code>copy_group_source_from_sockptr</code>

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
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aaae00)
Location: net/ipv4/ip_sockglue.c:698
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5f730)
Location: net/ipv6/ipv6_sockglue.c:139
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81aaae00-ffffffff81aab0d0: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81b5f730-ffffffff81b5fa00: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a95570)
Location: net/ipv4/ip_sockglue.c:698
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4cc20)
Location: net/ipv6/ipv6_sockglue.c:139
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81a95570-ffffffff81a95840: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81b4cc20-ffffffff81b4cef0: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b509d0)
Location: net/ipv4/ip_sockglue.c:697
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13f30)
Location: net/ipv6/ipv6_sockglue.c:139
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81b509d0-ffffffff81b50ca0: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81c13f30-ffffffff81c14200: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdf000)
Location: net/ipv4/ip_sockglue.c:699
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81daf6d0)
Location: net/ipv6/ipv6_sockglue.c:141
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81cdf000-ffffffff81cdf2ed: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81daf6d0-ffffffff81daf9b9: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9f4b0)
Location: net/ipv4/ip_sockglue.c:700
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7ef00)
Location: net/ipv6/ipv6_sockglue.c:141
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81e9f4b0-ffffffff81e9f79b: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81f7ef00-ffffffff81f7f1e9: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efdc90)
Location: net/ipv4/ip_sockglue.c:707
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdf140)
Location: net/ipv6/ipv6_sockglue.c:141
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81efdc90-ffffffff81efdf7b: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff81fdf140-ffffffff81fdf429: copy_group_source_from_sockptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req *greqs, sockptr_t optval, int optlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc1e70)
Location: net/ipv4/ip_sockglue.c:698
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820acf50)
Location: net/ipv6/ipv6_sockglue.c:141
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81fc1e70-ffffffff81fc215b: copy_group_source_from_sockptr (STB_LOCAL)
ffffffff820acf50-ffffffff820ad239: copy_group_source_from_sockptr (STB_LOCAL)
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
