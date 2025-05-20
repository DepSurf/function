# Function: <code>netlink_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174c1b0)
Location: net/netlink/af_netlink.c:2781
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_poll
  - net/netlink/af_netlink.c:__netlink_dump_start
```
**Symbols:**

```
ffffffff8174c1b0-ffffffff8174c461: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b7ef0)
Location: net/netlink/af_netlink.c:2056
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff817b7ef0-ffffffff817b8180: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e79d0)
Location: net/netlink/af_netlink.c:2073
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff817e79d0-ffffffff817e7c60: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818076e0)
Location: net/netlink/af_netlink.c:2124
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff818076e0-ffffffff8180796e: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81886210)
Location: net/netlink/af_netlink.c:2137
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81886210-ffffffff818864d6: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d9b20)
Location: net/netlink/af_netlink.c:2178
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff818d9b20-ffffffff818d9de2: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81906570)
Location: net/netlink/af_netlink.c:2187
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81906570-ffffffff819068e6: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2187
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81967810-ffffffff81967b8e: netlink_dump (STB_LOCAL)
ffffffff8196b108-ffffffff8196b121: netlink_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199e2a0)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff8199e2a0-ffffffff8199e62b: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a77e50)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81a77e50-ffffffff81a78243: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a80d10)
Location: net/netlink/af_netlink.c:2212
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81a80d10-ffffffff81a8104e: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a694d0)
Location: net/netlink/af_netlink.c:2222
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81a694d0-ffffffff81a697c3: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2233
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81b22a80-ffffffff81b22d7f: netlink_dump (STB_LOCAL)
ffffffff81d393e0-ffffffff81d393f4: netlink_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2212
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81cab650-ffffffff81cab977: netlink_dump (STB_LOCAL)
ffffffff81f05bc3-ffffffff81f05bd8: netlink_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2233
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81e68450-ffffffff81e6878a: netlink_dump (STB_LOCAL)
ffffffff820ad91b-ffffffff820ad930: netlink_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2204
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81ec42c0-ffffffff81ec45fa: netlink_dump (STB_LOCAL)
ffffffff8212eb06-ffffffff8212eb1b: netlink_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2199
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff81f87680-ffffffff81f879ba: netlink_dump (STB_LOCAL)
ffffffff822108b2-ffffffff822108c7: netlink_dump.cold (STB_LOCAL)
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
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4b958)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffff800010c4b958-ffff800010c4bc84: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5c1b0)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
c0d5c1b0-c0d5c4d4: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d49a80)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
c000000000d49a80-c000000000d49ed8: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b8e98)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffe0007b8e98-ffffffe0007b915e: netlink_dump (STB_LOCAL)
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
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193e110)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff8193e110-ffffffff8193e49b: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f7c10)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff818f7c10-ffffffff818f7f9b: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198f2a0)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff8198f2a0-ffffffff8198f62b: netlink_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlink_dump(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b1b80)
Location: net/netlink/af_netlink.c:2188
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_recvmsg
```
**Symbols:**

```
ffffffff819b1b80-ffffffff819b1f0b: netlink_dump (STB_LOCAL)
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
