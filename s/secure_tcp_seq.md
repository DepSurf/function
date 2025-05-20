# Function: <code>secure_tcp_seq</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff817c4200)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff817c4200-ffffffff817c42bd: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff8183dcd0)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff8183dcd0-ffffffff8183dd90: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818884d0)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff818884d0-ffffffff81888590: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818a8a70)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff818a8a70-ffffffff818a8b30: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818f4100)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff818f4100-ffffffff818f41c2: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819260b0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819260b0-ffffffff81926172: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819fa090)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819fa090-ffffffff819fa152: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819f9c80)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819f9c80-ffffffff819f9d42: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819dfe30)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819dfe30-ffffffff819dfef5: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81a90570)
Location: net/core/secure_seq.c:132
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff81a90570-ffffffff81a90632: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81c06440)
Location: net/core/secure_seq.c:136
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff81c06440-ffffffff81c06516: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81db5d90)
Location: net/core/secure_seq.c:136
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff81db5d90-ffffffff81db5e66: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81e26360)
Location: net/core/secure_seq.c:136
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff81e26360-ffffffff81e26436: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81ee42f0)
Location: net/core/secure_seq.c:136
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff81ee42f0-ffffffff81ee43c6: secure_tcp_seq (STB_GLOBAL)
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
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffff800010bc2280)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffff800010bc2280-ffff800010bc236c: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (c0cdd618)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
c0cdd618-c0cdd6fc: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (c000000000c9bfd0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
c000000000c9bfd0-c000000000c9c114: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffe00074f114)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffe00074f114-ffffffe00074f1c4: secure_tcp_seq (STB_GLOBAL)
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
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818c60b0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff818c60b0-ffffffff818c6172: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff8187fff0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff8187fff0-ffffffff818800b2: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819170b0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819170b0-ffffffff81917172: secure_tcp_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 secure_tcp_seq(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819382c0)
Location: net/core/secure_seq.c:133
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
**Symbols:**

```
ffffffff819382c0-ffffffff81938382: secure_tcp_seq (STB_GLOBAL)
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
