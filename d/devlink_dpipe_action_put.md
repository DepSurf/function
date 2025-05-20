# Function: <code>devlink_dpipe_action_put</code>

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
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:1732
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81952293-ffffffff819522ae: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff8194c030-ffffffff8194c1b3: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81981110)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81981110-ffffffff81981292: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58a50)
Location: net/core/devlink.c:1766
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a58a50-ffffffff81a58bda: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60c20)
Location: net/core/devlink.c:2098
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a60c20-ffffffff81a60daa: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a42cc0)
Location: net/core/devlink.c:2301
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a42cc0-ffffffff81a42e41: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:2863
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81d3877e-ffffffff81d38792: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff81af9bc0-ffffffff81af9d4d: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3378
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81f050a8-ffffffff81f050bd: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff81c7be80-ffffffff81c7c015: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff820ad0d6-ffffffff820ad0eb: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff81e35820-ffffffff81e359b5: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:2860
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff8213647c-ffffffff82136491: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff82036370-ffffffff82036505: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:108
Inline: False
Direct callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff82218104-ffffffff82218119: devlink_dpipe_action_put.cold (STB_LOCAL)
ffffffff8210afd0-ffffffff8210b165: devlink_dpipe_action_put (STB_GLOBAL)
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
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c299d8)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffff800010c299d8-ffff800010c29b64: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3ff2c)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c0d3ff2c-c0d400c0: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1eff0)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c000000000d1eff0-c000000000d1f1e4: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a186c)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffe0007a186c-ffffffe0007a19a6: devlink_dpipe_action_put (STB_GLOBAL)
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
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81920f80)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81920f80-ffffffff81921102: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dad30)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff818dad30-ffffffff818daeb2: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81972110)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81972110-ffffffff81972292: devlink_dpipe_action_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_dpipe_action_put(struct sk_buff *skb, struct devlink_dpipe_action *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81994790)
Location: net/core/devlink.c:1734
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81994790-ffffffff81994912: devlink_dpipe_action_put (STB_GLOBAL)
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
