# Function: <code>packet_do_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81804d30)
Location: net/packet/af_packet.c:2916
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_bind_spkt
  - net/packet/af_packet.c:packet_bind
Direct callers:
  - net/packet/af_packet.c:packet_bind_spkt
  - net/packet/af_packet.c:packet_bind
```
**Symbols:**

```
ffffffff81804d30-ffffffff81804f65: packet_do_bind.part.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875a32)
Location: net/packet/af_packet.c:3030
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81875750-ffffffff81875982: packet_do_bind.part.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a9f12)
Location: net/packet/af_packet.c:2991
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff818a9c20-ffffffff818a9e6b: packet_do_bind.part.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cfe00)
Location: net/packet/af_packet.c:3057
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff818cfe00-ffffffff818d0045: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81954ce0)
Location: net/packet/af_packet.c:3049
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81954ce0-ffffffff81954f53: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819b0ad0)
Location: net/packet/af_packet.c:3029
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff819b0ad0-ffffffff819b0d3d: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e5ec0)
Location: net/packet/af_packet.c:3041
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff819e5ec0-ffffffff819e612a: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a55900)
Location: net/packet/af_packet.c:3067
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81a55900-ffffffff81a55b99: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8c9d0)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81a8c9d0-ffffffff81a8cc69: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b89400)
Location: net/packet/af_packet.c:3097
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81b89400-ffffffff81b89699: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b98f00)
Location: net/packet/af_packet.c:3114
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81b98f00-ffffffff81b991a3: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b884f0)
Location: net/packet/af_packet.c:3126
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81b884f0-ffffffff81b88793: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c54600)
Location: net/packet/af_packet.c:3131
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81c54600-ffffffff81c5489b: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df2cb0)
Location: net/packet/af_packet.c:3185
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81df2cb0-ffffffff81df2fdd: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc70b0)
Location: net/packet/af_packet.c:3185
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81fc70b0-ffffffff81fc73dd: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82027de0)
Location: net/packet/af_packet.c:3197
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff82027de0-ffffffff820280cd: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f7640)
Location: net/packet/af_packet.c:3193
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff820f7640-ffffffff820f792d: packet_do_bind (STB_LOCAL)
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
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5a6f0)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffff800010d5a6f0-ffff800010d5a9a4: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e57c18)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
c0e57c18-c0e57ebc: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e91850)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
c000000000e91850-c000000000e91bd8: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe000890d16)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffe000890d16-ffffffe000890f64: packet_do_bind (STB_LOCAL)
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
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2c060)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81a2c060-ffffffff81a2c2f9: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e9250)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff819e9250-ffffffff819e94e9: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a97c10)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81a97c10-ffffffff81a97ea9: packet_do_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int packet_do_bind(struct sock *sk, const char *name, int ifindex, __be16 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa1b60)
Location: net/packet/af_packet.c:3086
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind
  - net/packet/af_packet.c:packet_bind_spkt
```
**Symbols:**

```
ffffffff81aa1b60-ffffffff81aa1e0b: packet_do_bind (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
