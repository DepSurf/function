# Function: <code>net_free</code>

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
In net/core/net_namespace.c (ffffffff81710be8)
Location: net/core/net_namespace.c:338
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff81778519)
Location: net/core/net_namespace.c:338
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff817a593a)
Location: net/core/net_namespace.c:352
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff817c3ba9)
Location: net/core/net_namespace.c:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff8183d669)
Location: net/core/net_namespace.c:375
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff81887b10)
Location: net/core/net_namespace.c:397
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff818a8620)
Location: net/core/net_namespace.c:397
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff818f3bf2)
Location: net/core/net_namespace.c:435
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff81925ba2)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff819f8136)
Location: net/core/net_namespace.c:442
Inline: True
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
In net/core/net_namespace.c (ffffffff819f7f06)
Location: net/core/net_namespace.c:443
Inline: True
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
In net/core/net_namespace.c (ffffffff819dde56)
Location: net/core/net_namespace.c:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8e0c0)
Location: net/core/net_namespace.c:429
Inline: True
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
```
**Symbols:**

```
ffffffff81a8e0c0-ffffffff81a8e117: net_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c03fd0)
Location: net/core/net_namespace.c:428
Inline: True
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
```
**Symbols:**

```
ffffffff81c03fd0-ffffffff81c04044: net_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db36d0)
Location: net/core/net_namespace.c:441
Inline: True
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
```
**Symbols:**

```
ffffffff81db36d0-ffffffff81db3744: net_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e23d80)
Location: net/core/net_namespace.c:442
Inline: True
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
```
**Symbols:**

```
ffffffff81e23d80-ffffffff81e23df4: net_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee1ce0)
Location: net/core/net_namespace.c:446
Inline: True
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
```
**Symbols:**

```
ffffffff81ee1ce0-ffffffff81ee1d54: net_free (STB_LOCAL)
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
In net/core/net_namespace.c (ffff800010bc04dc)
Location: net/core/net_namespace.c:436
Inline: True
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
In net/core/net_namespace.c (c0cdbf34)
Location: net/core/net_namespace.c:436
Inline: True
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
In net/core/net_namespace.c (c000000000c9b820)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void net_free(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074d77e)
Location: net/core/net_namespace.c:436
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffe00074d77e-ffffffe00074d7c0: net_free (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff818c5ba2)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff8187fae2)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff81916ba2)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
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
In net/core/net_namespace.c (ffffffff81937db2)
Location: net/core/net_namespace.c:436
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_drop_ns
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
