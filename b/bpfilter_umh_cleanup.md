# Function: <code>bpfilter_umh_cleanup</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8196c940)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff8196c940-ffffffff8196c988: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819d60e0)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff819d60e0-ffffffff819d6128: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a0cbd0)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff81a0cbd0-ffffffff81a0cc18: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81afd980)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff81afd980-ffffffff81afd9cb: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpfilter_umh_cleanup(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81b0b99b)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81b0b8b0-ffffffff81b0b8e6: bpfilter_umh_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpfilter_umh_cleanup(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81af95fb)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81af9510-ffffffff81af9546: bpfilter_umh_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpfilter_umh_cleanup(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81bba14b)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81bba060-ffffffff81bba096: bpfilter_umh_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpfilter_umh_cleanup(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81d4e14b)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81d4e050-ffffffff81d4e08c: bpfilter_umh_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpfilter_umh_cleanup(struct umd_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f17aab)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
```
**Symbols:**

```
ffffffff81f179a0-ffffffff81f179dc: bpfilter_umh_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc6280)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffff800010cc6280-ffff800010cc62e4: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c0dd1a54)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
c0dd1a54-c0dd1aac: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c000000000de2dc0)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
c000000000de2dc0-c000000000de2e4c: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffe00081acc0)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffe00081acc0-ffffffe00081ad22: bpfilter_umh_cleanup (STB_LOCAL)
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
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819ac970)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff819ac970-ffffffff819ac9b8: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81966430)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff81966430-ffffffff81966478: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a17210)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff81a17210-ffffffff81a17258: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a21c40)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
```
**Symbols:**

```
ffffffff81a21c40-ffffffff81a21c88: bpfilter_umh_cleanup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct umh_info *info</code> ➡️ <code>struct umd_info *info</code>
</li>
</ul>
</details>
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
