# Function: <code>tcp_ca_find</code>

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
In net/ipv4/tcp_cong.c (ffffffff8178036c)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff817ee01d)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff8181e9bd)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff8183f2e3)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff818bea43)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff81914633)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff81942de3)
Location: net/ipv4/tcp_cong.c:23
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff819a73b9)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff819de079)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81acb46e)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81acace0-ffffffff81acad35: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ad7495)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81ad6c90-ffffffff81ad6ce5: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ac257d)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81ac1d20-ffffffff81ac1d79: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81b80313)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81b7fa40-ffffffff81b7fa99: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81d1055f)
Location: net/ipv4/tcp_cong.c:25
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81d0fb20-ffffffff81d0fb86: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ed627f)
Location: net/ipv4/tcp_cong.c:25
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
Direct callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
```
**Symbols:**

```
ffffffff81ed5770-ffffffff81ed57d6: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f3519f)
Location: net/ipv4/tcp_cong.c:25
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81f34450-ffffffff81f344b6: tcp_ca_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tcp_congestion_ops *tcp_ca_find(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffb31f)
Location: net/ipv4/tcp_cong.c:25
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81ffa5d0-ffffffff81ffa636: tcp_ca_find (STB_GLOBAL)
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
In net/ipv4/tcp_cong.c (ffff800010c91660)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (c0da0260)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (c000000000da11e8)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffe0007f1354)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff8197dee9)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff819379a9)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff819e86b9)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
In net/ipv4/tcp_cong.c (ffffffff819f241e)
Location: net/ipv4/tcp_cong.c:24
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
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
