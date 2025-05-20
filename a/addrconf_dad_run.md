# Function: <code>addrconf_dad_run</code>

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
In net/ipv6/addrconf.c (ffffffff817d1c96)
Location: net/ipv6/addrconf.c:3731
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8183f611)
Location: net/ipv6/addrconf.c:3983
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8187120e)
Location: net/ipv6/addrconf.c:4026
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81895e5e)
Location: net/ipv6/addrconf.c:4100
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff819171ac)
Location: net/ipv6/addrconf.c:4102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8196e943)
Location: net/ipv6/addrconf.c:4161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a0080)
Location: net/ipv6/addrconf.c:4181
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff819a0080-ffffffff819a0142: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0c350)
Location: net/ipv6/addrconf.c:4219
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a0c350-ffffffff81a0c411: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a43000)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a43000-ffffffff81a430c1: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b39160)
Location: net/ipv6/addrconf.c:4189
Inline: False
```
**Symbols:**

```
ffffffff81b39160-ffffffff81b39221: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b47e60)
Location: net/ipv6/addrconf.c:4216
Inline: False
```
**Symbols:**

```
ffffffff81b47e60-ffffffff81b47f21: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b35b80)
Location: net/ipv6/addrconf.c:4218
Inline: False
```
**Symbols:**

```
ffffffff81b35b80-ffffffff81b35c41: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfc2e0)
Location: net/ipv6/addrconf.c:4254
Inline: False
```
**Symbols:**

```
ffffffff81bfc2e0-ffffffff81bfc3a1: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d95460)
Location: net/ipv6/addrconf.c:4267
Inline: False
```
**Symbols:**

```
ffffffff81d95460-ffffffff81d95534: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f64460)
Location: net/ipv6/addrconf.c:4276
Inline: False
```
**Symbols:**

```
ffffffff81f64460-ffffffff81f64534: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc3ca0)
Location: net/ipv6/addrconf.c:4282
Inline: False
```
**Symbols:**

```
ffffffff81fc3ca0-ffffffff81fc3d74: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82091250)
Location: net/ipv6/addrconf.c:4333
Inline: False
```
**Symbols:**

```
ffffffff82091250-ffffffff82091324: addrconf_dad_run (STB_LOCAL)
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
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d045b8)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffff800010d045b8-ffff800010d04770: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0ba0c)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
c0e0ba0c-c0e0bac0: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2e520)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
c000000000e2e520-c000000000e2e674: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084d4e2)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffe00084d4e2-ffffffe00084d5ca: addrconf_dad_run (STB_LOCAL)
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
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e2690)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff819e2690-ffffffff819e2751: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199f450)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff8199f450-ffffffff8199f511: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4d110)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a4d110-ffffffff81a4d1d1: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void addrconf_dad_run(struct inet6_dev *idev, bool restart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a59080)
Location: net/ipv6/addrconf.c:4225
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a59080-ffffffff81a5913f: addrconf_dad_run (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
