# Function: <code>netlink_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174b840)
Location: net/netlink/af_netlink.c:3298
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff8174b840-ffffffff8174b8d4: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b8820)
Location: net/netlink/af_netlink.c:2567
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff817b8820-ffffffff817b88b4: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e82d0)
Location: net/netlink/af_netlink.c:2585
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff817e82d0-ffffffff817e8364: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81807fd0)
Location: net/netlink/af_netlink.c:2684
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81807fd0-ffffffff81808066: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818869c0)
Location: net/netlink/af_netlink.c:2701
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff818869c0-ffffffff81886a56: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818da340)
Location: net/netlink/af_netlink.c:2728
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff818da340-ffffffff818da3d6: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81906d80)
Location: net/netlink/af_netlink.c:2750
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81906d80-ffffffff81906e16: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81968020)
Location: net/netlink/af_netlink.c:2733
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff81968020-ffffffff819680b6: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199eac0)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff8199eac0-ffffffff8199eb56: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a77770)
Location: net/netlink/af_netlink.c:2788
Inline: True
```
**Symbols:**

```
ffffffff81a77770-ffffffff81a777cf: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a80640)
Location: net/netlink/af_netlink.c:2813
Inline: True
```
**Symbols:**

```
ffffffff81a80640-ffffffff81a8069f: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a69cd0)
Location: net/netlink/af_netlink.c:2823
Inline: True
```
**Symbols:**

```
ffffffff81a69cd0-ffffffff81a69d29: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b232c0)
Location: net/netlink/af_netlink.c:2836
Inline: True
```
**Symbols:**

```
ffffffff81b232c0-ffffffff81b23319: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cab460)
Location: net/netlink/af_netlink.c:2822
Inline: True
```
**Symbols:**

```
ffffffff81cab460-ffffffff81cab4c5: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e69140)
Location: net/netlink/af_netlink.c:2895
Inline: True
```
**Symbols:**

```
ffffffff81e69140-ffffffff81e691a5: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec4fb0)
Location: net/netlink/af_netlink.c:2869
Inline: True
```
**Symbols:**

```
ffffffff81ec4fb0-ffffffff81ec5051: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f88380)
Location: net/netlink/af_netlink.c:2863
Inline: True
```
**Symbols:**

```
ffffffff81f88380-ffffffff81f88431: netlink_hash (STB_LOCAL)
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
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4b7a8)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffff800010c4b7a8-ffff800010c4b870: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5dab4)
Location: net/netlink/af_netlink.c:2734
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
c0d5ce20-c0d5ce84: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4b8c0)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
c000000000d4b8c0-c000000000d4b9a4: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b9c1a)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffe0007b9c1a-ffffffe0007b9ca6: netlink_hash (STB_LOCAL)
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
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193e930)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff8193e930-ffffffff8193e9c6: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f8430)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff818f8430-ffffffff818f84c6: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198fac0)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff8198fac0-ffffffff8198fb56: netlink_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 netlink_hash(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b2460)
Location: net/netlink/af_netlink.c:2734
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff819b2460-ffffffff819b24f6: netlink_hash (STB_LOCAL)
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
