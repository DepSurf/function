# Function: <code>inet_frag_rbtree_purge</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81915be0)
Location: net/ipv4/ip_fragment.c:756
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81915be0-ffffffff81915c5d: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cee20)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff819cee20-ffffffff819cee94: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a059b0)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81a059b0-ffffffff81a05a24: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af50a0)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81af50a0-ffffffff81af5114: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b01ea0)
Location: net/ipv4/inet_fragment.c:263
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81b01ea0-ffffffff81b01f14: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aed7b0)
Location: net/ipv4/inet_fragment.c:263
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81aed7b0-ffffffff81aed824: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81badb70)
Location: net/ipv4/inet_fragment.c:263
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81badb70-ffffffff81badbe4: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81d40be0)
Location: net/ipv4/inet_fragment.c:263
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81d40be0-ffffffff81d40c69: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f09930)
Location: net/ipv4/inet_fragment.c:264
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81f09930-ffffffff81f099c0: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f69440)
Location: net/ipv4/inet_fragment.c:264
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81f69440-ffffffff81f694d0: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8202fac0)
Location: net/ipv4/inet_fragment.c:264
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff8202fac0-ffffffff8202fb50: inet_frag_rbtree_purge (STB_GLOBAL)
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
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbe720)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffff800010cbe720-ffff800010cbe7a0: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dca0a4)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
c0dca0a4-c0dca120: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dd8e50)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
c000000000dd8e50-c000000000dd8f44: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000814766)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffe000814766-ffffffe0008147dc: inet_frag_rbtree_purge (STB_GLOBAL)
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
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a5750)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff819a5750-ffffffff819a57c4: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8195f210)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff8195f210-ffffffff8195f284: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a0fff0)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81a0fff0-ffffffff81a10064: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int inet_frag_rbtree_purge(struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1a840)
Location: net/ipv4/inet_fragment.c:232
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/inet_fragment.c:inet_frag_destroy
```
**Symbols:**

```
ffffffff81a1a840-ffffffff81a1a8b4: inet_frag_rbtree_purge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum skb_drop_reason reason</code>
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
