# Function: <code>calipso_cache_check</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81870629)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a3599)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c9b65)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194d245)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a59f5)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dcb65)
Location: net/ipv6/calipso.c:210
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4b7a2)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a82372)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7c4e0)
Location: net/ipv6/calipso.c:196
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81b7c4e0-ffffffff81b7c6a8: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8b520)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81b8b520-ffffffff81b8b6e8: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7a370)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81b7a370-ffffffff81b7a534: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c45030)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81c45030-ffffffff81c451f4: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de40b0)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81de40b0-ffffffff81de4276: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb67c0)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff81fb67c0-ffffffff81fb6984: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82016ed0)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff82016ed0-ffffffff82017090: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calipso_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e5e70)
Location: net/ipv6/calipso.c:199
Inline: False
Direct callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff820e5e70-ffffffff820e6030: calipso_cache_check (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4e658)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4ef78)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e84e60)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000886d5e)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a21a02)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819de7c2)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8c482)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a99213)
Location: net/ipv6/calipso.c:196
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
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
