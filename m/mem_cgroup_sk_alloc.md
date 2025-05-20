# Function: <code>mem_cgroup_sk_alloc</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236750)
Location: mm/memcontrol.c:5662
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81236750-ffffffff8123683f: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242200)
Location: mm/memcontrol.c:5724
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81242200-ffffffff812422d4: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262000)
Location: mm/memcontrol.c:5824
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81262000-ffffffff812620ca: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286000)
Location: mm/memcontrol.c:5892
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81286000-ffffffff812860ca: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129af60)
Location: mm/memcontrol.c:6223
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8129af60-ffffffff8129b01b: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6230)
Location: mm/memcontrol.c:6515
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff812b6230-ffffffff812b62e4: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8120)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812c8120-ffffffff812c81b9: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd980)
Location: mm/memcontrol.c:6713
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812fd980-ffffffff812fda11: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309da0)
Location: mm/memcontrol.c:6973
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81309da0-ffffffff81309e65: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310610)
Location: mm/memcontrol.c:6834
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81310610-ffffffff813106d5: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7015
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81cc2b9d-ffffffff81cc2bb2: mem_cgroup_sk_alloc.cold (STB_LOCAL)
ffffffff8135b920-ffffffff8135b9e2: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:6995
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81e75105-ffffffff81e7511a: mem_cgroup_sk_alloc.cold (STB_LOCAL)
ffffffff813d51c0-ffffffff813d52b0: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7184
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff8206828d-ffffffff820682a2: mem_cgroup_sk_alloc.cold (STB_LOCAL)
ffffffff8145ac40-ffffffff8145ad30: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7252
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff820e7b72-ffffffff820e7b87: mem_cgroup_sk_alloc.cold (STB_LOCAL)
ffffffff814908a0-ffffffff8149099a: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7629
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff821c48a1-ffffffff821c48b6: mem_cgroup_sk_alloc.cold (STB_LOCAL)
ffffffff814c0210-ffffffff814c030a: mem_cgroup_sk_alloc (STB_GLOBAL)
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
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b020)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffff80001036b020-ffff80001036b0b4: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c670)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
c055c670-c055c7a4: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a750)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
c00000000045a750-c00000000045a890: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe00024874a)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffe00024874a-ffffffe000248824: mem_cgroup_sk_alloc (STB_GLOBAL)
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
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0700)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812c0700-ffffffff812c0799: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b17c0)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812b17c0-ffffffff812b1859: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be510)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812be510-ffffffff812be5a9: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_sk_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cef20)
Location: mm/memcontrol.c:6855
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff812cef20-ffffffff812ceff2: mem_cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
