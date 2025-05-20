# Function: <code>cn_queue_add_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81541760)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81541760-ffffffff81541875: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff815930a0)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff815930a0-ffffffff815931b5: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff815c0960)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff815c0960-ffffffff815c0a75: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff815d64a0)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff815d64a0-ffffffff815d65b5: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff8163d270)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff8163d270-ffffffff8163d385: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81678b45-ffffffff81678b5b: cn_queue_add_callback.cold.7 (STB_LOCAL)
ffffffff81678890-ffffffff81678989: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:73
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81697c35-ffffffff81697c4b: cn_queue_add_callback.cold.6 (STB_LOCAL)
ffffffff81697970-ffffffff81697a72: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff816d07b1-ffffffff816d07c7: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff816d04f0-ffffffff816d05f5: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff816f45d1-ffffffff816f45e7: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff816f4310-ffffffff816f4415: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff817acaa0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff817acaa0-ffffffff817acb5b: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff817c1670)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff817c1670-ffffffff817c172b: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81bffbea-ffffffff81bffc00: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff817a4b40-ffffffff817a4c45: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81d02336-ffffffff81d0234c: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff818304c0-ffffffff818305c5: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81eca8cf-ffffffff81eca8e5: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff819717c0-ffffffff819718da: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81adc9e0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81adc9e0-ffffffff81adcab0: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81b2ac50)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81b2ac50-ffffffff81b2ad20: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81b81f00)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81b81f00-ffffffff81b81fd0: cn_queue_add_callback (STB_GLOBAL)
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
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffff8000108dd308)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffff8000108dd308-ffff8000108dd4c8: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (c09cc6c4)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
c09cc6c4-c09cc800: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (c000000000970b30)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
c000000000970b30-c000000000970cf0: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffe000573c2a)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffe000573c2a-ffffffe000573d88: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff816b9dc1-ffffffff816b9dd7: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff816b9b00-ffffffff816b9c05: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81697a01-ffffffff81697a17: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff81697740-ffffffff81697845: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff816e8291-ffffffff816e82a7: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff816e7fd0-ffffffff816e80d5: cn_queue_add_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cn_queue_add_callback(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:59
Inline: False
Direct callers:
  - drivers/connector/connector.c:cn_add_callback
```
**Symbols:**

```
ffffffff81702991-ffffffff817029a7: cn_queue_add_callback.cold (STB_LOCAL)
ffffffff817026d0-ffffffff817027d5: cn_queue_add_callback (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct cb_id *id</code> ➡️ <code>const struct cb_id *id</code>
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
