# Function: <code>ipmr_cache_resolve</code>

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
In net/ipv4/ipmr.c (ffffffff817aa128)
Location: net/ipv4/ipmr.c:905
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
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
In net/ipv4/ipmr.c (ffffffff81817613)
Location: net/ipv4/ipmr.c:914
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81848e83)
Location: net/ipv4/ipmr.c:919
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8186c4a2)
Location: net/ipv4/ipmr.c:968
Inline: True
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
In net/ipv4/ipmr.c (ffffffff818ecd81)
Location: net/ipv4/ipmr.c:1094
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1008
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1011
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b02d90)
Location: net/ipv4/ipmr.c:971
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81b02d90-ffffffff81b02ee4: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b11170)
Location: net/ipv4/ipmr.c:974
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81b11170-ffffffff81b112c4: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:974
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:976
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d553a0)
Location: net/ipv4/ipmr.c:970
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81d553a0-ffffffff81d554f8: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1f6b0)
Location: net/ipv4/ipmr.c:980
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81f1f6b0-ffffffff81f1f812: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7f1b0)
Location: net/ipv4/ipmr.c:980
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81f7f1b0-ffffffff81f7f312: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipmr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc_cache *uc, struct mfc_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82045830)
Location: net/ipv4/ipmr.c:980
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff82045830-ffffffff82045992: ipmr_cache_resolve (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe000820034)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1003
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
