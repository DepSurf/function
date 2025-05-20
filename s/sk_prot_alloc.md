# Function: <code>sk_prot_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700a80)
Location: net/core/sock.c:1336
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81700a80-ffffffff81700bac: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767440)
Location: net/core/sock.c:1336
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81767440-ffffffff81767577: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794460)
Location: net/core/sock.c:1326
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81794460-ffffffff81794580: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b2850)
Location: net/core/sock.c:1447
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff817b2850-ffffffff817b297f: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182aa60)
Location: net/core/sock.c:1455
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8182aa60-ffffffff8182ab8f: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874b60)
Location: net/core/sock.c:1467
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81874b60-ffffffff81874c81: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895420)
Location: net/core/sock.c:1463
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81895420-ffffffff81895543: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e08c0)
Location: net/core/sock.c:1589
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff818e08c0-ffffffff818e09fa: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81912b00)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81912b00-ffffffff81912c3a: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3ae0)
Location: net/core/sock.c:1679
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff819e3ae0-ffffffff819e3c1c: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3480)
Location: net/core/sock.c:1671
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff819e3480-ffffffff819e35af: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9500)
Location: net/core/sock.c:1704
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff819c9500-ffffffff819c9621: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78880)
Location: net/core/sock.c:1827
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81a78880-ffffffff81a789a1: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bec2b0)
Location: net/core/sock.c:1961
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81bec2b0-ffffffff81bec3e0: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98d10)
Location: net/core/sock.c:2026
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81d98d10-ffffffff81d98e40: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e07090)
Location: net/core/sock.c:2084
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81e07090-ffffffff81e071c0: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3900)
Location: net/core/sock.c:2064
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81ec3900-ffffffff81ec3a30: sk_prot_alloc (STB_LOCAL)
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
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baa288)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffff800010baa288-ffff800010baa418: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc8dc0)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
c0cc8dc0-c0cc8efc: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c803f0)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
c000000000c803f0-c000000000c80620: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073dc52)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffe00073dc52-ffffffe00073dd90: sk_prot_alloc (STB_LOCAL)
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
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b2b00)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff818b2b00-ffffffff818b2c3a: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ca50)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8186ca50-ffffffff8186cb8a: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81903b00)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81903b00-ffffffff81903c3a: sk_prot_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *sk_prot_alloc(struct proto *prot, gfp_t priority, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924b00)
Location: net/core/sock.c:1591
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81924b00-ffffffff81924c3a: sk_prot_alloc (STB_LOCAL)
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
