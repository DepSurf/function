# Function: <code>cn_queue_alloc_callback_entry</code>

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
In drivers/connector/cn_queue.c (ffffffff81541774)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff815930b4)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff815c0974)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff815d64b4)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff8163d284)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff81678895)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff81697975)
Location: drivers/connector/cn_queue.c:35
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff816d04f5)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff816f4315)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct cn_callback_entry *cn_queue_alloc_callback_entry(struct cn_queue_dev *dev, const char *name, struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:21
Inline: False
Direct callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
**Symbols:**

```
ffffffff817ac9a0-ffffffff817aca21: cn_queue_alloc_callback_entry (STB_LOCAL)
ffffffff817acd11-ffffffff817acd22: cn_queue_alloc_callback_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct cn_callback_entry *cn_queue_alloc_callback_entry(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/connector/cn_queue.c (0)
Location: drivers/connector/cn_queue.c:21
Inline: False
Direct callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
**Symbols:**

```
ffffffff817c1570-ffffffff817c15f1: cn_queue_alloc_callback_entry (STB_LOCAL)
ffffffff81c0d87b-ffffffff81c0d88c: cn_queue_alloc_callback_entry.cold (STB_LOCAL)
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
In drivers/connector/cn_queue.c (ffffffff817a4b5d)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff818304dd)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff819717dd)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cn_callback_entry *cn_queue_alloc_callback_entry(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81adc860)
Location: drivers/connector/cn_queue.c:21
Inline: False
Direct callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
**Symbols:**

```
ffffffff81adc860-ffffffff81adc8f7: cn_queue_alloc_callback_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cn_callback_entry *cn_queue_alloc_callback_entry(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81b2aad0)
Location: drivers/connector/cn_queue.c:21
Inline: False
Direct callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
**Symbols:**

```
ffffffff81b2aad0-ffffffff81b2ab67: cn_queue_alloc_callback_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cn_callback_entry *cn_queue_alloc_callback_entry(struct cn_queue_dev *dev, const char *name, const struct cb_id *id, void (*callback)(struct cn_msg *, struct netlink_skb_parms *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/cn_queue.c (ffffffff81b81d50)
Location: drivers/connector/cn_queue.c:21
Inline: False
Direct callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
**Symbols:**

```
ffffffff81b81d50-ffffffff81b81e16: cn_queue_alloc_callback_entry (STB_LOCAL)
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
In drivers/connector/cn_queue.c (ffff8000108dd338)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (c09cc6d8)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (c000000000970b5c)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffe000573c4e)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff816b9b05)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff81697745)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff816e7fd5)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
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
In drivers/connector/cn_queue.c (ffffffff817026d5)
Location: drivers/connector/cn_queue.c:21
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
