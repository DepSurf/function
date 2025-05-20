# Function: <code>udp_sysctl_init</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191a7a0)
Location: net/ipv4/udp.c:2909
Inline: False
```
**Symbols:**

```
ffffffff8191a7a0-ffffffff8191a7c8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81948f50)
Location: net/ipv4/udp.c:3025
Inline: False
```
**Symbols:**

```
ffffffff81948f50-ffffffff81948f78: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ad5a0)
Location: net/ipv4/udp.c:3010
Inline: False
```
**Symbols:**

```
ffffffff819ad5a0-ffffffff819ad5c8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e4250)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffff819e4250-ffffffff819e4278: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad19a0)
Location: net/ipv4/udp.c:3063
Inline: False
```
**Symbols:**

```
ffffffff81ad19a0-ffffffff81ad19c8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81add9d0)
Location: net/ipv4/udp.c:3173
Inline: False
```
**Symbols:**

```
ffffffff81add9d0-ffffffff81add9f2: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac8aa0)
Location: net/ipv4/udp.c:3244
Inline: False
```
**Symbols:**

```
ffffffff81ac8aa0-ffffffff81ac8ac5: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b87320)
Location: net/ipv4/udp.c:3259
Inline: False
```
**Symbols:**

```
ffffffff81b87320-ffffffff81b87345: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d18050)
Location: net/ipv4/udp.c:3274
Inline: False
```
**Symbols:**

```
ffffffff81d18050-ffffffff81d1807b: udp_sysctl_init (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81edfbf5)
Location: net/ipv4/udp.c:3305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
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
In net/ipv4/udp.c (ffffffff81f3f035)
Location: net/ipv4/udp.c:3451
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
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
In net/ipv4/udp.c (ffffffff82005305)
Location: net/ipv4/udp.c:3440
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
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
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c98d60)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffff800010c98d60-ffff800010c98d94: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da6aac)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
c0da6aac-c0da6adc: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daa490)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
c000000000daa490-c000000000daa4bc: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f6ce2)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffe0007f6ce2-ffffffe0007f6d14: udp_sysctl_init (STB_LOCAL)
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
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819840c0)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffff819840c0-ffffffff819840e8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193db80)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffff8193db80-ffffffff8193dba8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ee890)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffff819ee890-ffffffff819ee8b8: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_sysctl_init(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f88f0)
Location: net/ipv4/udp.c:3046
Inline: False
```
**Symbols:**

```
ffffffff819f88f0-ffffffff819f8918: udp_sysctl_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
