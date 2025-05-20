# Function: <code>bpf_sock_map_update</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 bpf_sock, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b1600)
Location: kernel/bpf/sockmap.c:892
Inline: False
```
**Symbols:**

```
ffffffff811b1600-ffffffff811b1612: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 bpf_sock, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cd7a0)
Location: kernel/bpf/sockmap.c:2539
Inline: False
```
**Symbols:**

```
ffffffff811cd7a0-ffffffff811cd7b5: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2430)
Location: net/core/sock_map.c:426
Inline: False
```
**Symbols:**

```
ffffffff818f2430-ffffffff818f2477: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944ec0)
Location: net/core/sock_map.c:430
Inline: False
```
**Symbols:**

```
ffffffff81944ec0-ffffffff81944f02: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979ed0)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffff81979ed0-ffffffff81979f12: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f4b0)
Location: net/core/sock_map.c:606
Inline: False
```
**Symbols:**

```
ffffffff81a4f4b0-ffffffff81a4f517: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a554c0)
Location: net/core/sock_map.c:634
Inline: False
```
**Symbols:**

```
ffffffff81a554c0-ffffffff81a55528: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a51300)
Location: net/core/sock_map.c:628
Inline: False
```
**Symbols:**

```
ffffffff81a51300-ffffffff81a51348: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b09d00)
Location: net/core/sock_map.c:619
Inline: False
```
**Symbols:**

```
ffffffff81b09d00-ffffffff81b09d48: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8ff40)
Location: net/core/sock_map.c:613
Inline: False
```
**Symbols:**

```
ffffffff81c8ff40-ffffffff81c8ffa8: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e4b3b0)
Location: net/core/sock_map.c:615
Inline: False
```
**Symbols:**

```
ffffffff81e4b3b0-ffffffff81e4b418: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea6ad0)
Location: net/core/sock_map.c:611
Inline: False
```
**Symbols:**

```
ffffffff81ea6ad0-ffffffff81ea6b38: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f695c0)
Location: net/core/sock_map.c:613
Inline: False
```
**Symbols:**

```
ffffffff81f695c0-ffffffff81f69628: bpf_sock_map_update (STB_GLOBAL)
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
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c20918)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffff800010c20918-ffff800010c209a0: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38288)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
c0d38288-c0d38308: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d12890)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
c000000000d12890-c000000000d12908: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000799558)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffe000799558-ffffffe0007995d2: bpf_sock_map_update (STB_GLOBAL)
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
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81919d40)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffff81919d40-ffffffff81919d82: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d3af0)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffff818d3af0-ffffffff818d3b32: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196aed0)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffff8196aed0-ffffffff8196af12: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sock_map_update(u64 sops, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d340)
Location: net/core/sock_map.c:438
Inline: False
```
**Symbols:**

```
ffffffff8198d340-ffffffff8198d382: bpf_sock_map_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 sops</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 bpf_sock</code>
</li>
</ul>
</details>
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
