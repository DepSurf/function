# Function: <code>decode_session4</code>

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
In net/xfrm/xfrm_policy.c (ffffffff819e8653)
Location: net/xfrm/xfrm_policy.c:3266
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
In net/xfrm/xfrm_policy.c (ffffffff81a1f663)
Location: net/xfrm/xfrm_policy.c:3268
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
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b12280)
Location: net/xfrm/xfrm_policy.c:3258
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b12280-ffffffff81b12699: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b206d0)
Location: net/xfrm/xfrm_policy.c:3279
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b206d0-ffffffff81b20ae9: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0d210)
Location: net/xfrm/xfrm_policy.c:3278
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81b0d210-ffffffff81b0d4c6: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd11b0)
Location: net/xfrm/xfrm_policy.c:3283
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81bd11b0-ffffffff81bd1469: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d67400)
Location: net/xfrm/xfrm_policy.c:3286
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81d67400-ffffffff81d67704: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f32450)
Location: net/xfrm/xfrm_policy.c:3360
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f32450-ffffffff81f32754: decode_session4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void decode_session4(struct sk_buff *skb, struct flowi *fl, bool reverse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f93600)
Location: net/xfrm/xfrm_policy.c:3370
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
**Symbols:**

```
ffffffff81f93600-ffffffff81f938e3: decode_session4 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff8205b632)
Location: net/xfrm/xfrm_policy.c:3392
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
In net/xfrm/xfrm_policy.c (ffff800010cdb604)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (c0de6000)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (c000000000e00710)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (ffffffe00082cf0c)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (ffffffff819becf3)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (ffffffff8197bae3)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (ffffffff81a29773)
Location: net/xfrm/xfrm_policy.c:3268
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
In net/xfrm/xfrm_policy.c (ffffffff81a34d03)
Location: net/xfrm/xfrm_policy.c:3268
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
