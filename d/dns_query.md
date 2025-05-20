# Function: <code>dns_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff81816bc0)
Location: net/dns_resolver/dns_query.c:69
Inline: False
```
**Symbols:**

```
ffffffff81816bc0-ffffffff81816e8c: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff81889a70)
Location: net/dns_resolver/dns_query.c:69
Inline: False
```
**Symbols:**

```
ffffffff81889a70-ffffffff81889d20: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff818be280)
Location: net/dns_resolver/dns_query.c:69
Inline: False
```
**Symbols:**

```
ffffffff818be280-ffffffff818be530: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff818e4bd0)
Location: net/dns_resolver/dns_query.c:71
Inline: False
```
**Symbols:**

```
ffffffff818e4bd0-ffffffff818e4e70: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff8196aa00)
Location: net/dns_resolver/dns_query.c:71
Inline: False
```
**Symbols:**

```
ffffffff8196aa00-ffffffff8196aca3: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:71
Inline: False
```
**Symbols:**

```
ffffffff819c46a3-ffffffff819c472f: dns_query.cold.1 (STB_LOCAL)
ffffffff819c4490-ffffffff819c46a3: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dns_query(const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:71
Inline: False
```
**Symbols:**

```
ffffffff819fbb3d-ffffffff819fbbc9: dns_query.cold.1 (STB_LOCAL)
ffffffff819fb940-ffffffff819fbb3d: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81a6b23b-ffffffff81a6b2ce: dns_query.cold (STB_LOCAL)
ffffffff81a6b010-ffffffff81a6b23b: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81aa1c2b-ffffffff81aa1cbe: dns_query.cold (STB_LOCAL)
ffffffff81aa1a00-ffffffff81aa1c2b: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81b9d5f0-ffffffff81b9d683: dns_query.cold (STB_LOCAL)
ffffffff81b9d3a0-ffffffff81b9d5f0: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81c336fa-ffffffff81c3378d: dns_query.cold (STB_LOCAL)
ffffffff81bacd60-ffffffff81bacf9e: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81c25a1d-ffffffff81c25ab0: dns_query.cold (STB_LOCAL)
ffffffff81b9bff0-ffffffff81b9c22e: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81d421ec-ffffffff81d4227f: dns_query.cold (STB_LOCAL)
ffffffff81c68f50-ffffffff81c6918e: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81f0eb55-ffffffff81f0ebe2: dns_query.cold (STB_LOCAL)
ffffffff81e0c1a0-ffffffff81e0c3c6: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff81fe21a0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81fe21a0-ffffffff81fe245a: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff8205e440)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff8205e440-ffffffff8205e774: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffff82131120)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff82131120-ffffffff82131454: dns_query (STB_GLOBAL)
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
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffff800010d72f60)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffff800010d72f60-ffff800010d7320c: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (c0e6fe0c)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
c0e6fe0c-c0e700d8: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (c000000000eb2150)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
c000000000eb2150-c000000000eb2510: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dns_resolver/dns_query.c (ffffffe0008a33ec)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffe0008a33ec-ffffffe0008a363a: dns_query (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81a40fbb-ffffffff81a4104e: dns_query.cold (STB_LOCAL)
ffffffff81a40d90-ffffffff81a40fbb: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff819fdbab-ffffffff819fdc3e: dns_query.cold (STB_LOCAL)
ffffffff819fd980-ffffffff819fdbab: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81aace6b-ffffffff81aacefe: dns_query.cold (STB_LOCAL)
ffffffff81aacc40-ffffffff81aace6b: dns_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dns_query(struct net *net, const char *type, const char *name, size_t namelen, const char *options, char **_result, time64_t *_expiry, bool invalidate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/dns_resolver/dns_query.c (0)
Location: net/dns_resolver/dns_query.c:74
Inline: False
```
**Symbols:**

```
ffffffff81ab91db-ffffffff81ab926e: dns_query.cold (STB_LOCAL)
ffffffff81ab8fb0-ffffffff81ab91db: dns_query (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>bool invalidate</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, name, namelen, options, _result, _expiry</code> ➡️ <code>net, type, name, namelen, options, _result, _expiry, invalidate</code>
</li>
</ul>
</details>
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
