# Function: <code>rawv6_push_pending_frames</code>

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
In net/ipv6/raw.c (ffffffff817e65ca)
Location: net/ipv6/raw.c:537
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81854993)
Location: net/ipv6/raw.c:537
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff818866a6)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff818acbe2)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff8192f58a)
Location: net/ipv6/raw.c:542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff8198826a)
Location: net/ipv6/raw.c:542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff819bec7c)
Location: net/ipv6/raw.c:541
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81a2db83)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81a646ee)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5b830)
Location: net/ipv6/raw.c:539
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b5b830-ffffffff81b5ba05: rawv6_push_pending_frames (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b6a080)
Location: net/ipv6/raw.c:539
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b6a080-ffffffff81b6a249: rawv6_push_pending_frames (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b583b0)
Location: net/ipv6/raw.c:539
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b583b0-ffffffff81b58579: rawv6_push_pending_frames (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81c1f740)
Location: net/ipv6/raw.c:539
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81c1f740-ffffffff81c1f909: rawv6_push_pending_frames (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81dbc350)
Location: net/ipv6/raw.c:505
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81dbc350-ffffffff81dbc533: rawv6_push_pending_frames (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:505
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81f8d5d0-ffffffff81f8d814: rawv6_push_pending_frames (STB_LOCAL)
ffffffff820b469c-ffffffff820b46c4: rawv6_push_pending_frames.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:504
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81fedb00-ffffffff81fedd4d: rawv6_push_pending_frames (STB_LOCAL)
ffffffff82135741-ffffffff82135762: rawv6_push_pending_frames.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rawv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct raw6_sock *rp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:504
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff820bb710-ffffffff820bb95d: rawv6_push_pending_frames (STB_LOCAL)
ffffffff8221724b-ffffffff8221726c: rawv6_push_pending_frames.cold (STB_LOCAL)
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
In net/ipv6/raw.c (ffff800010d2a574)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (c0e2e5e4)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (c000000000e5b750)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffe00086ad5a)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81a03d7e)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff819c0b3e)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81a6e7fe)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81a7ae27)
Location: net/ipv6/raw.c:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
