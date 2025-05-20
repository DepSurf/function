# Function: <code>nexthop_free_rcu</code>

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
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff819d5f6c-ffffffff819d5f7f: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff819d3610-ffffffff819d36a1: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a180)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff81a0a180-ffffffff81a0a21a: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc650)
Location: net/ipv4/nexthop.c:107
Inline: False
```
**Symbols:**

```
ffffffff81afc650-ffffffff81afc77a: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09d20)
Location: net/ipv4/nexthop.c:238
Inline: False
```
**Symbols:**

```
ffffffff81b09d20-ffffffff81b09e4a: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af5ac0)
Location: net/ipv4/nexthop.c:504
Inline: False
```
**Symbols:**

```
ffffffff81af5ac0-ffffffff81af5c08: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:504
Inline: False
```
**Symbols:**

```
ffffffff81d3e0f1-ffffffff81d3e11a: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff81bb63c0-ffffffff81bb652c: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:505
Inline: False
```
**Symbols:**

```
ffffffff81f0a9cf-ffffffff81f0a9f8: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff81d49fd0-ffffffff81d4a14b: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:505
Inline: False
```
**Symbols:**

```
ffffffff820b2284-ffffffff820b22ad: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff81f13650-ffffffff81f137cb: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:505
Inline: False
```
**Symbols:**

```
ffffffff82133434-ffffffff8213345d: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff81f73320-ffffffff81f7349b: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:505
Inline: False
```
**Symbols:**

```
ffffffff82214e40-ffffffff82214e69: nexthop_free_rcu.cold (STB_LOCAL)
ffffffff82039930-ffffffff82039aab: nexthop_free_rcu (STB_GLOBAL)
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
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc3618)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffff800010cc3618-ffff800010cc3710: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcedf8)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
c0dcedf8-c0dceee4: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000ddf220)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
c000000000ddf220-c000000000ddf384: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000818918)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffe000818918-ffffffe0008189d0: nexthop_free_rcu (STB_GLOBAL)
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
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819a9f20)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff819a9f20-ffffffff819a9fba: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819639e0)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff819639e0-ffffffff81963a7a: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a147c0)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff81a147c0-ffffffff81a1485a: nexthop_free_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nexthop_free_rcu(struct callback_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f1d0)
Location: net/ipv4/nexthop.c:89
Inline: False
```
**Symbols:**

```
ffffffff81a1f1d0-ffffffff81a1f26a: nexthop_free_rcu (STB_GLOBAL)
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
