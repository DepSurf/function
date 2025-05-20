# Function: <code>bictcp_update</code>

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
In net/ipv4/tcp_cubic.c (ffffffff817ac68e)
Location: net/ipv4/tcp_cubic.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81819bee)
Location: net/ipv4/tcp_cubic.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff8184b4ae)
Location: net/ipv4/tcp_cubic.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff8186ef1e)
Location: net/ipv4/tcp_cubic.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff818ef8ae)
Location: net/ipv4/tcp_cubic.c:224
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81946263)
Location: net/ipv4/tcp_cubic.c:224
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81976403)
Location: net/ipv4/tcp_cubic.c:224
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff819e00f0)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81a16f80)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b07ff0)
Location: net/ipv4/tcp_cubic.c:221
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
**Symbols:**

```
ffffffff81b07ff0-ffffffff81b0823f: bictcp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b163d0)
Location: net/ipv4/tcp_cubic.c:221
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
**Symbols:**

```
ffffffff81b163d0-ffffffff81b1661f: bictcp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b041b0)
Location: net/ipv4/tcp_cubic.c:212
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff81b041b0-ffffffff81b043ff: bictcp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cubic.c (0)
Location: net/ipv4/tcp_cubic.c:212
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff81bc64f0-ffffffff81bc67f0: bictcp_update (STB_LOCAL)
ffffffff81d3ecb9-ffffffff81d3ecdd: bictcp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cubic.c (0)
Location: net/ipv4/tcp_cubic.c:214
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff81d5b850-ffffffff81d5bb6c: bictcp_update (STB_LOCAL)
ffffffff81f0b5ea-ffffffff81f0b60e: bictcp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cubic.c (0)
Location: net/ipv4/tcp_cubic.c:214
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff81f25d20-ffffffff81f2603c: bictcp_update (STB_LOCAL)
ffffffff820b2e6f-ffffffff820b2e93: bictcp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cubic.c (0)
Location: net/ipv4/tcp_cubic.c:214
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff81f85620-ffffffff81f8593c: bictcp_update (STB_LOCAL)
ffffffff82134017-ffffffff8213403b: bictcp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bictcp_update(struct bictcp *ca, u32 cwnd, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cubic.c (0)
Location: net/ipv4/tcp_cubic.c:214
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_cong_avoid
```
**Symbols:**

```
ffffffff8204bcf0-ffffffff8204c010: bictcp_update (STB_LOCAL)
ffffffff822159f9-ffffffff82215a1d: bictcp_update.cold (STB_LOCAL)
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
In net/ipv4/tcp_cubic.c (ffff800010cd29b4)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (c0ddcd18)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (c000000000df1348)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffe000823eca)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff819b6610)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81973400)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81a21090)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
In net/ipv4/tcp_cubic.c (ffffffff81a2c3c6)
Location: net/ipv4/tcp_cubic.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
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
