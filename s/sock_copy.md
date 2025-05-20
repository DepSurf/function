# Function: <code>sock_copy</code>

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
In net/core/sock.c (ffffffff81703cde)
Location: net/core/sock.c:1302
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8176a76a)
Location: net/core/sock.c:1302
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8179788a)
Location: net/core/sock.c:1310
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff817b545a)
Location: net/core/sock.c:1431
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8182d8da)
Location: net/core/sock.c:1439
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81877c7c)
Location: net/core/sock.c:1451
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8189815c)
Location: net/core/sock.c:1447
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff818e26bc)
Location: net/core/sock.c:1573
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8191488c)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6def)
Location: net/core/sock.c:1662
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e661f)
Location: net/core/sock.c:1654
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff819cc42f)
Location: net/core/sock.c:1677
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81a7ba7f)
Location: net/core/sock.c:1800
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81bef913)
Location: net/core/sock.c:1934
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_copy(struct sock *nsk, const struct sock *osk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d99370)
Location: net/core/sock.c:1999
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81d99370-ffffffff81d99442: sock_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_copy(struct sock *nsk, const struct sock *osk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e07690)
Location: net/core/sock.c:2057
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81e07690-ffffffff81e07762: sock_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_copy(struct sock *nsk, const struct sock *osk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3e80)
Location: net/core/sock.c:2037
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81ec3e80-ffffffff81ec3f52: sock_copy (STB_LOCAL)
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
In net/core/sock.c (ffff800010bad700)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (c0ccb2c0)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (c000000000c82fec)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffe00073f93a)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff818b488c)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8186e7dc)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8190588c)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff819268ae)
Location: net/core/sock.c:1575
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
