# Function: <code>devlink_dpipe_value_put</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81947fb0)
Location: net/core/devlink.c:1930
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81947fb0-ffffffff8194805c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d2c0)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff8197d2c0-ffffffff8197d36c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a50a30)
Location: net/core/devlink.c:1964
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a50a30-ffffffff81a50adc: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56d00)
Location: net/core/devlink.c:2296
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a56d00-ffffffff81a56dac: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39cd0)
Location: net/core/devlink.c:2499
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81a39cd0-ffffffff81a39d7c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3061
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81af0710-ffffffff81af07d0: devlink_dpipe_value_put (STB_LOCAL)
ffffffff81d3837f-ffffffff81d38394: devlink_dpipe_value_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3576
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81c73f60-ffffffff81c7402c: devlink_dpipe_value_put (STB_LOCAL)
ffffffff81f04d92-ffffffff81f04da7: devlink_dpipe_value_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3840
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff81e2ca00-ffffffff81e2cacc: devlink_dpipe_value_put (STB_LOCAL)
ffffffff820acda2-ffffffff820acdb7: devlink_dpipe_value_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3058
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff82030760-ffffffff8203082c: devlink_dpipe_value_put (STB_LOCAL)
ffffffff821363cd-ffffffff821363e2: devlink_dpipe_value_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:305
Inline: False
Direct callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
```
**Symbols:**

```
ffffffff8210a5f0-ffffffff8210a6bc: devlink_dpipe_value_put (STB_LOCAL)
ffffffff822180c6-ffffffff822180db: devlink_dpipe_value_put.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c24e78)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffff800010c24e78-ffff800010c24f3c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c0a0)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c0d3c0a0-c0d3c170: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d189d0)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
c000000000d189d0-c000000000d18ad0: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079d34e)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffe00079d34e-ffffffe00079d3ce: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d130)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff8191d130-ffffffff8191d1dc: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d6ee0)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff818d6ee0-ffffffff818d6f8c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e2c0)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff8196e2c0-ffffffff8196e36c: devlink_dpipe_value_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_dpipe_value_put(struct sk_buff *skb, struct devlink_dpipe_value *value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81990750)
Location: net/core/devlink.c:1932
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81990750-ffffffff819907fc: devlink_dpipe_value_put (STB_LOCAL)
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
