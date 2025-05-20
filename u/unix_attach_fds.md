# Function: <code>unix_attach_fds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817be65e)
Location: net/unix/af_unix.c:1533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182b5fe)
Location: net/unix/af_unix.c:1521
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185d01e)
Location: net/unix/af_unix.c:1526
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81881838)
Location: net/unix/af_unix.c:1533
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819029d4)
Location: net/unix/af_unix.c:1532
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81958e44)
Location: net/unix/af_unix.c:1522
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198da04)
Location: net/unix/af_unix.c:1539
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819fdf40)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff819fdf40-ffffffff819fdfee: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a34b30)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81a34b30-ffffffff81a34bde: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b29970)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b29970-ffffffff81b29a1b: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b382a0)
Location: net/unix/scm.c:104
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b382a0-ffffffff81b3834b: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b25f40)
Location: net/unix/scm.c:104
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b25f40-ffffffff81b25feb: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81bebba0)
Location: net/unix/scm.c:106
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81bebba0-ffffffff81bebc4b: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81d84080)
Location: net/unix/scm.c:106
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81d84080-ffffffff81d84135: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81f51910)
Location: net/unix/scm.c:106
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81f51910-ffffffff81f519c5: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81fb12a0)
Location: net/unix/scm.c:107
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81fb12a0-ffffffff81fb1377: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff8207e9c0)
Location: net/unix/scm.c:105
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff8207e9c0-ffffffff8207ea9a: unix_attach_fds (STB_GLOBAL)
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
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffff800010cf5358)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffff800010cf5358-ffff800010cf5418: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c0dfbe48)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
c0dfbe48-c0dfbf10: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c000000000e1b490)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
c000000000e1b490-c000000000e1b598: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffe000840e7e)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffe000840e7e-ffffffe000840f20: unix_attach_fds (STB_GLOBAL)
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
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819d41c0)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff819d41c0-ffffffff819d426e: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81990f80)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81990f80-ffffffff8199102e: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a3ec40)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81a3ec40-ffffffff81a3ecee: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie *scm, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a4a700)
Location: net/unix/scm.c:103
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81a4a700-ffffffff81a4a7ae: unix_attach_fds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
