# Function: <code>proc_create_net_single</code>

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
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81327da0)
Location: fs/proc/proc_net.c:175
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff81327da0-ffffffff81327de8: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133ef90)
Location: fs/proc/proc_net.c:193
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff8133ef90-ffffffff8133efe0: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813672f0)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff813672f0-ffffffff81367340: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8137f570)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff8137f570-ffffffff8137f5c0: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c97e0)
Location: fs/proc/proc_net.c:213
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813c97e0-ffffffff813c982f: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813db450)
Location: fs/proc/proc_net.c:197
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813db450-ffffffff813db49f: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e2380)
Location: fs/proc/proc_net.c:197
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff813e2380-ffffffff813e23cf: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81433e90)
Location: fs/proc/proc_net.c:197
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff81433e90-ffffffff81433edf: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814aded0)
Location: fs/proc/proc_net.c:210
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff814aded0-ffffffff814adf2e: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544460)
Location: fs/proc/proc_net.c:207
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff81544460-ffffffff815444be: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c060)
Location: fs/proc/proc_net.c:207
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff8157c060-ffffffff8157c0be: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b4970)
Location: fs/proc/proc_net.c:207
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
```
**Symbols:**

```
ffffffff815b4970-ffffffff815b49ce: proc_create_net_single (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffff80001044ccd8)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffff80001044ccd8-ffff80001044cd54: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c061141c)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
c061141c-c061147c: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c000000000564310)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
c000000000564310-c000000000564390: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffe0002e1a46)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffe0002e1a46-ffffffe0002e1aba: proc_create_net_single (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81377b50)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff81377b50-ffffffff81377ba0: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81368620)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff81368620-ffffffff81368670: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81375620)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff81375620-ffffffff81375670: proc_create_net_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813890c0)
Location: fs/proc/proc_net.c:194
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/ipv6/route.c:ip6_route_net_init_late
```
**Symbols:**

```
ffffffff813890c0-ffffffff81389110: proc_create_net_single (STB_GLOBAL)
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
