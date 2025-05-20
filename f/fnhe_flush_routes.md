# Function: <code>fnhe_flush_routes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81753240)
Location: net/ipv4/route.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_set_nexthop
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81753240-ffffffff8175328a: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817bf3d0)
Location: net/ipv4/route.c:575
Inline: False
Direct callers:
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff817bf3d0-ffffffff817bf41a: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817eed20)
Location: net/ipv4/route.c:578
Inline: False
Direct callers:
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff817eed20-ffffffff817eed6a: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180eea0)
Location: net/ipv4/route.c:594
Inline: False
Direct callers:
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff8180eea0-ffffffff8180eef6: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188e460)
Location: net/ipv4/route.c:597
Inline: False
Direct callers:
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff8188e460-ffffffff8188e4b6: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e2180)
Location: net/ipv4/route.c:580
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff818e2180-ffffffff818e21d6: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190f020)
Location: net/ipv4/route.c:580
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff8190f020-ffffffff8190f076: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81970af0)
Location: net/ipv4/route.c:588
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81970af0-ffffffff81970b46: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a74f0)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff819a74f0-ffffffff819a7546: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a935f6)
Location: net/ipv4/route.c:588
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9d4a6)
Location: net/ipv4/route.c:588
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81a881f6)
Location: net/ipv4/route.c:571
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81b42c96)
Location: net/ipv4/route.c:572
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81ccf6f4)
Location: net/ipv4/route.c:575
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81e8f8f4)
Location: net/ipv4/route.c:575
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81eedff4)
Location: net/ipv4/route.c:575
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
In net/ipv4/route.c (ffffffff81fb2154)
Location: net/ipv4/route.c:575
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
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
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c57098)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffff800010c57098-ffff800010c570f4: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d667e8)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
c0d667e8-c0d6684c: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d57fd0)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
c000000000d57fd0-c000000000d58068: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c10bc)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffe0007c10bc-ffffffe0007c1120: fnhe_flush_routes (STB_LOCAL)
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
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81947360)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81947360-ffffffff819473b6: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81900e50)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff81900e50-ffffffff81900ea6: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b1b30)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff819b1b30-ffffffff819b1b86: fnhe_flush_routes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fnhe_flush_routes(struct fib_nh_exception *fnhe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bb1d0)
Location: net/ipv4/route.c:589
Inline: False
Direct callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff819bb1d0-ffffffff819bb226: fnhe_flush_routes (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
