# Function: <code>single_open_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file, int (*show)(struct seq_file *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812867e0)
Location: fs/proc/proc_net.c:63
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_open
  - net/ipv4/proc.c:snmp_seq_open
  - net/ipv4/proc.c:netstat_seq_open
  - net/ipv4/proc.c:sockstat_seq_open
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_open
  - net/ipv6/route.c:rt6_stats_seq_open
  - net/ipv6/proc.c:snmp6_seq_open
  - net/ipv6/proc.c:sockstat6_seq_open
```
**Symbols:**

```
ffffffff812867e0-ffffffff81286849: single_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file, int (*show)(struct seq_file *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812b3980)
Location: fs/proc/proc_net.c:63
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_open
  - net/ipv4/proc.c:netstat_seq_open
  - net/ipv4/proc.c:snmp_seq_open
  - net/ipv4/proc.c:sockstat_seq_open
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_open
  - net/ipv6/route.c:rt6_stats_seq_open
  - net/ipv6/proc.c:snmp6_seq_open
  - net/ipv6/proc.c:sockstat6_seq_open
```
**Symbols:**

```
ffffffff812b3980-ffffffff812b39e1: single_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file, int (*show)(struct seq_file *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812c9210)
Location: fs/proc/proc_net.c:64
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_open
  - net/ipv4/proc.c:netstat_seq_open
  - net/ipv4/proc.c:snmp_seq_open
  - net/ipv4/proc.c:sockstat_seq_open
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_open
  - net/ipv6/route.c:rt6_stats_seq_open
  - net/ipv6/proc.c:snmp6_seq_open
  - net/ipv6/proc.c:sockstat6_seq_open
```
**Symbols:**

```
ffffffff812c9210-ffffffff812c9271: single_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file, int (*show)(struct seq_file *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812d6530)
Location: fs/proc/proc_net.c:65
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_open
  - net/ipv4/proc.c:netstat_seq_open
  - net/ipv4/proc.c:snmp_seq_open
  - net/ipv4/proc.c:sockstat_seq_open
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_open
  - net/ipv6/route.c:rt6_stats_seq_open
  - net/ipv6/proc.c:snmp6_seq_open
  - net/ipv6/proc.c:sockstat6_seq_open
```
**Symbols:**

```
ffffffff812d6530-ffffffff812d65b3: single_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file, int (*show)(struct seq_file *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812fad80)
Location: fs/proc/proc_net.c:65
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_open
  - net/ipv4/proc.c:netstat_seq_open
  - net/ipv4/proc.c:snmp_seq_open
  - net/ipv4/proc.c:sockstat_seq_open
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_open
  - net/ipv6/route.c:rt6_stats_seq_open
  - net/ipv6/proc.c:snmp6_seq_open
  - net/ipv6/proc.c:sockstat6_seq_open
```
**Symbols:**

```
ffffffff812fad80-ffffffff812fae03: single_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813282f0)
Location: fs/proc/proc_net.c:144
Inline: False
```
**Symbols:**

```
ffffffff813282f0-ffffffff813283b2: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133f4d0)
Location: fs/proc/proc_net.c:162
Inline: False
```
**Symbols:**

```
ffffffff8133f4d0-ffffffff8133f592: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813677f0)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff813677f0-ffffffff81367888: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8137fa70)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff8137fa70-ffffffff8137fb08: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9e10)
Location: fs/proc/proc_net.c:182
Inline: False
```
**Symbols:**

```
ffffffff813c9e10-ffffffff813c9ea0: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813dba90)
Location: fs/proc/proc_net.c:166
Inline: False
```
**Symbols:**

```
ffffffff813dba90-ffffffff813dbb70: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e29b0)
Location: fs/proc/proc_net.c:166
Inline: False
```
**Symbols:**

```
ffffffff813e29b0-ffffffff813e2a8c: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814344c0)
Location: fs/proc/proc_net.c:166
Inline: False
```
**Symbols:**

```
ffffffff814344c0-ffffffff8143459c: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814ae5e0)
Location: fs/proc/proc_net.c:179
Inline: False
```
**Symbols:**

```
ffffffff814ae5e0-ffffffff814ae6e4: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544c20)
Location: fs/proc/proc_net.c:176
Inline: False
```
**Symbols:**

```
ffffffff81544c20-ffffffff81544d24: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c810)
Location: fs/proc/proc_net.c:176
Inline: False
```
**Symbols:**

```
ffffffff8157c810-ffffffff8157c910: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b5130)
Location: fs/proc/proc_net.c:176
Inline: False
```
**Symbols:**

```
ffffffff815b5130-ffffffff815b5230: single_open_net (STB_LOCAL)
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
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffff80001044d388)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffff80001044d388-ffff80001044d438: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c0611970)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
c0611970-c06119f4: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c000000000564c60)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
c000000000564c60-c000000000564d6c: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffe0002e1c90)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffe0002e1c90-ffffffe0002e1d24: single_open_net (STB_LOCAL)
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
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81378050)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff81378050-ffffffff813780e8: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81368b20)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff81368b20-ffffffff81368bb8: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81375b20)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff81375b20-ffffffff81375bb8: single_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int single_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813895d0)
Location: fs/proc/proc_net.c:163
Inline: False
```
**Symbols:**

```
ffffffff813895d0-ffffffff81389668: single_open_net (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int (*show)(struct seq_file *, void *)</code>
</li>
</ul>
</details>
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
