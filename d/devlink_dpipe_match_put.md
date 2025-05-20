# Function: <code>devlink_dpipe_match_put</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:1684
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81952278-ffffffff81952293: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff8194bea0-ffffffff8194c023: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819812a0)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff819812a0-ffffffff81981422: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58be0)
Location: net/core/devlink.c:1718
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a58be0-ffffffff81a58d6a: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60a90)
Location: net/core/devlink.c:2050
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a60a90-ffffffff81a60c1a: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a42b30)
Location: net/core/devlink.c:2253
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a42b30-ffffffff81a42cb1: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:2815
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81d38792-ffffffff81d387a6: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff81af9d50-ffffffff81af9edd: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3330
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81f050bd-ffffffff81f050d2: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff81c7c020-ffffffff81c7c1b5: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3594
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff820ad0c1-ffffffff820ad0d6: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff81e35670-ffffffff81e35805: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:2812
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff82136467-ffffffff8213647c: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff820361c0-ffffffff82036355: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:60
Inline: False
Direct callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff82218119-ffffffff8221812e: devlink_dpipe_match_put.cold (STB_LOCAL)
ffffffff8210b180-ffffffff8210b315: devlink_dpipe_match_put (STB_GLOBAL)
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
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c29848)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffff800010c29848-ffff800010c299d4: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d400c0)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c0d400c0-c0d40254: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1edf0)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c000000000d1edf0-c000000000d1efe4: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a1732)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffe0007a1732-ffffffe0007a186c: devlink_dpipe_match_put (STB_GLOBAL)
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
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81921110)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81921110-ffffffff81921292: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818daec0)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff818daec0-ffffffff818db042: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819722a0)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff819722a0-ffffffff81972422: devlink_dpipe_match_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_dpipe_match_put(struct sk_buff *skb, struct devlink_dpipe_match *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81994600)
Location: net/core/devlink.c:1686
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81994600-ffffffff81994782: devlink_dpipe_match_put (STB_GLOBAL)
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
