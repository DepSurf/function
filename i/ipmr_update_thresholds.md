# Function: <code>ipmr_update_thresholds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mfc_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a7140)
Location: net/ipv4/ipmr.c:691
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff817a7140-ffffffff817a71e0: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mfc_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81814e20)
Location: net/ipv4/ipmr.c:706
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81814e20-ffffffff81814ece: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mfc_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818465e0)
Location: net/ipv4/ipmr.c:711
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818465e0-ffffffff8184668e: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mfc_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818688f0)
Location: net/ipv4/ipmr.c:731
Inline: True
```
**Symbols:**

```
ffffffff818688f0-ffffffff81868985: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mfc_cache *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e8ce0)
Location: net/ipv4/ipmr.c:845
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818e8ce0-ffffffff818e8d6d: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8193f4c0)
Location: net/ipv4/ipmr.c:812
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8193f4c0-ffffffff8193f55a: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196f260)
Location: net/ipv4/ipmr.c:815
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8196f260-ffffffff8196f2fa: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819d8470)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819d8470-ffffffff819d8513: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0f180)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a0f180-ffffffff81a0f223: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b00260)
Location: net/ipv4/ipmr.c:783
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81b00260-ffffffff81b00303: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0e2e0)
Location: net/ipv4/ipmr.c:786
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81b0e2e0-ffffffff81b0e383: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afbfb0)
Location: net/ipv4/ipmr.c:786
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81afbfb0-ffffffff81afc053: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbd450)
Location: net/ipv4/ipmr.c:788
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81bbd450-ffffffff81bbd552: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d51c30)
Location: net/ipv4/ipmr.c:781
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81d51c30-ffffffff81d51d46: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1bbf0)
Location: net/ipv4/ipmr.c:788
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81f1bbf0-ffffffff81f1bd09: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7b6c0)
Location: net/ipv4/ipmr.c:788
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81f7b6c0-ffffffff81f7b7e5: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82041db0)
Location: net/ipv4/ipmr.c:788
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff82041db0-ffffffff82041ed5: ipmr_update_thresholds (STB_LOCAL)
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
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cc90a0)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffff800010cc90a0-ffff800010cc9180: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd44a4)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c0dd44a4-c0dd4578: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de6640)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c000000000de6640-c000000000de673c: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081d32a)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffe00081d32a-ffffffe00081d3e4: ipmr_update_thresholds (STB_LOCAL)
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
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819aed00)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819aed00-ffffffff819aeda3: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196b330)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8196b330-ffffffff8196b3d3: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a195a0)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a195a0-ffffffff81a19643: ipmr_update_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipmr_update_thresholds(struct mr_table *mrt, struct mr_mfc *cache, unsigned char *ttls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a24260)
Location: net/ipv4/ipmr.c:809
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a24260-ffffffff81a24303: ipmr_update_thresholds (STB_LOCAL)
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
<code>struct mfc_cache *cache</code> ➡️ <code>struct mr_mfc *cache</code>
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
