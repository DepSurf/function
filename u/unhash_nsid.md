# Function: <code>unhash_nsid</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81887be0)
Location: net/core/net_namespace.c:479
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff818a86f0)
Location: net/core/net_namespace.c:479
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff818f3cc7)
Location: net/core/net_namespace.c:517
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81925c77)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unhash_nsid(struct net *net, struct net *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8390)
Location: net/core/net_namespace.c:525
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff819f8390-ffffffff819f8475: unhash_nsid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unhash_nsid(struct net *net, struct net *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f7c60)
Location: net/core/net_namespace.c:526
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff819f7c60-ffffffff819f7d45: unhash_nsid (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff819de487)
Location: net/core/net_namespace.c:517
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81a8e1c7)
Location: net/core/net_namespace.c:517
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81c040f7)
Location: net/core/net_namespace.c:516
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db3807)
Location: net/core/net_namespace.c:535
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e23eb7)
Location: net/core/net_namespace.c:536
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81ee1e17)
Location: net/core/net_namespace.c:540
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffff800010bc0ea8)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (c0cdc058)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (c000000000c9b980)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffe00074dccc)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff818c5c77)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff8187fbb7)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81916c77)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In net/core/net_namespace.c (ffffffff81937e87)
Location: net/core/net_namespace.c:519
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
</ul>
