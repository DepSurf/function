# Function: <code>decode_session6</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e8506)
Location: net/xfrm/xfrm_policy.c:3375
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffff81a1f516)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11bf0)
Location: net/xfrm/xfrm_policy.c:3367
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b11bf0-ffffffff81b11fcb: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b202f0)
Location: net/xfrm/xfrm_policy.c:3388
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b202f0-ffffffff81b206cb: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0e1d0)
Location: net/xfrm/xfrm_policy.c:3353
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b0e1d0-ffffffff81b0e58e: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd1600)
Location: net/xfrm/xfrm_policy.c:3358
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81bd1600-ffffffff81bd1a74: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d67710)
Location: net/xfrm/xfrm_policy.c:3361
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81d67710-ffffffff81d67bf7: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f32770)
Location: net/xfrm/xfrm_policy.c:3435
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f32770-ffffffff81f32c57: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void decode_session6(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f93900)
Location: net/xfrm/xfrm_policy.c:3445
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f93900-ffffffff81f93dd8: decode_session6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205b570)
Location: net/xfrm/xfrm_policy.c:3426
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffff800010cdb4ac)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (c0de5e18)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (c000000000e004dc)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffe00082cde0)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffff819beba6)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffff8197b996)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffff81a29626)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
In net/xfrm/xfrm_policy.c (ffffffff81a34bb6)
Location: net/xfrm/xfrm_policy.c:3377
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
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
</ul>
