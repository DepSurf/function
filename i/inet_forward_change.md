# Function: <code>inet_forward_change</code>

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
In net/ipv4/devinet.c (ffffffff81792d56)
Location: net/ipv4/devinet.c:1982
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81800509)
Location: net/ipv4/devinet.c:2014
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81831469)
Location: net/ipv4/devinet.c:2014
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81852a03)
Location: net/ipv4/devinet.c:2059
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff818d2813)
Location: net/ipv4/devinet.c:2068
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81928dc1)
Location: net/ipv4/devinet.c:2078
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff819580b1)
Location: net/ipv4/devinet.c:2233
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff819bcb01)
Location: net/ipv4/devinet.c:2323
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff819f37f1)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_forward_change(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ae10e0)
Location: net/ipv4/devinet.c:2324
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
**Symbols:**

```
ffffffff81ae10e0-ffffffff81ae11c5: inet_forward_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_forward_change(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aedf80)
Location: net/ipv4/devinet.c:2323
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
**Symbols:**

```
ffffffff81aedf80-ffffffff81aee065: inet_forward_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad9801)
Location: net/ipv4/devinet.c:2324
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b98931)
Location: net/ipv4/devinet.c:2325
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d2a7b0)
Location: net/ipv4/devinet.c:2332
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef22c0)
Location: net/ipv4/devinet.c:2333
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f51d90)
Location: net/ipv4/devinet.c:2336
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82018060)
Location: net/ipv4/devinet.c:2366
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffff800010ca9b14)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (c0db6288)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (c000000000dbf070)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffe000804628)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81993591)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff8194d051)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff819fde31)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
In net/ipv4/devinet.c (ffffffff81a081c1)
Location: net/ipv4/devinet.c:2318
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
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
</ul>
