# Function: <code>bpf_msg_redirect_hash</code>

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
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1770)
Location: net/core/filter.c:2192
Inline: False
```
**Symbols:**

```
ffffffff818b1770-ffffffff818b17ad: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2d60)
Location: net/core/sock_map.c:919
Inline: False
```
**Symbols:**

```
ffffffff818f2d60-ffffffff818f2d9d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81945220)
Location: net/core/sock_map.c:926
Inline: False
```
**Symbols:**

```
ffffffff81945220-ffffffff8194525d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8197a240)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffff8197a240-ffffffff8197a27d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4df50)
Location: net/core/sock_map.c:1190
Inline: False
```
**Symbols:**

```
ffffffff81a4df50-ffffffff81a4dfc8: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53f40)
Location: net/core/sock_map.c:1278
Inline: False
```
**Symbols:**

```
ffffffff81a53f40-ffffffff81a53fb8: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4fa50)
Location: net/core/sock_map.c:1261
Inline: False
```
**Symbols:**

```
ffffffff81a4fa50-ffffffff81a4facd: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08720)
Location: net/core/sock_map.c:1252
Inline: False
```
**Symbols:**

```
ffffffff81b08720-ffffffff81b0879d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8e6c0)
Location: net/core/sock_map.c:1254
Inline: False
```
**Symbols:**

```
ffffffff81c8e6c0-ffffffff81c8e762: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49aa0)
Location: net/core/sock_map.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81e49aa0-ffffffff81e49b42: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea5160)
Location: net/core/sock_map.c:1259
Inline: False
```
**Symbols:**

```
ffffffff81ea5160-ffffffff81ea5202: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67df0)
Location: net/core/sock_map.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81f67df0-ffffffff81f67edb: bpf_msg_redirect_hash (STB_GLOBAL)
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
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c21488)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffff800010c21488-ffff800010c214f8: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38c2c)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
c0d38c2c-c0d38c88: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d138b0)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
c000000000d138b0-c000000000d13918: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079a2d4)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffe00079a2d4-ffffffe00079a336: bpf_msg_redirect_hash (STB_GLOBAL)
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
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8191a0b0)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffff8191a0b0-ffffffff8191a0ed: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d3e60)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffff818d3e60-ffffffff818d3e9d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196b240)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffff8196b240-ffffffff8196b27d: bpf_msg_redirect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_msg_redirect_hash(u64 msg, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d6b0)
Location: net/core/sock_map.c:946
Inline: False
```
**Symbols:**

```
ffffffff8198d6b0-ffffffff8198d6ed: bpf_msg_redirect_hash (STB_GLOBAL)
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
