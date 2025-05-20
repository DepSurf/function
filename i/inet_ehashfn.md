# Function: <code>inet_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81761ef0)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
**Symbols:**

```
ffffffff81761ef0-ffffffff81761ff3: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce200)
Location: net/ipv4/inet_hashtables.c:30
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff817ce200-ffffffff817ce2fd: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fdfa0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff817fdfa0-ffffffff817fe09d: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181e3c0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff8181e3c0-ffffffff8181e4c2: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189d2c0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff8189d2c0-ffffffff8189d3cd: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1910)
Location: net/ipv4/inet_hashtables.c:32
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff818f1910-ffffffff818f1a11: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f4f0)
Location: net/ipv4/inet_hashtables.c:32
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff8191f4f0-ffffffff8191f5f1: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81981e60)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81981e60-ffffffff81981f60: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b86b0)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff819b86b0-ffffffff819b87b3: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3170)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
**Symbols:**

```
ffffffff81aa3170-ffffffff81aa3273: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aad6a0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81aad6a0-ffffffff81aad7a3: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98770)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
**Symbols:**

```
ffffffff81a98770-ffffffff81a98877: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b53c50)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81b53c50-ffffffff81b53d57: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce1810)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81ce1810-ffffffff81ce192e: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea29c0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81ea29c0-ffffffff81ea2ade: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f011e0)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81f011e0-ffffffff81f012fe: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5490)
Location: net/ipv4/inet_hashtables.c:31
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81fc5490-ffffffff81fc55ae: inet_ehashfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69ad8)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffff800010c69ad8-ffff800010c69c18: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d78dbc)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
c0d78dbc-c0d78edc: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6ea80)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
c000000000d6ea80-c000000000d6ec10: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cf940)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffe0007cf940-ffffffe0007cfa58: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958520)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81958520-ffffffff81958623: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912010)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff81912010-ffffffff81912113: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c2cf0)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff819c2cf0-ffffffff819c2df3: inet_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cc7c0)
Location: net/ipv4/inet_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
**Symbols:**

```
ffffffff819cc7c0-ffffffff819cc8c3: inet_ehashfn (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
