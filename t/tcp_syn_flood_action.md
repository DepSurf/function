# Function: <code>tcp_syn_flood_action</code>

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
In net/ipv4/tcp_input.c (ffffffff8176dbc6)
Location: net/ipv4/tcp_input.c:6113
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff817dbf2a)
Location: net/ipv4/tcp_input.c:6165
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8180bfe9)
Location: net/ipv4/tcp_input.c:6257
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8182c19c)
Location: net/ipv4/tcp_input.c:6255
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff818ab02c)
Location: net/ipv4/tcp_input.c:6152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819009ca)
Location: net/ipv4/tcp_input.c:6316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8192ea9f)
Location: net/ipv4/tcp_input.c:6367
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8199209c)
Location: net/ipv4/tcp_input.c:6425
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819c4290-ffffffff819c4338: tcp_syn_flood_action (STB_LOCAL)
ffffffff819ceaa6-ffffffff819ceabe: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab19b0)
Location: net/ipv4/tcp_input.c:6540
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81aafbc0-ffffffff81aafc68: tcp_syn_flood_action (STB_LOCAL)
ffffffff81abac5f-ffffffff81abac77: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abc970)
Location: net/ipv4/tcp_input.c:6676
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81aba8d0-ffffffff81aba978: tcp_syn_flood_action (STB_LOCAL)
ffffffff81c32637-ffffffff81c3264f: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6685
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81aa5bb0-ffffffff81aa5c57: tcp_syn_flood_action (STB_LOCAL)
ffffffff81c24924-ffffffff81c2493c: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6720
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81b61f20-ffffffff81b61fc7: tcp_syn_flood_action (STB_LOCAL)
ffffffff81d3a75a-ffffffff81d3a772: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6804
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81cf0b00-ffffffff81cf0bd3: tcp_syn_flood_action (STB_LOCAL)
ffffffff81f06f8e-ffffffff81f06fa6: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb51b0)
Location: net/ipv4/tcp_input.c:6826
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81eb51b0-ffffffff81eb52c3: tcp_syn_flood_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f135e0)
Location: net/ipv4/tcp_input.c:6833
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81f135e0-ffffffff81f136f3: tcp_syn_flood_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7ac0)
Location: net/ipv4/tcp_input.c:6993
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
```
**Symbols:**

```
ffffffff81fd7ac0-ffffffff81fd7bd3: tcp_syn_flood_action (STB_LOCAL)
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
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c78a38)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffff800010c78a38-ffff800010c78b1c: tcp_syn_flood_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86d60)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
c0d86d60-c0d86e4c: tcp_syn_flood_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7ed90)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
c000000000d7ed90-c000000000d7eec4: tcp_syn_flood_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007d9f42)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffe0007d9f42-ffffffe0007da016: tcp_syn_flood_action (STB_LOCAL)
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
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81964100-ffffffff819641a8: tcp_syn_flood_action (STB_LOCAL)
ffffffff8196e916-ffffffff8196e92e: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff8191dbf0-ffffffff8191dc98: tcp_syn_flood_action (STB_LOCAL)
ffffffff81928406-ffffffff8192841e: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819ce8d0-ffffffff819ce978: tcp_syn_flood_action (STB_LOCAL)
ffffffff819d90e6-ffffffff819d90fe: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool tcp_syn_flood_action(const struct sock *sk, const char *proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6481
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819d8460-ffffffff819d8508: tcp_syn_flood_action (STB_LOCAL)
ffffffff819e2d51-ffffffff819e2d69: tcp_syn_flood_action.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
