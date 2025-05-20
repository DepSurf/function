# Function: <code>free_pg_vec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void free_pg_vec(void **pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174a5d0)
Location: net/netlink/af_netlink.c:322
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818033d0)
Location: net/packet/af_packet.c:3993
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8174a5d0-ffffffff8174a65e: free_pg_vec (STB_LOCAL)
ffffffff818033d0-ffffffff8180345c: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81874800)
Location: net/packet/af_packet.c:4086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81874800-ffffffff81874883: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a8df0)
Location: net/packet/af_packet.c:4059
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff818a8df0-ffffffff818a8e73: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cf5a0)
Location: net/packet/af_packet.c:4132
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff818cf5a0-ffffffff818cf623: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81954510)
Location: net/packet/af_packet.c:4131
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81954510-ffffffff81954593: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819ada90)
Location: net/packet/af_packet.c:4136
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff819ada90-ffffffff819adb13: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e4400)
Location: net/packet/af_packet.c:4165
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff819e4400-ffffffff819e4483: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a533d0)
Location: net/packet/af_packet.c:4198
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81a533d0-ffffffff81a53452: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a89fc0)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81a89fc0-ffffffff81a8a042: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85470)
Location: net/packet/af_packet.c:4228
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b85470-ffffffff81b854e7: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b94e60)
Location: net/packet/af_packet.c:4224
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b94e60-ffffffff81b94ed7: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b83ed0)
Location: net/packet/af_packet.c:4238
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b83ed0-ffffffff81b83f47: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c4ffc0)
Location: net/packet/af_packet.c:4239
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81c4ffc0-ffffffff81c50037: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df0c00)
Location: net/packet/af_packet.c:4294
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81df0c00-ffffffff81df0c7f: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc4c80)
Location: net/packet/af_packet.c:4293
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81fc4c80-ffffffff81fc4cff: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82025b70)
Location: net/packet/af_packet.c:4314
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff82025b70-ffffffff82025bef: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f54e0)
Location: net/packet/af_packet.c:4315
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff820f54e0-ffffffff820f555f: free_pg_vec (STB_LOCAL)
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
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d56f88)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff800010d56f88-ffff800010d57024: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e575ec)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0e575ec-c0e57690: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e90360)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c000000000e90360-c000000000e90450: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088e7ac)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe00088e7ac-ffffffe00088e838: free_pg_vec (STB_LOCAL)
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
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a29650)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81a29650-ffffffff81a296d2: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e6840)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff819e6840-ffffffff819e68c2: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a95200)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81a95200-ffffffff81a95282: free_pg_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pg_vec(struct pgv *pg_vec, unsigned int order, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa15d0)
Location: net/packet/af_packet.c:4217
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81aa15d0-ffffffff81aa1652: free_pg_vec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void **pg_vec</code> ➡️ <code>struct pgv *pg_vec</code>
</li>
</ul>
</details>
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
