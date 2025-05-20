# Function: <code>fib6_ifdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib6_ifdown(struct rt6_info *rt, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3230)
Location: net/ipv6/route.c:2603
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_ifdown
```
**Symbols:**

```
ffffffff817d3230-ffffffff817d3260: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib6_ifdown(struct rt6_info *rt, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81840c30)
Location: net/ipv6/route.c:2657
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_ifdown
```
**Symbols:**

```
ffffffff81840c30-ffffffff81840c60: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib6_ifdown(struct rt6_info *rt, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872900)
Location: net/ipv6/route.c:2714
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_ifdown
```
**Symbols:**

```
ffffffff81872900-ffffffff81872930: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fib6_ifdown(struct rt6_info *rt, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81898960)
Location: net/ipv6/route.c:2797
Inline: True
```
**Symbols:**

```
ffffffff81898960-ffffffff818989c1: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fib6_ifdown(struct rt6_info *rt, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81919ca0)
Location: net/ipv6/route.c:3501
Inline: True
```
**Symbols:**

```
ffffffff81919ca0-ffffffff81919d01: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81971ce0)
Location: net/ipv6/route.c:4024
Inline: False
```
**Symbols:**

```
ffffffff81971ce0-ffffffff81971ecb: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7430)
Location: net/ipv6/route.c:4003
Inline: False
```
**Symbols:**

```
ffffffff819a7430-ffffffff819a761e: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a13a50)
Location: net/ipv6/route.c:4668
Inline: False
```
**Symbols:**

```
ffffffff81a13a50-ffffffff81a13c52: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4a640)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffff81a4a640-ffffffff81a4a842: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44af0)
Location: net/ipv6/route.c:4722
Inline: False
```
**Symbols:**

```
ffffffff81b44af0-ffffffff81b44cd2: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52f00)
Location: net/ipv6/route.c:4706
Inline: False
```
**Symbols:**

```
ffffffff81b52f00-ffffffff81b530e2: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40890)
Location: net/ipv6/route.c:4721
Inline: False
```
**Symbols:**

```
ffffffff81b40890-ffffffff81b40a72: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c06ec0)
Location: net/ipv6/route.c:4851
Inline: False
```
**Symbols:**

```
ffffffff81c06ec0-ffffffff81c070a2: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da1a40)
Location: net/ipv6/route.c:4838
Inline: False
```
**Symbols:**

```
ffffffff81da1a40-ffffffff81da1c1f: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f70db0)
Location: net/ipv6/route.c:4838
Inline: False
```
**Symbols:**

```
ffffffff81f70db0-ffffffff81f70f8f: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd0ea0)
Location: net/ipv6/route.c:4836
Inline: False
```
**Symbols:**

```
ffffffff81fd0ea0-ffffffff81fd107e: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209e790)
Location: net/ipv6/route.c:4836
Inline: False
```
**Symbols:**

```
ffffffff8209e790-ffffffff8209e96e: fib6_ifdown (STB_LOCAL)
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
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0d718)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffff800010d0d718-ffff800010d0d938: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e13f80)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
c0e13f80-c0e141a8: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e393f0)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
c000000000e393f0-c000000000e396b0: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000855490)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffe000855490-ffffffe000855618: fib6_ifdown (STB_LOCAL)
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
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9cd0)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffff819e9cd0-ffffffff819e9ed2: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6a90)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffff819a6a90-ffffffff819a6c92: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a54750)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffff81a54750-ffffffff81a54952: fib6_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib6_ifdown(struct fib6_info *rt, void *p_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a60740)
Location: net/ipv6/route.c:4681
Inline: False
```
**Symbols:**

```
ffffffff81a60740-ffffffff81a60942: fib6_ifdown (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *p_arg</code>
</li>
<li>
<b>Param removed. </b>
<code>void *arg</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
</ul>
</details>
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
