# Function: <code>ip6mr_update_thresholds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr6_table *mrt, struct mfc6_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817f87a0)
Location: net/ipv6/ip6mr.c:905
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817f87a0-ffffffff817f8840: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr6_table *mrt, struct mfc6_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81867f80)
Location: net/ipv6/ip6mr.c:905
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81867f80-ffffffff81868025: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr6_table *mrt, struct mfc6_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189ade0)
Location: net/ipv6/ip6mr.c:905
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8189ade0-ffffffff8189ae85: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ip6mr_update_thresholds(struct mr6_table *mrt, struct mfc6_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c0cf0)
Location: net/ipv6/ip6mr.c:908
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818c0cf0-ffffffff818c0d83: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ip6mr_update_thresholds(struct mr6_table *mrt, struct mfc6_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81943f10)
Location: net/ipv6/ip6mr.c:908
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81943f10-ffffffff81943fa3: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199ca50)
Location: net/ipv6/ip6mr.c:824
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8199ca50-ffffffff8199caea: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d38c0)
Location: net/ipv6/ip6mr.c:838
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d38c0-ffffffff819d395a: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a42a60)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a42a60-ffffffff81a42b03: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a796c0)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a796c0-ffffffff81a79763: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b73950)
Location: net/ipv6/ip6mr.c:837
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b73950-ffffffff81b739f3: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b826c0)
Location: net/ipv6/ip6mr.c:837
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b826c0-ffffffff81b82763: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b71270)
Location: net/ipv6/ip6mr.c:837
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b71270-ffffffff81b71313: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c3b480)
Location: net/ipv6/ip6mr.c:838
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81c3b480-ffffffff81c3b582: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dd9590)
Location: net/ipv6/ip6mr.c:831
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81dd9590-ffffffff81dd96a6: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81fab1b0)
Location: net/ipv6/ip6mr.c:839
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81fab1b0-ffffffff81fab2c9: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200b940)
Location: net/ipv6/ip6mr.c:839
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8200b940-ffffffff8200ba65: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820da950)
Location: net/ipv6/ip6mr.c:839
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff820da950-ffffffff820daa75: ip6mr_update_thresholds (STB_LOCAL)
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
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d42a30)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffff800010d42a30-ffff800010d42b10: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e45660)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c0e45660-c0e45734: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e77ee0)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c000000000e77ee0-c000000000e77fdc: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087e51e)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffe00087e51e-ffffffe00087e5d8: ip6mr_update_thresholds (STB_LOCAL)
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
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a18d50)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a18d50-ffffffff81a18df3: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d5b10)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d5b10-ffffffff819d5bb3: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a837d0)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a837d0-ffffffff81a83873: ip6mr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6mr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a900f0)
Location: net/ipv6/ip6mr.c:833
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a900f0-ffffffff81a90193: ip6mr_update_thresholds (STB_LOCAL)
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
<b>Param type changed. </b>
<code>struct mr6_table *mrt</code> ➡️ <code>struct mr_table *mrt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct mfc6_cache *cache</code> ➡️ <code>struct mr_mfc *cache</code>
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
