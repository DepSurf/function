# Function: <code>cipso_v4_cache_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff817ae830)
Location: net/ipv4/cipso_ipv4.c:318
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff8181b760)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff8184d020)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81870a80)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff818f1460)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81947d90)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81979a10)
Location: net/ipv4/cipso_ipv4.c:248
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff819e3510)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81a1a500)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81b0a0a0)
Location: net/ipv4/cipso_ipv4.c:236
Inline: False
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_getattr
```
**Symbols:**

```
ffffffff81b0a0a0-ffffffff81b0a268: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81b18460)
Location: net/ipv4/cipso_ipv4.c:236
Inline: False
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_getattr
```
**Symbols:**

```
ffffffff81b18460-ffffffff81b18628: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81b061b0)
Location: net/ipv4/cipso_ipv4.c:236
Inline: False
```
**Symbols:**

```
ffffffff81b061b0-ffffffff81b06374: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81bc8ea0)
Location: net/ipv4/cipso_ipv4.c:235
Inline: False
```
**Symbols:**

```
ffffffff81bc8ea0-ffffffff81bc9064: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81d5e650)
Location: net/ipv4/cipso_ipv4.c:235
Inline: False
```
**Symbols:**

```
ffffffff81d5e650-ffffffff81d5e816: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81f28d70)
Location: net/ipv4/cipso_ipv4.c:235
Inline: False
```
**Symbols:**

```
ffffffff81f28d70-ffffffff81f28f34: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff81f888e0)
Location: net/ipv4/cipso_ipv4.c:235
Inline: False
```
**Symbols:**

```
ffffffff81f888e0-ffffffff81f88aa0: cipso_v4_cache_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cipso_v4_cache_check(const unsigned char *key, u32 key_len, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/cipso_ipv4.c (ffffffff8204ffa0)
Location: net/ipv4/cipso_ipv4.c:233
Inline: False
```
**Symbols:**

```
ffffffff8204ffa0-ffffffff82050160: cipso_v4_cache_check (STB_LOCAL)
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
In net/ipv4/cipso_ipv4.c (ffff800010cd6468)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (c0de0280)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (c000000000df5ffc)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffe000826eea)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff819b9b90)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81976980)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81a24610)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
In net/ipv4/cipso_ipv4.c (ffffffff81a2fa60)
Location: net/ipv4/cipso_ipv4.c:234
Inline: True
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
