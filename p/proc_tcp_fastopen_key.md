# Function: <code>proc_tcp_fastopen_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *ctl, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a58b0)
Location: net/ipv4/sysctl_net_ipv4.c:210
Inline: False
```
**Symbols:**

```
ffffffff817a58b0-ffffffff817a5a76: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *ctl, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81813540)
Location: net/ipv4/sysctl_net_ipv4.c:209
Inline: False
```
**Symbols:**

```
ffffffff81813540-ffffffff81813703: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *ctl, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844a50)
Location: net/ipv4/sysctl_net_ipv4.c:209
Inline: False
```
**Symbols:**

```
ffffffff81844a50-ffffffff81844c13: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *ctl, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81866500)
Location: net/ipv4/sysctl_net_ipv4.c:251
Inline: False
```
**Symbols:**

```
ffffffff81866500-ffffffff818666ba: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6230)
Location: net/ipv4/sysctl_net_ipv4.c:258
Inline: False
```
**Symbols:**

```
ffffffff818e6230-ffffffff818e63f5: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193cd30)
Location: net/ipv4/sysctl_net_ipv4.c:261
Inline: False
```
**Symbols:**

```
ffffffff8193cd30-ffffffff8193cf24: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196cbc0)
Location: net/ipv4/sysctl_net_ipv4.c:279
Inline: False
```
**Symbols:**

```
ffffffff8196cbc0-ffffffff8196cdb4: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff819d6420-ffffffff819d66b8: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff819d6ee3-ffffffff819d6eef: proc_tcp_fastopen_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff81a0cf10-ffffffff81a0d1a8: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff81a0d9d3-ffffffff81a0d9df: proc_tcp_fastopen_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afdcd0)
Location: net/ipv4/sysctl_net_ipv4.c:293
Inline: False
```
**Symbols:**

```
ffffffff81afdcd0-ffffffff81afdf56: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0bd40)
Location: net/ipv4/sysctl_net_ipv4.c:293
Inline: False
```
**Symbols:**

```
ffffffff81b0bd40-ffffffff81b0bfc6: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af99a0)
Location: net/ipv4/sysctl_net_ipv4.c:291
Inline: False
```
**Symbols:**

```
ffffffff81af99a0-ffffffff81af9c21: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bba520)
Location: net/ipv4/sysctl_net_ipv4.c:295
Inline: False
```
**Symbols:**

```
ffffffff81bba520-ffffffff81bba91f: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4e600)
Location: net/ipv4/sysctl_net_ipv4.c:282
Inline: False
```
**Symbols:**

```
ffffffff81d4e600-ffffffff81d4ea4f: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f180d0)
Location: net/ipv4/sysctl_net_ipv4.c:286
Inline: False
```
**Symbols:**

```
ffffffff81f180d0-ffffffff81f1851f: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f77d30)
Location: net/ipv4/sysctl_net_ipv4.c:288
Inline: False
```
**Symbols:**

```
ffffffff81f77d30-ffffffff81f7817f: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203e310)
Location: net/ipv4/sysctl_net_ipv4.c:284
Inline: False
```
**Symbols:**

```
ffffffff8203e310-ffffffff8203e78e: proc_tcp_fastopen_key (STB_LOCAL)
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
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc6880)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffff800010cc6880-ffff800010cc6b20: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (c0dd1ea4)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
c0dd1ea4-c0dd2154: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3360)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
c000000000de3360-c000000000de3704: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b0c0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffe00081b0c0-ffffffe00081b2ce: proc_tcp_fastopen_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff819accb0-ffffffff819acf48: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff819ad773-ffffffff819ad77f: proc_tcp_fastopen_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff819692e0-ffffffff81969578: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff81969da3-ffffffff81969daf: proc_tcp_fastopen_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff81a17550-ffffffff81a177e8: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff81a18013-ffffffff81a1801f: proc_tcp_fastopen_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_tcp_fastopen_key(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: net/ipv4/sysctl_net_ipv4.c:298
Inline: False
```
**Symbols:**

```
ffffffff81a21fe0-ffffffff81a22287: proc_tcp_fastopen_key (STB_LOCAL)
ffffffff81a22a93-ffffffff81a22a9f: proc_tcp_fastopen_key.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ctl_table *table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ctl_table *ctl</code>
</li>
</ul>
</details>
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
