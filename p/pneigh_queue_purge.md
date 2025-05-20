# Function: <code>pneigh_queue_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81724340)
Location: net/core/neighbour.c:185
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_table_clear
```
**Symbols:**

```
ffffffff81724340-ffffffff81724375: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8178ddd0)
Location: net/core/neighbour.c:185
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff8178ddd0-ffffffff8178de05: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bb6a0)
Location: net/core/neighbour.c:186
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff817bb6a0-ffffffff817bb6d5: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817d9f10)
Location: net/core/neighbour.c:222
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff817d9f10-ffffffff817d9f45: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818546b0)
Location: net/core/neighbour.c:222
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff818546b0-ffffffff818546e5: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189fd00)
Location: net/core/neighbour.c:225
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff8189fd00-ffffffff8189fd35: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c26d0)
Location: net/core/neighbour.c:279
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff818c26d0-ffffffff818c2705: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8190ed90)
Location: net/core/neighbour.c:279
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff8190ed90-ffffffff8190edc5: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81941400)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff81941400-ffffffff81941435: pneigh_queue_purge (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff81a1585d)
Location: net/core/neighbour.c:276
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
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
In net/core/neighbour.c (ffffffff81a15b4d)
Location: net/core/neighbour.c:278
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
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
In net/core/neighbour.c (ffffffff819fc6bd)
Location: net/core/neighbour.c:282
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
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
In net/core/neighbour.c (ffffffff81aae6e7)
Location: net/core/neighbour.c:282
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c23ce0)
Location: net/core/neighbour.c:310
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
```
**Symbols:**

```
ffffffff81c23ce0-ffffffff81c23e96: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list, struct net *net, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd6270)
Location: net/core/neighbour.c:343
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
```
**Symbols:**

```
ffffffff81dd6270-ffffffff81dd647a: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list, struct net *net, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e470b0)
Location: net/core/neighbour.c:343
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
```
**Symbols:**

```
ffffffff81e470b0-ffffffff81e472ba: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list, struct net *net, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f05ec0)
Location: net/core/neighbour.c:351
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
```
**Symbols:**

```
ffffffff81f05ec0-ffffffff81f060ca: pneigh_queue_purge (STB_LOCAL)
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
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be2650)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffff800010be2650-ffff800010be26b0: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfb670)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
c0cfb670-c0cfb6c8: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc4900)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
c000000000cc4900-c000000000cc49a4: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076786e)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffe00076786e-ffffffe0007678d4: pneigh_queue_purge (STB_LOCAL)
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
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e13d0)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff818e13d0-ffffffff818e1405: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189b210)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff8189b210-ffffffff8189b245: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81932400)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff81932400-ffffffff81932435: pneigh_queue_purge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pneigh_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81953ad0)
Location: net/core/neighbour.c:276
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_ifdown
```
**Symbols:**

```
ffffffff81953ad0-ffffffff81953b05: pneigh_queue_purge (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int family</code>
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
